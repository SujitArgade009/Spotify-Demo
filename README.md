# Spotify-Demo
This is my first mini project for Frontend using HTML and CSS (Bootstrap framework).

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spotify - Web Player: Music for everyone</title>
    <link rel="icon" href="./Assets/logo.png">
    <link rel="stylesheet" href="project.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" 
    integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" 
    crossorigin="anonymous" 
    referrerpolicy="no-referrer" 
    />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo+Play:wght@600&family=Montserrat:wght@300;400;500;600;700&family=Poppins&display=swap"  rel="stylesheet">
   
</head>
<body>
    <div class="main">
        <div class="sidebar">
            <div class="nav">
                <div class="nav-option" style="opacity: 1;"> 
                    <i class="fa-solid fa-house"></i>
                    <a href="#">Home</a>
                </div>
                <div class="nav-option">
                    <i class="fa-solid fa-magnifying-glass"></i>
                    <a href="#">Search</a>
                </div>
            </div>
            <div class="library">
                <div class="options">
                    <div class="lib-option nav-option">
                        <img src="./Assets/library_icon.png"/>
                        <a href="#">Your library</a>
                     </div>
                    <div class="icons">
                        <i class="fa-solid fa-plus"></i>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div> 
                </div>
                <div class="lib-box">
                    <div class="box">
                        <p class="box-p1"> Create your first playlist</p>
                        <p class="box-p2">It's easy, We'll help you</p>
                        <button class="badge">Create Playlist</button>
                    </div>
                </div>
                <div class="lib-box">
                    <div class="box">
                        <p class="box-p1"> Let's find some podcasts to follow</p>
                        <p class="box-p2">We'll keep you updated on new episode</p>
                        <button class="badge">Browse podcasts</button>
                    </div>
                </div>
            </div>
        </div>
        <div class="main-content">
            <div class="sticky-nav">
                <div class="sticky-nav-icons">
                    <img src="./Assets/backward_icon.png"/>
                    <img src="./Assets/forward_icon.png" class="hide"/>
                </div>
                <div class="sticky-nav-options">
                    <button class="badge nav-item hide">Explore Premium</button>
                    <button class="badge nav-item dark-badge"><i class="fa-regular fa-circle-down" style="margin-right: 5px;"></i>Install App</button>
                    <i class="fa-solid fa-user nav-item"></i>
                </div>
            </div>
            <h2>Recently Played</h2>
            <div class="cards-container">
                <div class="card">
                    <img src="./Assets/card1img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
            </div>
            <h2>Trending now near you</h2>
            <div class="cards-container">
                <div class="card">
                    <img src="./Assets/card1img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
                <div class="card">
                    <img src="./Assets/card2img.jpeg" class="card-img">
                    <p class="card-title">Tere Bin - India</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
                <div class="card">
                    <img src="./Assets/card3img.jpeg" class="card-img">
                    <p class="card-title">Back To Love - India</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
                <div class="card">
                    <img src="./Assets/card4img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
                <div class="card">
                    <img src="./Assets/card2img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
            </div>
            <h2>Featured Charts</h2>
            <div class="cards-container">
                <div class="card">
                    <img src="./Assets/card5img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - Global</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
                <div class="card">
                    <img src="./Assets/card6img.jpeg" class="card-img">
                    <p class="card-title">Top Songs - India</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
                <div class="card">
                    <img src="./Assets/card1img.jpeg" class="card-img">
                    <p class="card-title">Top 50 - India</p>
                    <p class="card-info">Your daily updates of the most Played...</p>
                </div>
            </div>
            <div class="footer">
                <div class="line"></div>
            </div>
        </div>
        <div class="music-player">
            <div class="album">
                <div class="cover-image">
                    <img src="./Assets/card2img.jpeg" alt="Song Image">
                </div>
                <div class="Description">
                    <p class="Song-title">Day Light</p>
                    <p class="Song-artist">David hassy</p>
                </div>
                <div class="icon">
                    <i class="fa-regular fa-heart"></i>
                </div>  
            </div>
            <div class="player">
                <div class="player-cantrols">
                    <img src="./Assets/player_icon1.png" class="player-cantrol-icon"/>
                    <img src="./Assets/player_icon2.png" class="player-cantrol-icon"/>
                    <img src="./Assets/player_icon3.png" class="player-cantrol-icon" style="opacity: 1; height: 2rem;"/>
                    <img src="./Assets/player_icon4.png" class="player-cantrol-icon"/>
                    <img src="./Assets/player_icon5.png" class="player-cantrol-icon"/>
                </div>
                <div class="playback-bar">
                    <span class="current-time">00:00</span>
                    <input type="range" min="0" max="100" class="progress-bar" step="1">
                    <span class="total-time">03:33</span>
                </div>
            </div>
            <div class="cantrols">
                <div class="cantrols-item">
                    <i class="fa-regular fa-circle-play"></i>
                    <i class="fa-solid fa-microphone-slash"></i>
                    <i class="fa-solid fa-bars"></i>
                    <i class="fa-solid fa-plug"></i>
                    <i class="fa-solid fa-volume-high"></i>
                    <input type="range" min="0" max="100" class="progress2bar" step="1">
                 </div>
            </div>
        </div>
    </div>
</body>
</html>
