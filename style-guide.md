# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Linear Gradient: hsl(236, 72%, 79%) to hsl(237, 63%, 64%)

### Neutral

- Very Light Grayish Blue: hsl(240, 78%, 98%)
- Light Grayish Blue: hsl(234, 14%, 74%)
- Grayish Blue: hsl(233, 13%, 49%)
- Dark Grayish Blue: hsl(232, 13%, 33%)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Montserrat](https://fonts.google.com/specimen/Montserrat)
- Weight: 700

<h1 class="Yearly ">&dollar;199.99</h1>
<h1 class="professional Yearly ">&dollar;249.99</h1>
<h1 class="Yearly ">&dollar;399.99</h1>

<script>
  function myFunction() {
    var x = document.getElementsByClassName("Monthly");
    if(checkbox.checked=="true"){
    x[0].innerHTML = "&dollar;199.99";
    x[1].innerHTML = "&dollar;249.99";
    x[2].innerHTML = "&dollar;399.99";
  }
}
function myFunction() {
  var y = document.getElementsByClassName("Yearly");
  if{checkbox.checked=false
    y[0].innerHTML = "&dollar;19.99";
    y[1].innerHTML = "&dollar;24.99";
    y[2].innerHTML = "&dollar;39.99";
  }
}
  </script>


  <script>
  function myFunction() {
  var checkbox = document.getElementById("fs");
  var Monthly = document.getElementsByClassName("Monthly ");
  var Yearly = document.getElementsByClassName("Yearly ");
  if (Monthly.style.display[0] == "block") {
    Yearly.style.display[0] = "block";
  } else {
    Monthly.style.display = "block";
  }
  }
  </script>


  <script>
    function myFunction() {
      var checkBox = document.getElementById("fs");
      var Monthly = document.getElementsByClassName("Monthly ");
      var Yearly = document.getElementsByClassName("Yearly ");
      if (checkBox.checked == true) {
        Monthly[0].innerHTML = "&dollar;199.99";
        Monthly[1].innerHTML = "&dollar;249.99";
        Monthly[2].innerHTML = "&dollar;399.99";
      }
      if (checkBox.checked == false) {
        Yearly[0].innerHTML = "&dollar;19.99";
        Yearly[1].innerHTML = "&dollar;24.99";
        Yearly[2].innerHTML = "&dollar;39.99";
      }
    }
  </script>
