<h1 align="center"> Data Science Projects Portfolio </h1>

<table>
<thead>
  <tr>
    <th colspan=2>Supervised Learning Projects</th>
  <tr>
    <th>S.No</th>
    <th>Name</th> 
    <th>Link</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>California Housing Price Prediction</td>
    <td>[![index-finger-flat-red-and-white-colors-rounded-vector-5284402](https://user-images.githubusercontent.com/66127023/229487991-9dfb37a1-9f8e-42ac-99d8-73c3d04a70ae.jpg)](https://github.com/santhulak/Streamlit_WebApplication_Apps/tree/main/California%20Housing%20Price%20Prediction)
</td>
    
  </tr>
</tbody>

</table>

## Regression Problem Statements

### [California Housing Price Prediction](https://github.com/santhulak/Streamlit_WebApplication_Apps/tree/main/California%20Housing%20Price%20Prediction)
### [Iris Flower Classification](https://github.com/santhulak/Streamlit_WebApplication_Apps/tree/main/Iris%20Flower%20Classification)

## Classification Problem Statements

### [Diabetis Prediction](https://github.com/santhulak/Streamlit_WebApplication_Apps/tree/main/Diabetes%20Prediction)
### [Heart Disease Prediction](https://github.com/santhulak/Streamlit_WebApplication_Apps/tree/main/Heart%20Disease%20Prediction)
### [Loan Eligibility Prediction](https://github.com/santhulak/Streamlit_WebApplication_Apps/tree/main/Loan%20Eligibility%20Prediction)


Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

| S.No          | Name          |Category   | Dataset        | Code | 
| ------------- |:-------------:| ----------:|--------------:|------:|
| 1             | California Housing Price Prediction | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

S.No | Name | Category | Dataset | Code|
---  |: ---  |: --- |: --- |: --- |: ---|
1 | California Housing Price Prediction | Regression | [house_prices.csv](https://github.com/santhulak/Machine-learning-projects/blob/main/House%20Price%20Prediction/house_prices.csv) |[Click to View Code](https://github.com/santhulak/Machine-learning-projects/tree/main/House%20Price%20Prediction)


<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #ccc; 
}

.panel {
  padding: 0 18px;
  display: none;
  background-color: white;
  overflow: hidden;
}
</style>
</head>
<body>

<h2>Accordion</h2>

<button class="accordion">Section 1</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">Section 2</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">Section 3</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
</script>

</body>
</html>


