---
layout: default
---

![Splash_IMAGE](./assets/images/splashImage_embryology.png)

# Lab 17: Embryology

### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>

1.  List all of the pathologies (from your lecture book) 
2.  Where does fertilization occur? 
3.  Summarize the key events from the video shown in class (approx. 1 page)
4.  What occurs during fertilization? 
  * What are key events and features of this stage? 
5.  What occurs during cleavage? 
  * What are key events and features of this stage?
6.  Detail the different structures that arise after fertilization (slide 15)
7.  What occurs during implantation? 
  * What are key events and features of this stage?
8.  What is gastrulation? 
  * What are the 3 germ layers, and what specific tissues and organs arise from each?
9.  What are the ‘extraembryonic membranes’ and what is the general function of each
10. List the hormones of gestation 
  * Slide 25 of powerpoint
11. Weight changes during pregnancy
12. What are the specific details of each trimester?

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
  var dateToRelease = new Date("12/03/2018");
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
    <p class="card-text">What is embryonic structure at the pointer?</p>
    <img src="./assets/images/splashImage_embryology_pointer.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample01">
      <br>
        <div class="well">
          Morula
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
    <p class="card-text">What embryonic structure is the precursor to Question 1?</p>
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample02">
      <br>
        <div class="well">
          Zygote
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
    <p class="card-text">What embryonic structure does Question 1 give rise to?</p>
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample03" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample03">
      <br>
        <div class="well">
          Blastocyst
        </div>
    </div>
  </div>  
</div>