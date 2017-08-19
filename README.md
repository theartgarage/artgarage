# frenchmen
frenchmen art market readme
To view in its entirety, click 'Raw'.

Maintenance:
  Since I will be busy with school, I've designed the website so that there's as little maintenance as possible.
  However, there are a few things that can be done that don't require too much work.
    
  EDITING ART PAGES:
  This is a block of code:
    <div class="responsive"> # refers to the responsive class - allows the image to be clicked
       <div class="gallery"> # refers to the gallery class - this makes the photo appear in a "gallery" box instead of just on the page 
          <a target="_blank" href="example.jpg"> # when the image is clicked, it opens the image on another page
            <img src="example.jpg" alt="333" width="600" height="400"> # sources the image, gives an alt name, and defines width/height(px)
          </a>
      <div class="desc"></div> # adds a blank space below the image for space reasons.
    </div>
  The code above will add an image for an artist. 
    
  <button class="accordion">A. R. Tiste</button>
     <div class="panel">
        <p>Example description about a person, place, or thing.</p>
     </div>
  This block of code adds a drop down button for an artist   
    
<div class="clearfix"></div>
The code above adds a "clearfix"--a way to clear things up with spacing so that the button shows up nicely on desktop and mobile.

<a href="example.com">Example</a>
This line of code creates a hyperlink to another page. It's important that the website link is always in quotations.

The structure of an artist button should then look like this:
  <button class="accordion">A.R. Tiste</button>
     <div class="panel">
        <p>THis is a bunch of background about a nonexistent artist.<br><br>You can put a <a href="example.com">website</a> here.</p>
           <div class="responsive">
              <div class="gallery"> # more than one image can be added at a time - just copy the block of code down to the last </div>
                  <a target="_blank" href="old3.jpg">                        # and then paste and change .jpg names for your new image
                     <img src="old3.jpg" alt="5" width="600" height="400">
                  </a>
              <div class="desc"></div>
             </div>
           </div>
            
<div class="clearfix"></div> # clearfix only goes at the very end of your block, right above </div>
</div>
# Don't forget ABC order on the artist pages!

  MAIN PAGE:
    There isn't much to fix on the main screen. The only things that should ever get changed are events.
    TO CHANGE AN EVENT:
      Scroll down to the event section on index.html. It will be marked as such: <!-- Coming Up -->
      Locate the block that starts with <p class="w3-opacity w3-center"> and ends with </p>
      Leave <br>Find us on *social media here*
      Change whatever is between the <i> and </i> tags. If needed, use <br> to add a space or two between events
      Commit changes
  And that's it!
      
