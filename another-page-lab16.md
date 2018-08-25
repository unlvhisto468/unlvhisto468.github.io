---
layout: default
---


![Splash_IMAGE](./assets/images/splashImage_graafianFollicle.png)
# Lab 16: Female Reproductive System


### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>

1.  List all of the pathologies of the female reproductive system from your text book
2.  Draw a general layout of the female reproductive system (and label all anatomical structures like on slide 40,57 of the powerpoint)
3.  List the hormones of the Female reproductive system (page 226 lab book)
4.  Draw the different stages of follicular development (Slide 42, general) and include details 
5.  What is (include sketch of) corpus hemmorhagicum, corpus luteum, corpus albicans, 
6.  Sketch the Fallopian tube, and label its different segments, and include all relevant cells, and their functions. 
7.  Sketch the different layers of the uterus
8.  Sketch and detail the menstrual cycle, and include the interplay with oovarian, follicular, and uterine cycles play a role on the menstrual cycle (I drew this on the board!!!) 
9.  Sketch what the 3 different uterine phases appear in a histological representation
10. What is the epithelium of the various organs, and structures of the female reproductive system? 
11. Sketch the mammary glands, and include all relevant cells, and their functions 

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
  var dateToRelease = new Date("11/28/2018");
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
    <p class="card-text">What is the entire structure depicted? What specific portion of this structure is the pointer at?</p>
    <img src="./assets/images/splashImage_graafianFollicle_pointer.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample01">
      <br>
        <div class="well">
          Antrum of the Graafian Follicle
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
    <p class="card-text">In what organ do you find the structure from Question 1?</p>
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample02">
      <br>
        <div class="well">
          Ovary
        </div>
    </div>
  </div>  
</div>
<br>