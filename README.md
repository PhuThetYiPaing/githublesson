# githublesson
<!DOCTYPE html>
<html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>
        Weather Forecast
    </title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Alfa+Slab+One&family=Great+Vibes&family=Montserrat:ital,wght@0,100;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,600;1,700;1,900&family=Pacifico&family=Roboto:wght@400;500;700;900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css"
        integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous" />
    <link rel="stylesheet" href="src/lexus.css" />
</head>

<body>
    <container>
        <h1>
            Weather App
        </h1>

        <form class="search" id="search-form">
            <div class="col-9">
                <input type="search" id="city-input" placeholder="Enter a city" class="control" />
            </div>
            <div class="col-7">
                <input type="submit" id="form-submit" value="Search" class="form-control btn btn-primary shadow-sm">
            </div>
        </form>
        <span>
            <div class="row">
                <div class="col-5">
                    <h2 id="city">
                        Daik-U</h2><br>
                    <h3>Precipitation: 1%
                        <br>
                        Humidity: 66%
                        <br>
                        Wind: 3 mph<br><br>
                    </h3>
                    <h2 class="temperature">
                        <small class="temp" id="degrees">20</small>
                        <small class="units" id="units">
                            <a href="#" id="celsius-link">°C |</a>
                            <a href="#" id="fahrenheit-link">°F</a>
                        </small>
                    </h2>
                </div>

                <div class="col-4">
                    <img src="src/download (1).png" width="250px">
                </div>
                <div class="col">
                    <h4><br><br>
                        <strong>
                            Wednesday
                        </strong><br>
                        10:30
                    </h4>
                    <h5>
                        Sunny<br>
                    </h5>
                </div>
            </div>
        </span>
        <section>
            <div class="row justify-content-end">
                <div class="col-">
                    Today
                </div>
                <div class="col-2">
                    <u>5 days Forecast</u>
                </div>
            </div>
        </section>
        <small>
            <div class="container px-1 py-1">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Thursday</h5>
                                <p class="card-text">Sunny<br>50°C</p>
                                <img src="https://p.kindpng.com/picc/s/178-1780516_download-weather-icon-png-sunny-weather-icon-png.png"
                                    width=58px>
                            </div>
                        </div>
                    </div>
                    <div class="col mx-1">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Friday</h5>
                                <p class="card-text">Sunny<br>40°C</p>
                                <img src="https://p.kindpng.com/picc/s/178-1780516_download-weather-icon-png-sunny-weather-icon-png.png"
                                    width=58px>

                            </div>
                        </div>
                    </div>
                    <div class="col mx-1">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Saturday</h5>
                                <p class="card-text">Sunny<br>53°C</p>
                                <img src="https://www.pngitem.com/pimgs/m/9-99892_simple-weather-icons-sunny-sunny-weather-icon-png.png"
                                    width=70px>

                            </div>
                        </div>
                    </div>
                    <div class="col mx-1">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Sunday</h5>
                                <p class="card-text">Sunny<br>60°C</p>
                                <img src="https://www.pngitem.com/pimgs/m/9-99892_simple-weather-icons-sunny-sunny-weather-icon-png.png"
                                    width=70px>
                            </div>
                        </div>
                    </div>
                    <div class="col mx-1">
                        <div class="card">
                            <div class="card-body">
                                <h5 class="card-title">Monday</h5>
                                <p class="card-text">Sunny<br>57°C</p>
                                <img src="https://www.pngitem.com/pimgs/m/9-99892_simple-weather-icons-sunny-sunny-weather-icon-png.png"
                                    width=70px>

                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </small>
    </container>
</body>
<script src="src/index.js">
</script>

</html>

</html>
