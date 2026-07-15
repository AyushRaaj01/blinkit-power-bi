# blinkit-power-bi
An interactive Power BI dashboard analyzing Blinkit's sales performance, delivery metrics, and customer buying patterns.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Power BI Blinkit Report</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            overflow: hidden;
            background-color: #f4f6f9;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        }
        .header {
            background-color: #111827;
            color: #ffffff;
            padding: 12px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .header h1 {
            margin: 0;
            font-size: 1.2rem;
            font-weight: 600;
        }
        .container {
            position: absolute;
            top: 50px; /* Aligns below the header */
            bottom: 0;
            left: 0;
            right: 0;
        }
        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>

    <!-- Simple Dashboard Top Bar -->
    <div class="header">
        <h1>Blinkit Sales Dashboard</h1>
    </div>

    <!-- Interactive Power BI Embedded Report -->
    <div class="container">
        <iframe 
            title="Blinkit Sales Dashboard" 
            src="https://app.powerbi.com/view?r=eyJrIjoiYmNkM2ZjMGMtN2MyMy00YzZlLTg5NzktNTViNzA1ODJjMTQ4IiwidCI6ImE4ZjNjYzcyLTZiYTAtNDJlNy1hNjU1LTI3NTA2ZDBiOGI5NCJ9" 
            allowFullScreen="true">
        </iframe>
    </div>

</body>
</html>

