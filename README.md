<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Komas Ako Art</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fafafa;
        }

        .header {
            background-color: white;
            padding: 1rem 0;
            box-shadow: 0 1px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .profile {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 2rem;
            background-color: white;
            box-shadow: 0 1px 5px rgba(0, 0, 0, 0.1);
            margin-bottom: 2rem;
        }

        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin-right: 2rem;
        }

        .profile-info {
            text-align: left;
        }

        .profile-info h1 {
            margin: 0;
            font-size: 2rem;
        }

        .profile-info p {
            margin: 0.5rem 0;
            color: #777;
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .photo {
            margin: 0.5rem;
            background-color: white;
            box-shadow: 0 1px 5px rgba(0, 0, 0, 0.1);
        }

        .photo img {
            width: 100%;
            height: auto;
            display: block;
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Komas Ako Art</h1>
    </header>
    <section class="profile">
        <img src="photos/profile.jpg" alt="Profile Picture">
        <div class="profile-info">
            <h1>@komas_ako_art</h1>
            <p>Artist | Illustrator | Designer</p>
            <p>Welcome to my art gallery!</p>
        </div>
    </section>
    <section class="gallery">
        <div class="photo">
            <img src="photos/photo1.jpg" alt="Photo 1">
        </div>
        <div class="photo">
            <img src="photos/photo2.jpg" alt="Photo 2">
        </div>
        <div class="photo">
            <img src="photos/photo3.jpg" alt="Photo 3">
        </div>
        <!-- Add more photos as needed -->
    </section>
</body>
</html>
