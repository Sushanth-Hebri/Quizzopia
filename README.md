<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quizzopia - Your Ultimate Quiz Conduction Platform</title>
    <link rel="icon" href="favicon.png" type="image/x-icon">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }

        .header {
            background-color: #e74c3c;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 30px;
            box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        }

        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }

        .logo {
            width: 100px;
            height: 100px;
            margin: 0 auto;
            display: block;
        }

        .features {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .feature {
            background-color: #3498db;
            color: white;
            text-align: center;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        }

        .premium-button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            display: block;
            margin: 30px auto;
        }
    </style>
</head>

<body>
    <div class="header">
        <h1>Quizzopia</h1>
        <img src="logo.png" alt="Quizzopia Logo" class="logo">
        <p>A site for quiz conduction with your questions</p>
    </div>

    <div class="container">
        <div class="features">
            <div class="feature">
                <h2>Create Custom Quizzes</h2>
                <p>With Quizzopia, you can easily create custom quizzes with your own questions and answers. The intuitive
                    interface makes it simple to add, edit, and organize questions to suit your needs.</p>
            </div>
            <div class="feature">
                <h2>Multiple Question Types</h2>
                <p>Quizzopia supports various question types, including multiple-choice, true/false, and open-ended questions,
                    providing a diverse and engaging experience for participants.</p>
            </div>
            <div class="feature">
                <h2>Premium Pack</h2>
                <p>We offer a premium pack that grants you access to exclusive features, such as advanced quiz analytics,
                    custom branding, and the ability to conduct unlimited quizzes. Upgrade to the premium pack and take your
                    quizzes to the next level!</p>
            </div>
            <div class="feature">
                <h2>User-Friendly Interface</h2>
                <p>Quizzopia is designed to be user-friendly and accessible for users of all skill levels. You don't need to
                    be a tech expert to create and conduct quizzes seamlessly.</p>
            </div>
            <div class="feature">
                <h2>Real-Time Results</h2>
                <p>As a quiz organizer, you can view real-time results and analytics to gauge participants' performance and
                    gain valuable insights into your quizzes' effectiveness.</p>
            </div>
        </div>

        <button class="premium-button">Upgrade to Premium Pack</button>
    </div>
</body>

</html>
