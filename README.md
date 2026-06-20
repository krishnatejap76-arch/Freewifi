<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Centered Full Screen Image</title>
    <style>
        /* Reset margins and paddings, ensure the container takes full height */
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background-color: #000; /* Optional: black background for any letterboxing */
            overflow: hidden; /* Prevents scrollbars on mobile */
        }

        /* Flexbox container to center the image perfectly */
        .image-container {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            height: 100%;
        }

        /* Responsive full-screen image rules */
        .image-container img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain; /* Ensures the whole image is visible without distortion */
        }
    </style>
</head>
<body>

    <div class="image-container">
        <img src="https://raw.githubusercontent.com/krishnatejap76-arch/Freewifi/4759d4fddd9c63233c6ac280dd2b30e3788b90b3/monkey.png" alt="Centered Monkey Image">
    </div>

</body>
</html>
