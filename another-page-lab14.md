---
layout: default
---


![Splash_IMAGE](./assets/images/splashImage_kidney_zoom2.png)
# Lab 14: Urinary System


### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>

1.  Sketch the flow of blood from the Renal artery all the way to the capillary bed
2.  Go to slide 6 of the Lab Powerpoint and label ALL structures that can bee seen histologically, and identify all the epithelial tissues, connective tissues and indicate where they are located
3.  List ALL the cells of the Juxtaglomerular Complex, and indicate what their function is (include a sketch!)
4.  Sketch a nephron – include the SPECIFIC types of ET throughout the entire NEPHRON & the LOOPS
5.  Indicate what occurs at each segment of the loops of a nephron (what gets resorbed, or excreted etc…)
6.  What is countercurrent exchange?
7.  How is urine Formed? (Look at slide 23-26 and summarize) I will ask you this on the final exam
8.  Draw a detailed glomerulus indicating where all the cells are, and the different poles
9.  Draw a urinary bladder with all of its structures, and also include the external and internal urinary sphincters
10. What is a duct of bellini?
11. What are the different types of epithelium of the male urethra?
12. Sketch a cross-ection of a ureter, and indicate all of its layers.
13. List all pathologies from textbook

</div>
<div id='else-part' style='visibility: hidden'>
  <em>Available starting: 
    <div id="else-part-available-date">_IF_SHOWING_ERROR_DATE_NOT_SET_CORRECTLY_VIA_JS_TO_HTML</div>
  </em>
</div>

<script>
  ////////// -- bypass dateChecks With URL hack
  // Get URL
  var url = window.location.href;
  // Get DIV
  var msg = document.getElementById('if-part');
  // Check if URL contains the keyword
  if( url.search( 'show' ) > 0 ) {
    // Display the message
    msg.style.visibility = "visible";
    msg.style.display = "block";
  }

  ////////// -- enforce date visibility based on date
  //release if-condition if is on or beyond dateToCheck
  var dateToRelease = new Date("11/05/2018");
  var todaysDate = new Date();
  var node;

  // call setHours to take the time out of the comparison
  if(dateToRelease.setHours(0,0,0,0) <= todaysDate.setHours(0,0,0,0)) {
      // Date equals today's date
        node = document.getElementById('if-part');
      node.style.visibility = 'visible';
      node.style.display = 'block';
  }
    else {
        node = document.getElementById('else-part');
      node.style.visibility = 'visible';
      node.style.display = 'inline-block';

      node = document.getElementById('else-part-available-date');
      node.innerHTML = "&nbsp;&nbsp;" + dateToRelease.toLocaleDateString();
      node.style.display = 'inline-block';
      // console.log(node)
    }

</script>
<!-- /////////////////////////////////////////// -->





<a id="jump-to-practice-questions" class="jump-to-section"> </a>
### Practice Questions

<div class="card">
  <div class="card-header">
    <strong>Question 1</strong>
  </div>
  <div class="card-body">
    <p class="card-text">What organ is this?</p>
    <img src="./assets/images/splashImage_kidney.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample01">
      <br>
        <div class="well">
          Kidney
        </div>
    </div>
  </div>  
</div>
<br>
<div class="card">
  <div class="card-header">
    <strong>Question 2</strong>
  </div>
  <div class="card-body">
    <p class="card-text">In this higher magnification view of Question 1, what structure is at the pointer?</p>
    <img src="./assets/images/splashImage_kidney_zoom1.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample02">
      <br>
        <div class="well">
          Glomerulus
        </div>
    </div>
  </div>  
</div>
<br>
<div class="card">
  <div class="card-header">
    <strong>Question 3</strong>
  </div>
  <div class="card-body">
    <p class="card-text">In this higher magnification view of Question 2, what is the specific location at the pointer?</p>
    <img src="./assets/images/splashImage_kidney_zoom2_pointer.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample03" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample03">
      <br>
        <div class="well">
          Vascular Pole 
        </div>
    </div>
  </div>  
</div>
<br> 