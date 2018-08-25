---
layout: default
---

![Splash_IMAGE](./assets/images/splashImage_retina.png)
# Lab 7: Special Senses

### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>

1.  Sketch Olfactory Epithelium and label all the cells, and their functions
2.  Draw a pathway of neuronal input from the olfactory epithelium to the brain. (I drew this on the board) include cribiform plate, and include different areas of the brain involved
3.  Sketch a taste bud and label all the cells within-detail the functions
4.  Sketch they eye like figure 9-4 
5.  Sketch layers of the eye and KNOW THEM  (refer to figure 9-12)
  * _You didn’t have to for the practical 1, but you will for the quiz, practical 2, and final practical_
6.  Sketch a pathway of light going through the different structures of the eye and recall detraction of light! 
7.  Make sure to know all the structures of the eye, and for sure know: blind spot, Suspensory ligament, lens, iris, ciliary body, poster chamber, anterior chamber, Pigmented epithelium, Tarsal glands, optic nerve, 
8.  For the EAR: 
  * Sketch the pinna (refer to figure 9-15)
  * Internal Ear
  * Macula of Utricle and saccule
  * Ampulla of semicircular canal
  * Cochlea
  * Organ of corti

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
  var dateToRelease = new Date("09/26/2018");
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
    <p class="card-text">What is this multi-layered structure depicted in this view? What organ is this?</p>
    <img src="./assets/images/splashImage_retina.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample01">
      <br>
        <div class="well">
          Retina of the Eye
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
    <p class="card-text">What type(s) of neurons are found in the photoreceptive layer of Question 1?</p>
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample02">
      <br>
        <div class="well">
          Rods and Cones
        </div>
    </div>
  </div>  
</div>
<br>

