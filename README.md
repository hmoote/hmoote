<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>دار غانم للسينما</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #181818;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #222;
            padding: 10px 0;
            text-align: center;
        }

        h1 {
            margin: 0;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .movie {
            width: 250px;
            margin: 10px;
            border: 1px solid #333;
            border-radius: 5px;
            overflow: hidden;
            position: relative;
        }

        .movie img {
            width: 100%;
        }

        .movie .details {
            padding: 10px;
        }

        .movie .details h2 {
            margin-top: 0;
            font-size: 1.2em;
        }

        .movie .details p {
            margin-bottom: 0;
            font-size: 0.9em;
        }

        .movie .button {
            position: absolute;
            bottom: 10px;
            left: 50%;
            transform: translateX(-50%);
            background-color: #f90;
            color: #fff;
            padding: 8px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>دار غانم للسينما</h1>
    </header>

    
