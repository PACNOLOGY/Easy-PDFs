# Easy-PDFs
quick pipeline to turn a series of images into a PDF

We are going to cover a quick and easy process for turning a series of photos into a PDF for easy presentation.

Prerequisites:

  -GIMP, which you can download from https://www.gimp.org/, just install the version best for your OS, it covers the big 3 (windows, mac, linux).
  
  -Any PDF program, even your web browser will work.
  
  -Any photos you'll be putting through this process.

We're gonna start with a new file in GIMP, preferably the size of whatever paper your office or agency uses.
<img src=https://imgur.com/WoEothL.png>

Now that we have our blank canvas, we're going to load all our photos.  The way we're going to do this is by clicking "open as layers"
<img src=https://imgur.com/G4wjuuu.png>

We will then select all the photos we want to use for our PDF, and open
<img src=https://imgur.com/OXnqGWW.png>

if they're in need of resizing, use the "Unified Transform Tool". NOTE: be sure you only grab the image by the very edge of a corner box, otherwise you'll find yourself doing perspective and warp transformations, and you'll wind up frustrated.  To reverse this is like any other program, press [ctrl-z], ([command-z] if on a mac)
When resizing, hold [CTRL] or [Command] to keep the image aspect ratio.
<img src=https://imgur.com/7alb8eN.png>

NOTE: you may have to do this per layer, so if you need to, the layer panel will be on the right side of the screen if working from default installation.  Use the eyeball icons to hide and show layers.

<img src=https://imgur.com/0pY0JwZ.png>

Once we have all our layers visible and a size we like, we're now going to make the PDF.  To do this, we simply click "export" or "export as..." and navigate to where we want to save our new PDF, then set the filename to "<filename>.pdf".

<img src=https://imgur.com/y8GvNGk.png>

VERY IMPORTANT STEP: We will be faced with a dialog box.  Make sure to tick the 2 boxes that say "Layers as pages (top layers first)" and "Reverse the pages order" as when we imported our photos as layers, the first in the sequence was laid down as the bottom layer.

<img src=https://imgur.com/GxuAZHw.png>

Click on "Export", and you're done.  Navigate to where you exported the PDF and test it out!

<img src=https://imgur.com/ZlU1Xgr.png>

For advanced users: if you're familiar with photoshop, then you'll find the same principles apply in GIMP.  if you want to add text to your pages, just be sure to merge each text layer with its corresponding photo layer, so it knows to include both per page.
