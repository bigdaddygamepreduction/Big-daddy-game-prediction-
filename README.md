<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Source Code Viewer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f9;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        pre {
            background-color: #1e1e1e;
            color: #d4d4d4;
            padding: 20px;
            border-radius: 8px;
            overflow-x: auto;
            font-family: 'Courier New', Courier, monospace;
            font-size: 14px;
            line-height: 1.5;
        }
        code {
            white-space: pre-wrap;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Source Code of index (6) (5).html</h1>
        <pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
    &lt;title&gt;Deposit Screenshot&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;h1&gt;Deposit Screenshot&lt;/h1&gt;
    &lt;input type="file" id="screenshot" accept="image/*"&gt;
    &lt;button onclick="next()"&gt;Next&lt;/button&gt;

    &lt;h1&gt;Registration Process Video&lt;/h1&gt;
    &lt;video width="320" height="240" controls&gt;
        &lt;source src="registration.mp4" type="video/mp4"&gt;
        Your browser does not support the video tag.
    &lt;/video&gt;
    &lt;button onclick="submitVideo()"&gt;Submit&lt;/button&gt;

    &lt;h1&gt;Login Interface&lt;/h1&gt;
    &lt;p style="color: red;"&gt;Invalid approval code. Please try again.&lt;/p&gt;
    &lt;input type="text" id="approvalCode"&gt;
    &lt;button onclick="submitCode()"&gt;Submit&lt;/button&gt;

    &lt;h1&gt;Big Daddy Game Wingo Prediction&lt;/h1&gt;
    &lt;input type="text" id="prediction" placeholder="Please enter exactly 6 digits."&gt;
    &lt;button onclick="submitPrediction()"&gt;Submit&lt;/button&gt;
&lt;/body&gt;
&lt;/html&gt;</code></pre>
    </div>
</body>
</html>
