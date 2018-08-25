---
layout: default
---

![Splash_IMAGE](./assets/images/splashImage_skeletalMuscle.png) 
# Lab 4: Muscular System

### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>

1.  Sketch the 3 types of muscle tissue. 
2.  Sketch the layers of organization of muscle, including the types of tissues
3.  How does CT stabilize muscle? 
4.  List the steps of the EXCITATION phase 
5.  Do a rough sketch of what a muscle fiber and its specific arrangements inside the fiber


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
  var dateToRelease = new Date("09/12/2018");
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
    <p class="card-text">What type of muscle tissue is this?</p>
    <img src="./assets/images/splashImage_skeletalMuscle.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample01">
      <br>
        <div class="well">
          Skeletal Muscle Tissue
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
    <p class="card-text">How many cells of Question 1 is depicted in the view?</p>
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample02">
      <br>
        <div class="well">
          3-4
        </div>
    </div>
  </div>  
</div>
<br>
