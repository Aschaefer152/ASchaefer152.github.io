!DOCTYPE html>
<html lang="en">
    <!DOCTYPE html>
    <!-- CSS Stylesheets with Relative Paths -->
    <html lang="en-us">
    <head>
      <meta charset="UTF-8">
      <title>CSS Stylesheets with Relative Paths</title>
      <!-- This line is money! It points your HTML to the CSS file. -->
      <!-- Notice the "relative" pathway? It matches a file inside our current directory's "assets" folder. Open it to see our style rules. -->
      <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
      <link rel="stylesheet" type="text/css" href="style.css">
    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-custom">
            <a class="navbar-brand" href="#"></a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
        
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                  <a class="nav-link" href="edits.html">Latitude</a>
                </li>
                <li class="nav-item active">
                  <a class="nav-link" href="comparison.html">Comparison <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="data.html">Data</a>
                </li>
                <li class="nav-item dropdown">
                  <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Plots
                  </a>
                  <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <a class="dropdown-item" href="temp.html">Max Temp</a>
                    <a class="dropdown-item" href="humidity.html">Humidity</a>
                    <a class="dropdown-item" href="cloudiness.html">Cloudiness</a>
                    <a class="dropdown-item" href="wind-speed.html">Wind Speed</a>
                  </div>
                </li>
              </ul>
            </div>
          </nav>
      <div class="container">
        <div class="row">
              <div class ="col-md-8">
                <h2> Summary: Latitude vs. X</h2>
                <img class="float_l" src="../Visualizations/Fig1.png" width="33%">
                <p>The purpose of this project was to analyze how weather changes as you get closer to the equator.  To accomplish this analysis, we first pulled data from the OpenWeatherMap API to assemble a dataset on over 500 cities.</p>
                <p>After assembling the dataset, we used Matplotlib to plot various aspects of weather vs.  latitude. Factors we looked at included: temperature, cloudiness, wing speed, and humidity. This site provides the source data and visualizations created as past of the analysis, as well as explanations and descriptions of any trends and correlations witnessed.</p>
              </div>
              <div class="col-md-4">

                    <h2>Visualizations</h2>
                    <div class="row">
                        <div>
                            <div class="col-2">
                              <a href="temp.html">
                                <img src="../Visualizations/Fig1.png" alt="Temp" width="700%">
                                </a>
                            </div>
                            <div class="col-2">
                              <a href="humidity.html">
                                <img src="../Visualizations/Fig2.png" alt="Humidity"  width="700%">
                              </a>
                            </div>
                        </div>
                        <div>
                            <div class="col-2">
                              <a href="cloudiness.html">
                                <img src="../Visualizations/Fig3.png" alt="Cloudiness"  width="700%">
                              </a>
                            </div>
                            <div class="col-2">
                              <a href="wind-speed.html">
                                <img src="../Visualizations/Fig4.png" alt="Wind Speed"  width="700%">
                              </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
      </div>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>

    </body>
</html>
