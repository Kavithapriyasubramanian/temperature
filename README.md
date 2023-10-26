# temp.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Temperature Converter Website using html, css & JavaScript</title>
    <!-- css link -->
    <link rel="stylesheet" href="temp.css" />

    <!-- box icons -->
    <link rel="stylesheet"
  href="https://unpkg.com/boxicons@latest/css/boxicons.min.css">

      <!-- font awesome -->
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

  </head>
  <body>
    <div class="container">
        <div class="temperature-converter">
            <div class="mobile">
                
                <div>
                    <i class='bx bx-signal-4'></i>
                    <i class='bx bx-wifi' ></i>
                    <i class='bx bxs-battery' ></i>
                </div>
            </div>

            <h1 class="title">Temperature Converter</h1>

            <div class="result">
              <span class="result-heading">Result (Celsius)</span>
              <h2 class="celsius-value" id="celsius"></h2>
            </div>

            <!-- input field -->
            <div class="degree-type">
                <!-- for degrees -->
              <div class="degree-field">
                <label for="degree">Degrees</label>
                <input type="number" name="degree" id="degree" />
              </div>

              <!-- for option selection -->
              <div class="temp-field">
                <label for="temp-type">Type</label>
                <select name="temperatures" id="temp-type" autocomplete="on">
                  <option id="fahrenheit" value="fahrenheit">Fahrenheit</option>
                  <option id="kelvin" value="kelvin">Kelvin</option>
                </select>
              </div>
            </div>
            <button id="convert-btn">Convert</button>

        </div>
      </div>
    <!-- script tags -->
    <script src="temp.js"></script>
  </body>
</html>
