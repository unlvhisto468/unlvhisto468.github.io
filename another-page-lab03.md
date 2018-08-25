---
layout: default
---


![Splash_IMAGE](./assets/images/splashImage_bone.png)

# Lab 3: Skeletal System

### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>

1.  Sketch the different cartilages – include: locations, presence of fibers, and functions
2.  Make a list of all the cells of the skeletal system and what their functions are
3.  List the steps of endochondral ossification
4.  List the steps of intramembranous ossification

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
  var dateToRelease = new Date("09/05/2018");
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
    <p class="card-text">What type of tissue is present in this view?</p>
    <img src="./assets/images/splashImage_bone.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample01">
      <br>
        <div class="well">
          Compact Bone
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
    <p class="card-text">The tissue type of Question 1 is made up of the inorganic component of mostly a mineral called  __________________?</p>
    <div style="margin-left: 20px;">
		<a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
		<div class="collapse" id="collapseExample02">
			<br>
	  		<div class="well">
		    	Hydroxyapatite <br>
		    	Ca<sub>10</sub>(PO<sub>4</sub>)<sub>6</sub>(OH)<sub>2</sub>
		  	</div>
		</div>
	</div>
  </div>
</div>