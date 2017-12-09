<!DOCTYPE html>
<html>
<head>
<style>
button.accordion {
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

button.accordion.active, button.accordion:hover {
    background-color: #ccc;
}

div.panel {
    padding: 0 18px;
    display: none;
    background-color: white;
}
</style>
</head>
<body>

<h2>Accordion</h2>

<button class="accordion">Snuba</button>
<div class="panel">
  <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>

  </p>
</div>

<button class="accordion">sailing</button>
<div class="panel">
    <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">aquanots</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">skimboarding</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">kayaking</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">paddleboarding</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">bubbleheads/snorkeling</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">freediving</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">OFZ</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">high dive + zip line</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">canoeing</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>

<button class="accordion">beach biking</button>
<div class="panel">
   <p>tide range: x ft to x ft </p>
  <p>	 ideal tide range: xft to xft</p>
  <p> link to procedures and more </p>
</div>


<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
    acc[i].onclick = function(){
        this.classList.toggle("active");
        var panel = this.nextElementSibling;
        if (panel.style.display === "block") {
            panel.style.display = "none";
        } else {
            panel.style.display = "block";
        }
    }
}
</script>

</body>
</html>

