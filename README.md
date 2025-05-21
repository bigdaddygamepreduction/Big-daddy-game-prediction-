<!DOCTYPE html>
<html>
<head>
    <title>Deposit Screenshot</title>
</head>
<body>
    <h1>Deposit Screenshot</h1>
    <input type="file" id="screenshot" accept="image/*">
    <button onclick="next()">Next</button>

    <h1>Registration Process Video</h1>
    <video width="320" height="240" controls>
        <source src="registration.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <button onclick="submitVideo()">Submit</button>

    <h1>Login Interface</h1>
    <p style="color: red;">Invalid approval code. Please try again.</p>
    <input type="text" id="approvalCode">
    <button onclick="submitCode()">Submit</button>

    <h1>Big Daddy Game Wingo Prediction</h1>
    <input type="text" id="prediction" placeholder="Please enter exactly 6 digits.">
    <button onclick="submitPrediction()">Submit</button>
</body>
</html>
