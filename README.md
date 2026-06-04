# Project Responsive Web Design using Bootstrap
## Date: 04-06-2026

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Game Changer</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Dribble GameZone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="gamesDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            Games
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="gamesDropdown">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Adventure</a></li>
                            <li><a class="dropdown-item" href="#">RPG</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="communityDropdown" role="button"
                            data-bs-toggle="dropdown" aria-expanded="false">
                            Community
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="communityDropdown">
                            <li><a class="dropdown-item" href="#">Forums</a></li>
                            <li><a class="dropdown-item" href="#">Events</a></li>
                            <li><a class="dropdown-item" href="#">Clans</a></li>
                        </ul>
                    </li>
                    <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
                    <li class="nav-item"><a class="btn btn-outline-primary ms-3" href="#">Sign Up</a></li>
                </ul>

            </div>
        </div>
    </nav>
    <div class="bg-dark text-white text-center py-5">
        <h1 class="display-5">Wanna play a Game?</h1>
        <p class="lead">GameZone is show and tell for gamers and developers.</p>
        <a href="#" class="btn btn-primary me-2">Learn More</a>
        <a href="#" class="btn btn-outline-light">Sign Up</a>
    </div>
    <div class="container py-5">
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card">
                    <img src="fabio-magalhaes-nmTm7knUnqs-unsplash.jpg" class="card-img-top" alt="Superman">
                    <div class="card-body">
                        <h5 class="card-title">Cyberpunk 2077</h5>
                        <div class="stats">👁️ 12.3k &nbsp; ❤️ 1.2k &nbsp; 💬 230</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="florian-olivo-Mf23RF8xArY-unsplash.jpg" class="card-img-top" alt="Batman">
                    <div class="card-body">
                        <h5 class="card-title">Valorant</h5>
                        <div class="stats">👁️ 10.1k &nbsp; ❤️ 900 &nbsp; 💬 180</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="javier-martinez-hUD0PUczwJQ-unsplash.jpg" class="card-img-top" alt="Assassin's Creed">
                    <div class="card-body">
                        <h5 class="card-title">Assassin's Creed</h5>
                        <div class="stats">👁️ 8.7k &nbsp; ❤️ 1.1k &nbsp; 💬 210</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="lorenzo-herrera-p0j-mE6mGo4-unsplash.jpg" class="card-img-top" alt="Halo Infinite">
                    <div class="card-body">
                        <h5 class="card-title">Halo Infinite</h5>
                        <div class="stats">👁️ 9.3k &nbsp; ❤️ 1.0k &nbsp; 💬 190</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="625497.jpg" class="card-img-top" alt="Fortnite">
                    <div class="card-body">
                        <h5 class="card-title">Dragon Ball</h5>
                        <div class="stats">👁️ 162k &nbsp; ❤️ 35k &nbsp; 💬 940</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="mateo-nCU4yq5xDEQ-unsplash.jpg" class="card-img-top" alt="Thor">
                    <div class="card-body">
                        <h5 class="card-title">Thor</h5>
                        <div class="stats">👁️ 17k &nbsp; ❤️ 167k &nbsp; 💬 900</div>
                    </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="card">
                    <img src="2086922.jpg" class="card-img-top" alt="Fortnite">
                    <div class="card-body">
                        <h5 class="card-title">Fortnite</h5>
                        <div class="stats">👁️ 62k &nbsp; ❤️ 15k &nbsp; 💬 30</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="2086892.jpg" class="card-img-top" alt="Cap">
                    <div class="card-body">
                        <h5 class="card-title">Captain America</h5>
                        <div class="stats">👁️ 100k &nbsp; ❤️ 90k &nbsp; 💬 1000</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="1752211.jpg" class="card-img-top" alt="Marvel">
                    <div class="card-body">
                        <h5 class="card-title">Marvel</h5>
                        <div class="stats">👁️ 1002k &nbsp; ❤️ 99k &nbsp; 💬 1000</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="2086822.jpg" class="card-img-top" alt="Avengers">
                    <div class="card-body">
                        <h5 class="card-title">Avengers</h5>
                        <div class="stats">👁️ 13.2k &nbsp; ❤️ 1.5k &nbsp; 💬 300</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="2096216.jpg" class="card-img-top" alt="SpiderMan">
                    <div class="card-body">
                        <h5 class="card-title">SpiderMan</h5>
                        <div class="stats">👁️ 9.9k &nbsp; ❤️ 1.5k &nbsp; 💬 900</div>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="2096210 (1).jpg" class="card-img-top" alt="Fortnite">
                    <div class="card-body">
                        <h5 class="card-title">BlunderGame</h5>
                        <div class="stats">👁️ 83.2k &nbsp; ❤️ 1.5k &nbsp; 💬 300</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p class="mb-1">Designed by</p>
            <p class="mb-2">© Muhilan | 212225240092</p>
        </div>
    </footer>

</body>

</html>
```

## OUTPUT:
<img width="1919" height="1023" alt="Screenshot 2026-06-04 224507" src="https://github.com/user-attachments/assets/8941e24f-36c4-4d7f-a2d8-25f894a976cd" />

<img width="1919" height="1015" alt="Screenshot 2026-06-04 224517" src="https://github.com/user-attachments/assets/4ec0c38a-9cca-4d61-9747-de803f82c981" />



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
