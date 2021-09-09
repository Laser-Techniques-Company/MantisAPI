# MantisAPI
A Simple REST API for mantisbt written in PHP

Note: This is still a work-in-progress. It has not been tested and still does not have functions for all API calls. However, it is extremely simple to add new functions to the class.

Usage:
```
include './MantisAPI.php';
$api = new MantisAPI('http://localhost/mantisbt', 'YOUR_API_KEY_HERE');
```

Examples: See [/examples/](examples/)