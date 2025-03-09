<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Comparison</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .image-container {
            display: flex;
            justify-content: center;
            margin: 20px;
        }
        .image-container img {
            width: 300px;
            margin: 0 20px;
            border: 2px solid #ccc;
            border-radius: 8px;
        }
        .vote-buttons {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            margin: 10px;
            border: none;
            border-radius: 5px;
            background-color: #4CAF50;
            color: white;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <h1>Who is the best?</h1>
    <div class="image-container">
        <div>
           <img src="images/WhatsApp_Image_2025-03-09_at_12.18.45_5b7ad539.jpg" alt="AALU">
        </div>
        <div>
          <img src="images/WhatsApp_Image_2025-03-09_at_12.19.38_0477c0dc.jpg" alt="BRUNO">
        </div>
    </div>

    <div class="vote-buttons">
        <button onclick="alert('You voted for BRUNO!')">Vote for AALU</button>
        <button onclick="alert('You voted for BRUNO!')">Vote for BRUNO</button>
    </div>

</body>
</html>
