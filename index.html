<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List of Domains</title>
</head>
<body>
    <div>
        <?php
        // SiteHost API details
        $api_server = 'https://api.demo.sitehost.co.nz';
        $api_version = '1.0';
        $api_key = 'd17261d51ff7046b760bd95b4ce781ac';
        $client_id = '293785';
        $format = 'json';

        // Construct API endpoint
        $api_endpoint = "$api_server/$api_version/srs/list_domains.$format?client_id=$client_id&apikey=$api_key";

        // Make API request
        $response = file_get_contents($api_endpoint);

        // Check if request was successful
        if ($response === false) {
            echo "Error: Failed to fetch data from the API.";
            exit;
        }

        // Parse JSON response
        $data = json_decode($response, true);

        // Check if JSON decoding was successful
        if ($data === null) {
            echo "Error: Failed to parse JSON response.";
            exit;
        }

        // Check if API returned any domains
        if (empty($data['domains'])) {
            echo "No domains found for customer #$client_id.";
            exit;
        }

        // Output domains
        echo "<h1>Domains for Customer #$client_id</h1>";
        echo "<ul>";
        foreach ($data['domains'] as $domain) {
            echo "<li>$domain</li>";
        }
        echo "</ul>";
        ?>
    </div>
</body>
</html>
