# media_query
<!DOCTYPE html>
<html lang="en">
  <!-- 
TODO: Change the background color for each device
[lightsalmon] Mobile Devices: 319px — 480px
[powderblue] iPads and Tablets: 481px — 1200px
[limegreen] Laptops: 1201px — 1600px
[seagreen] Desktops: 1601px and more
-->

  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, minimum-scale=1"
    />
    <title>Media Query</title>
    <style>
      body {
        background-color: aquamarine;
      }
      @media (min-width: 319px) and (max-weidth: 480px) {
        body {
          background-color: lightsalmon;
        }
      }
      @media (min-width: 841px) and (max-width: 1200px) {
        body {
          background-color: powderblue;
        }
      }
      @media (min-width: 1201px) and (min-width: 1600px) {
        body {
          background-color: limegreen;
        }
      }
    </style>
  </head>

  <body></body>
</html>
