<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ncho</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #50c9f8c4;
        }

        .profile-container {
            text-align: center;
            width: 300px;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .profile-pic {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
        }

        .profile-name {
            font-size: 22px;
            font-weight: bold;
            color: #333;
            margin-bottom: 10px;
        }

        .profile-bio {
            font-size: 14px;
            color: #666;
            margin-bottom: 20px;
        }

        .social-links {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .social-link {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 10px;
            background-color: #f0f0f0;
            border-radius: 8px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }

        .social-link:hover {
            background-color: #e2e2e2;
        }

        .social-link svg {
            margin-right: 8px;
        }
    </style>
</head>
<body>

    <div class="profile-container">
        <!-- Profile Picture -->
        <img src="img/tak tau.jpg" alt="Profile Picture" class="profile-pic">
        
        <!-- Profile Name -->
        <h1 class="profile-name">nicho</h1>
        
       
        <!-- Social Links -->
        <div class="social-links">
            </a>
            <a href="https://www.instagram.com/ncho_titi/?next=%2Fthe_wild_kin%2Fp%2FCbZ5ts2odnC%2F" class="social-link">
                <i data-feather="instagram"></i>
                Instagram
            </a>
            <a href="http://www.youtube.com/@nakergaming223" class="social-link">
                <i data-feather="youTube"></i>
                youtube
            </a>
        </div>
    </div>

    <!-- Feather Icons CDN -->
    <script src="https://unpkg.com/feather-icons"></script>
    <script>
        feather.replace();
    </script>

</body>
</html>
