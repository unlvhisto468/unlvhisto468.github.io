---
layout: default
---


![Splash_IMAGE](./assets/images/splashImage_spinal.png)

# Lab 6: Nervous System

### Lab Notebook Questions

<!-- /////////////////////////////////////////// -->
<!-- [conditional logic for release of labnotes] -->
<div id='if-part' markdown="1" style='visibility: hidden; display: none;'>


&nbsp; &nbsp; &nbsp;_Note: This chapter should be super detailed_
1.  List all the types of neurons and where they may be found
2.  List all the glial cells, and where they may be found, and their functions. Also note any subtype of cells, I.E. protoplasmic astrocytes vs fibrous astrocytes. 
3.  Sketch out the anatomical divisions and functional divisions of the nervous system ( there is a slide that you can use as a guide)
4.  Sketch out the following and list functions:
  * Teased nerve fibers (like on figures 8.20-8.22)
  * Cross sections of nerve fibers (fig 8-19) 
  * Nerve structure (figs 8.24-8.25)
  * Spinal cord and all its structures (tracts,nuclei) pg 103
  * Figure 8-28
  * Ganglion like figures B, C of figure 8-28
  * Auerbach's plexus 
    * _google image this so you can see what it looks like zoomed out, the image on figure 8-30 is too zoomed in for my taste, and should have had a zoomed out and zoomed in view_
  * Choroid plexus
  * Meninges
  * Neuromuscular Junction
  * Cerebellum
  * Medulla oblongata
  * Cerebrum (all layers) with types of cells within each
5.  Additionally, google image "Hypothalamus" as we DO have those slides in class, but there is not an example in the book. 



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
  var dateToRelease = new Date("09/19/2018");
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
    <p class="card-text">What organ is depicted in this view? What division of the nervous system does this organ belong to?</p>
    <img src="./assets/images/splashImage_spinal.png" width="500">
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample01" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample01">
      <br>
        <div class="well">
          Spinal Cord of the Central Nervous System
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
    <p class="card-text">In what bone can the organ from Question 1 be found?</p>
    <div style="margin-left: 20px;">
    <a class="btn btn-primary" role="button" data-toggle="collapse" href="#collapseExample02" aria-expanded="false" aria-controls="collapseExample"> Show Answer</a>
    <div class="collapse" id="collapseExample02">
      <br>
        <div class="well">
          Vertebra 
        </div>
    </div>
  </div>  
</div>
<br>