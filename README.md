# kamila
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Базарбай Камилланың Профилі</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .profile-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100%;
            width: 100%;
        }

        .profile-card {
            background: white;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            text-align: center;
            width: 350px;
            position: relative;
        }

        .profile-card h1 {
            font-size: 24px;
            margin: 10px 0;
        }

        .profile-card p {
            font-size: 16px;
            margin: 5px 0;
        }

        .profile-card .profile-image {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin: 0 auto 15px;
            border: 3px solid #fad0c4;
            object-fit: cover;
        }

        .portfolio-link {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: #ff9a9e;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 14px;
        }

        .portfolio-link:hover {
            background: #fad0c4;
            color: black;
            transition: 0.3s;
        }
    </style>
</head>
<body>
    <div class="profile-container">
        <div class="profile-card">
            <img src="kamilla.jpeg" alt="Камилланың суреті" class="profile-image">
            <h1>Базарбай Камилла</h1>
            <p><strong>Туған күні:</strong> 22.04.2007</p>
            <p><strong>Туған жері:</strong> Шымкент</p>
            <p><strong>Мамандығы:</strong> ФЕК242</p>
            <p><strong>Мамандық коды:</strong> 6В05302</p>
            <p><strong>Қызығушылықтары:</strong> аспаздық, волейбол, ән айту</p>
            <a href="https://kamibazarbai45.wixsite.com/my-site-3" class="portfolio-link">Портфолио</a>
        </div>
    </div>
</body>
</html>
