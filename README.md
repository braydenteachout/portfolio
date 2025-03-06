<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brayden's Portfolio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }


        #welcome-section {
            height: 100vh;
            background: linear-gradient(to right, #0044cc, #66a3ff);
            color: white;
        }


        .project-tile {
            border: none;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .project-tile:hover {
            transform: scale(1.05);
        }


        .navbar {
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }


        #social-media {
            background-color: #f8f9fa;
        }
        </style>
</head>
<body>


    <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top">
        <div class="container">
            <a class="navbar-brand">Brayden Teachout</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#welcome-section">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#profile">Profile</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>


    <section id="welcome-section" class="d-flex flex-column justify-content-center align-items-center text-center">
        <h1>Hi, I'm Brayden, a Future Developer!</h1>
        <p>Passionate about coding and creating cool projects.</p>
    </section>

    <section id="profile" class="container my-5 p-4 bg-light rounded shadow">
        <h2 class="text-primary">Profile</h2>
        <br>
        <div class="row">
            <div class="col-md-6">
                <h3 class="text-info">My Journey</h3>
                <ul class="list-unstyled">
                    <li>🚀 Started learning to code in 2024</li>
                    <li>💻 Built my first project a month ago</li>
                    <li>🌍 Passionate about building web applications</li>
                </ul>
            </div>
            <div class="col-md-6">
                <h3 class="text-info">About Me</h3>
                <p>
                    I'm passionate about coding and love creating cool projects. 
                    In my free time, I enjoy learning new technologies and solving coding challenges.
                </p>
            </div>
        </div>
    </section>


    <section id="projects" class="container text-center py-5">
        <h2>Projects</h2>
        <div class="row justify-content-center">
            <div class="col-md-6">
                <div class="card project-tile">
                    <div class="card-body">
                        <h5 class="card-title">My Project</h5>
                        <p class="card-text">Check out one of my latest projects!</p>
                        <a href="https://braydenteachout.github.io/" class="btn btn-primary">View Project</a>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <section id="social-media" class="text-center py-5 bg-light">
        <h2>Social Profiles</h2>
        <a href="https://www.codewars.com/users/braydenteachout" class="btn btn-dark m-2">CodeWars</a>
        <a href="https://github.com/braydenteachout" class="btn btn-dark m-2">GitHub</a>
        <a href="https://www.linkedin.com/in/brayden-teachout-71439734b/" class="btn btn-dark m-2">LinkedIn</a>
    </section>


    <section id="contact" class="container text-center py-5">
        <h2>Contact Me</h2>
        <p>Email: bteac328@evit.edu</p>
    </section>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
