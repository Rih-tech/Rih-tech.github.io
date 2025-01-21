<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Search Engine</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        #searchResults {
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>Search Engine Example</h1>
    <input type="text" id="searchInput" placeholder="Search..." onkeyup="search()">
    <div id="searchResults"></div>

    <script src="search.js"></script>

</body>
</html>
