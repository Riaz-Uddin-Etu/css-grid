# css-grid
You can make your page fully responsive by using this css grid layout.
For your better understanding I write HTML Below. Use these code to understanding.


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>grid</title>
    <link rel="stylesheet" href="grid.css" />
    <link rel="shortcut icon" type="img/png" href="grid.png" />
    <style>
      html {
        font-size: 62.5%; /* 10px */
      }
      body {
        padding: 10px;
        margin: 0;
      }
      p {
        border: 2px dotted black;
      }
      .brd {
        border: 2px dotted #fff;
      }
      .content-Title {
        display: flex;
        justify-content: center;
        align-items: center;
        font-size: 3rem;
      }
      .content-Title h1 {
        border: 4px solid black;
      }
      .col-1-of-2,
      .col-1-of-3,
      .col-2-of-3,
      .col-1-of-4,
      .col-2-of-4,
      .col-3-of-4,
      .col-1-of-6,
      .col-5-of-6,
      .col-1-of-12,
      .col-11-of-12 {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100px;
        font-size: 18px;
      }
      .col-1-of-2 {
        background-color: #129ee1;
      }
      .col-1-of-3 {
        background-color: #e21216;
      }
      .col-2-of-3 {
        background-color: #17c0eb;
      }
      .col-1-of-4 {
        background-color: #12e29a;
      }
      .col-2-of-4 {
        background-color: #129ee1;
      }
      .col-3-of-4 {
        background-color: #1216e2;
      }
      .col-1-of-6 {
        background-color: black;
        color: #ffffff;
      }
      .col-5-of-6 {
        background-color: black;
        color: #ffffff;
      }
      .col-1-of-12 {
        background-color: #ff3838;
      }
      .col-11-of-12 {
        background-color: #ff3838;
      }
    </style>
  </head>
  <body>
    <div class="content-Title"><h1>CSS GRID LAYOUT</h1></div>
    <div class="row">
      <div class="col-1-of-2"><p>1 of 2</p></div>
      <div class="col-1-of-2"><p>1 of 2</p></div>
    </div>
    <div class="row">
      <div class="col-1-of-3"><p>1 of 3</p></div>
      <div class="col-1-of-3"><p>1 of 3</p></div>
      <div class="col-1-of-3"><p>1 of 3</p></div>
    </div>
    <div class="row">
      <div class="col-2-of-3"><p>2 of 3</p></div>
      <div class="col-1-of-3"><p>1 of 3</p></div>
    </div>
    <div class="row">
      <div class="col-1-of-4"><p>1 of 4</p></div>
      <div class="col-1-of-4"><p>1 of 4</p></div>
      <div class="col-1-of-4"><p>1 of 4</p></div>
      <div class="col-1-of-4"><p>1 of 4</p></div>
    </div>
    <div class="row">
      <div class="col-2-of-4"><p>2 of 4</p></div>
      <div class="col-2-of-4"><p>2 of 4</p></div>
    </div>
    <div class="row">
      <div class="col-3-of-4"><p>3 of 4</p></div>
      <div class="col-1-of-4"><p>1 of 4</p></div>
    </div>
    <div class="row">
      <div class="col-1-of-6"><p class="brd">1 of 6</p></div>
      <div class="col-1-of-6"><p class="brd">1 of 6</p></div>
      <div class="col-1-of-6"><p class="brd">1 of 6</p></div>
      <div class="col-1-of-6"><p class="brd">1 of 6</p></div>
      <div class="col-1-of-6"><p class="brd">1 of 6</p></div>
      <div class="col-1-of-6"><p class="brd">1 of 6</p></div>
    </div>
    <div class="row">
      <div class="col-5-of-6"><p class="brd">5 of 6</p></div>
      <div class="col-1-of-6"><p class="brd">1 of 6</p></div>
    </div>
    <div class="row">
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
    </div>
    <div class="row">
      <div class="col-11-of-12"><p>11 of 12</p></div>
      <div class="col-1-of-12"><p>1 of 12</p></div>
    </div>
  </body>
</html>


