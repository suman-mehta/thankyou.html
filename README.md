<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thank You!</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: #fff;
            text-align: center;
            padding: 50px;
            animation: fadeIn 1s ease-in;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
        }

        h1 {
            color: #ffdd57;
            animation: slideIn 1s ease-in-out;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2em;
            opacity: 0;
            animation: fadeInUp 1s ease-in-out forwards;
            animation-delay: 0.5s;
            line-height: 1.6;
            max-width: 600px;
            margin: 10px 0;
        }

        .button {
            display: inline-block;
            padding: 12px 24px;
            font-size: 1em;
            color: #fff;
            background-color: #ff4081;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 30px;
            opacity: 0;
            animation: fadeInUp 1s ease-in-out forwards;
            animation-delay: 1s;
            transition: background-color 0.3s, transform 0.3s;
        }

        .button:hover {
            background-color: #e91e63;
            transform: scale(1.05);
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideIn {
            from {
                transform: translateY(-20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        @keyframes fadeInUp {
            from {
                transform: translateY(20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        /* Mobile Responsiveness */
        @media (max-width: 600px) {
            body {
                padding: 20px;
            }

            h1 {
                font-size: 2em;
            }

            p {
                font-size: 1em;
            }

            .button {
                font-size: 0.9em;
            }
        }
    </style>
</head>
<body>
    <h1>Thank You!</h1>
    <p>Your support means the world to us. We appreciate your time and effort.</p>
    <a href="index.html" class="button">Go Back Home</a>
</body>
</html>
