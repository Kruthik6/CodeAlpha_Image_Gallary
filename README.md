# CodeAlpha_Image_Gallary
By this we can enter to the different folder in the gallary


<!DOCTYPE html>
<html lang="en">

  <style>
    .rounded{
     width:300px;
    margin:auto;
    }
     .rounded img {
        border-radius:50%;
    }

        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color:peru;
        }
        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .icon {
            margin: 0 20px;
            text-align: center;
        }
        .icon img {
            width: 100px;
            height: 100px;
            cursor: pointer;
            transition: transform 0.2s;
        }
        .icon img:hover {
            transform: scale(1.1);
        }
        .icon a {
            text-decoration: none;
            color: rgb(52, 33, 138);
            font-size: 18px;
        }
    </style>

<body>
    <h1> IMAGE GALLARY</h1>
    <div class="container">
        
        
        
        
        <div class="rounded">


        <div class="icon">

            <a href="ANIMALS.html">
                <img src="13.png" alt="Icon 1">
                <p>Animals</p>
            </a>
        </div>
        
        <div class="rounded">
        <div class="icon">
            <a href="FLOWERS.html">
                <img src="15.jpeg" alt="Icon 2">
                <p>Flowers</p>
            </a>
        </div>
        
        <div class="rounded">
        <div class="icon">
            <a href="BIRDS.html">
                <img src="14.webp" alt="Icon 3">
                <p>Birds</p>
            </a>
        </div>
    </div>
</body>
</html>
