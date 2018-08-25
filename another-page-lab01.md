---
layout: default
---


![Splash_IMAGE](./assets/images/splashImage_epithelialTissue.png)

# Lab 1: Epithelial Tissue

<a id="jump-to-notebook-questions" class="jump-to-section"> </a>
### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>
	
##### Histological Technique

1.  Histological Technique (list the major steps with slight detail)
2.  Make a table including the different types of stains, and what they stain for
3.  Sketch the different stages of mitosis (with a description of each stage and what you can see histologically)
4.  Sketch the different planes of section

##### Epithelium

1.  Sketch out all the different types of epithelia, include location, function – make your list extensive. 
2.  Use your lab book, and textbook to to make your lab report as extensive as possible 

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
	var dateToRelease = new Date("08/27/2018");
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
    <p class="card-text">What type of epithelial tissue is present in this view? What specific cell type is the pointer at?</p>
    <img src="./assets/images/splashImage_epithelialTissue.png" width="500">
    <div style="margin-left: 20px;">
		<a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
		<div class="collapse" id="collapseExample01">
			<br>
	  		<div class="well">
		    	Simple Columnar ET with Goblet Cells
		  	</div>
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
    <p class="card-text">In what human organ(s) could you find the epithelial type from (Question 1)?</p>
    <div style="margin-left: 20px;">
		<a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
		<div class="collapse" id="collapseExample02">
			<br>
	  		<div class="well">
		    	Stomach, Small Intestine, Large Intestine, Gallbladder, Rectum
		  	</div>
		</div>
	</div>
  </div>
</div>


