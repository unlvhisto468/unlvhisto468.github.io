---
layout: default
---

![Splash_IMAGE](./assets/images/splashImage_thymus.png)
# Lab 11: Lymphatic System

### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>

1.  Sketch and label all the major structures and locations of cells of the lymph node
2.  Sketch and label all the major structures and locations of cells of the Spleen
3.  Sketch and label all the major structures and locations of cells of the Thymus
4.  Sketch and label all the major structures and locations of cells of the Tonsils (all 3 types) 


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
  var dateToRelease = new Date("10/24/2018");
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
    <p class="card-text">What organ is depicted in this view? What portion of this organ is depicted at the pointer?</p>
    <img src="./assets/images/splashImage_thymus_pointer.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample">Show Answer</a>
    <div class="collapse" id="collapseExample01">
      <br>
        <div class="well">
          Medulla of the Thymus
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
    <p class="card-text">What is the term for the organ in Question 1 when it begins to degenerate and is replaced by adipose tissue?  When does this occur?</p>
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample02">
      <br>
        <div class="well">
          Involution after Puberty
        </div>
    </div>
  </div>  
</div>
<br>

