# day11

# detect key presses project

i have created a detect key project using html javascript css
## Step 1: Create the HTML file

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Detect Key Presses</title>
    <!-- Google Fonts -->
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap"
      rel="stylesheet"
    />
    <!-- Stylesheet-->
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div id="result">Press Any Key To Get Started</div>
    <!-- Script -->
    <script src="script.js"></script>
  </body>
</html>

## step 2 create css
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
body {
  height: 100vh;
  background-color: #2887e3;
}
#result {
  background-color:tomato;
  width: 80vw;
  max-width: 600px;
  position: absolute;
  transform: translate(-50%, -50%);
  top: 50%;
  left: 50%;
  padding: 80px 40px;
  text-align: center;
  color: #f5f5f5;
  font-size: 3.6vmin;
  border-radius: 10px;
  box-shadow: 0 10px 50px rgba(0, 0, 0, 0.2);
  font-style: italic;
}
#result span:nth-child(1) {
  color: #2887e3;
  font-size: 3em;
  display: block;
  font-style: normal;
}
#result span:nth-child(2) {
  font-size: 1.5em;
  font-style: normal;

## step 3 : similarly create js file

in the end project ur html file on browse

