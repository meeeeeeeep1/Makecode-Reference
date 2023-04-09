<!DOCTYPE html>
<html>
<head>
  <style>
    .card {
      border: 1px solid #ccc;
      border-radius: 10px;
      box-shadow: 0px 0px 5px #ccc;
      max-width: 200px;
      margin: auto;
      padding: 20px;
      font-family: Helvetica Neue,Arial,Helvetica,sans-serif !important;
    }
    .card h1 {
      font-size: 24px;
      font-weight: bold;
      margin-top: 0px;
      font-family: Helvetica Neue,Arial,Helvetica,sans-serif !important;
    }
    .card p {
      font-size: 15px;
      line-height: 1.5;
      margin-top: 10px;
      font-family: Helvetica Neue,Arial,Helvetica,sans-serif !important;
    }
    .card img {
      max-width: 100%;
      margin: 10px 0px;
    }
    .card button {
      background-color: #d6d6d6;
      border: none;
      border-radius: 5px;
      color: black;
      cursor: pointer;
      font-size: 18px;
      margin-top: 10px;
      padding: 10px;
      width: 100%;
            font-family: Helvetica Neue,Arial,Helvetica,sans-serif !important;

    }
    .card button:hover {
      background-color: #a3a3a3;
    }
.parent {
display: grid;
grid-template-columns: repeat(15, 1fr);
grid-template-rows: repeat(10, 1fr);
grid-column-gap: 0px;
grid-row-gap: 0px;
}

.div1 { grid-area: 1 / 1 / 5 / 8; }
.div2 { grid-area: 1 / 9 / 5 / 16; }
.div3 { grid-area: 6 / 1 / 10 / 8; }
.div4 { grid-area: 6 / 9 / 10 / 16; }

  </style>
</head>
<body>
 <div class="parent">
<div class="div1">
 <div class="card">
    <h1>CSS Grid Generator</h1>
    <p>A simple tool that helps you format html in a grid</p>
    <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/28963/og-cssgrid.jpg" alt="MakeCode Arcade Cover Image">
    <button onclick="location.href = 'https://cssgrid-generator.netlify.app';">Learn more</button>
  </div> </div>
<div class="div2">
   <div class="card">
    <h1>Makecode Arcade Buttton Test</h1>
    <p>A button tester created for makecode arcade.</p>
    <img src="https://github.com/meeeeeeeep1/Makecode-Reference/blob/main/images/Untitled(5).jpg" alt="MakeCode Arcade Cover Image">
    <button onclick="location.href = 'https://arcade.makecode.com/developer/button-tester';">Learn more</button>
  </div> </div>
<div class="div3"> </div>
<div class="div4"> </div>

</div> 
 
</body>

</html>
