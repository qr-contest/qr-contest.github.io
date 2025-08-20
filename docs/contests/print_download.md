---
layout: home
title: Print/Download
parent: Contests Tab
nav_order: 4
---

{: .no_toc}

<div class="sticky-gotop">
<span class="inline-icon"><i class="fa-solid fa-arrow-up"></i></span>
</div>
<div class="sticky-right">
<details markdown="block">
  <summary>
    Quick Links
  </summary>
  {: .text-delta }
- Quick Links
{: toc}
</details>
</div>

<div class="accordion-bar">Print/Download</div>
## Print/Download
This section allows you to choose whether to output to an Auto generated PDF(s) for your Question(s) and Answers or to output PNG files (individual images per file) or to Avery© labels, or to manually layout a PDF, SVG, or STL (3d Printable) .  You are allowed to print your contest so that you may test the voting.  Until you launch your contest by paying for it, the results will only show the last vote scanned.  So, if you have a question with 3 answers and you print a PDF out, you can test your campaign by scanning them one at a time and seeing the results.  Each time you scan (no matter who scans), the prior result will be removed.  You can think of this as a 'draft' mode where you are just testing your contest, but not really aggregating results.  After testing and your're ready to launch/publish your contest, go to [Pay and Launch](#pay-and-launch)

<p align="center" class="screen-shot">
<img class="image-border" alt="print and download options" src="../../../assets/images/print_download.png">
</p>

### Auto PDF
<span class="inline-icon"><i class="fa-regular fa-circle-dot"></i></span> Auto PDF - this will output one PDF per Question.  The Answers will be arranged automatically on the page.  You should not put more than 6 answers on a Question if you want them to layout correctly on a single PDF.  You may choose Lanscape (the default) or Portrait orientation for the PDF.

The other settings are explained in the <span class="inline-accordion">Configure Options</span> section above.  Setting them here will override the <span class="inline-accordion">Configure Options</span> values.

{: .note }
> If you have Adobe Acrobat or the new free Microsoft Edge PDF Editor, you may edit the generated PDF and place things wherever you like.  Just be sure to not modify the QR codes in the document.  Also, when you print the PDF make sure you check the <span class="form-lable">Actual Size</span> radio button on your print dialog.  The PDFs are generated with precise measurements and should not be scaled.


### PNG
<span class="inline-icon"><i class="fa-regular fa-circle-dot"></i></span> PNG - Selecting this option will allow you to control every visual aspect of each of your questions and answers and output them to multiple PNG files.  Each Question will be in a separate PNG and each answer will be in their own PNG file.  The software will also generate a 'directory' so that you know which Questions and Answers go together.  The program will automatically layout each answer to make them look nicely when output. However, you may adjust any aspect of each PNG by following the below procedures.

<p align="center" class="screen-shot">
<img class="image-border" alt="manually layout PNG images" src="../../../assets/images/manual_png.png">
</p>

You may change each property for **every** Answer, or you can modify the 1st Answer to be the layout you would like to use for all of the Answers and choose <span class="inline-button">Apply current layout to all...</span> - you will then be prompted to select whethe ry ou want to apply the layout to All Questions (this Location), All Answers (this Question) or Cancel.

<p align="center" class="screen-shot">
<img class="image-border" alt="apply to" src="../../../assets/images/apply_to.png">
</p>

<span class="inline-button">All Questions (this Location)</span> - for QR-Contest, there is only 1 Location per Question.  However, your contest may have multiple Questions.  Pressing this button will apply the current layout choices to all Questions and their Answers.
<br>
<br>
<span class="inline-button">All Answers (this Question)</span> - Pressing this button will apply the current layout choices to all Answers for this Question.  If you have multiple Questions, pressing this will not affect the other Questions.  Use the arrow buttons at the top to change Questions and Answers.



In addition, if you are on an Answer past the first one, you can use the <span class="inline-button">Match Previous</span> button to match the layout of the Answer you are on to the previous Answer.

In addition to colors, fonts, etc. you may also manually locate any of the object in the preview area.  Select an object (text, QR code, photo) and you will see gripper handles on the 4 corners of the object (the image above has them around the QR code).  You may change the size of the object by dragging the gripper handles, or you may click and drag the middle of the object to relocate it.  The stacking order of the objects is: QR Code on top, then the Text answer (if any), then the Photo (if any), then the background.

{: .note }
> Changing the size of the Text box will increase or decrease the font size to fit your Answer into the box if the auto-scale text icon <img src="../../../assets/images/auto_text.png"> is chosen (the default).

You may traverse through the Question(s) and Answers using the left <span class="inline-icon"><i class="fa-solid fa-caret-left"></i></span> and right <span class="inline-icon"><i class="fa-solid fa-caret-right"></i></span> arrows.

When you are done laying out the PNG files, you should press <span class="inline-button">Make PNGs</span>.  The PNG files will be generated [see here](#make-pngs).  If you do not traverse through all the questions or answers, the ones you have not visited will use the auto-layout algorithm.

You may choose the resulting size of the PNG files by changing the Size (width x height). Or, you may choose a pre-defined size (like for your Canon Ivy Printer, so you can print stickers!).  We update this list often.  If you are looking to output Avery® labels, you should use the Avery® radio button on the <span class="inline-accordion">Print/Download</span> section. You may also change the QR Code colors, Text style and photo transparency (if you have photo answers).

Click on an object in the preview to set the properties.  For example, the QR code is selected by default when you first get to this screen.  You can change the foreground and background colors of the QR code as well as the shape of the little internal 'rectangles'.  

#### QR Code
To change the colors, click on the left color box for foreground or the right color box for background.  Then, select a color from the color picker.  You'll see the preview update with your changes. To make the color picker go away, click outside of it.

<p align="center" class="screen-shot">
<img class="image-border" alt="QR code color picker" src="../../../assets/images/qr_color_picker.png">
</p>

To change the shape of the internal 'rectangles', use the left <span class="inline-icon-black"><i class="fa-solid fa-caret-left"></i></span> and right <span class="inline-icon-black"><i class="fa-solid fa-caret-right"></i></span> arrow buttons.  You can choose circle, triangle, hexagon, star, etc.

<p align="center" class="screen-shot">
<img class="image-border" alt="QR code internal shapes" src="../../../assets/images/qr_shape_picker.png">
</p>

#### Text
Click on the **Text Here** (whatever your text answer is) at the top of the preview.  That will display a row of attributes you can change for the text.  You may change the font color, bold, underline and italic.  If the auto-scale text icon <img src="../../../assets/images/auto_text.png"> is chosen, the text will scale to fit/fill the text box area.  If you select the radio button to manually enter the font size and justification, then the auto-scale will be disabled.  You may enter decimal numbers for the font, but be careful, as we have not put any limits on the size at this point.  If you type 300, you're going to get a big chunk of text that will overflow the box. If your answer does not have text, it will not appear in the layout.

<p align="center" class="screen-shot">
<img class="image-border" alt="text attributes, color, bold, underline, italic" src="../../../assets/images/text_attributes.png">
</p>

#### Photo
Click on the picture of your answer (if you have a photo) and you may change the opacity of the image.  The default is 100 - meaning completely opaque so nothing under the photo shows through.  You can change the opacity so that the image background (see below) shows through or blends with the photo. The below sample shows the opacity at 50% on a white background, so it make the photo 'lighter'.  If your answer does not have a photo, it will not appear in the layout.

<p align="center" class="screen-shot">
<img class="image-border" alt="photo attributes" src="../../../assets/images/photo_attributes.png">
</p>

The PNG layout also allows you to modify the Photo to be Contain or Cover.  See the section [Question Page Appearance](./config_opts#question-page-appearance) for a description.  Click on the Photo and above the Opacity setting will be a checkbox.  The default setting for PNG is to use Cover (the far left radio button) - which means the image will fill the layout box.  If you choose the right radio button, the image will be set to be 'Contained' in the result rectangle.  You may play with these to see what they do.  If you choose the check box on the far right, that means to scale the photo to be the same aspect ratio as the source and to restrict its sizing to match that aspect ratio.  Unchecking the box will revert to Cover and Contain mode.

<p align="center" class="screen-shot">
<img class="image-border" alt="aspect correct or contain or cover" src="../../../assets/images/manpng_contcover.png">
</p>

#### Background
Click on the empty space of the background and you may change the color.  The default is white, so the color box above the preview is a little tricky to see.  We've changed it to light yellow below:

<p align="center" class="screen-shot">
<img class="image-border" alt="light yellow background" src="../../../assets/images/light_yellow_bg.png">
</p>

#### Hot Tip
In the above image, you can see that the background of the QR code is white.  We'll change the background of the QR code to light blue with a 50% transparency (in the color picker).  See below.  The QR code background becomes light green because the light blue combined with the yellow of the overall Background will give you light green (blue + yellow = green).

<p align="center" class="screen-shot">
<img class="image-border" alt="light blue QR background plus light yellow image background gives light green QR background" src="../../../assets/images/qr_blend.png">
</p>

#### Make PNGs
When you are finished altering the properties, click <span class="inline-button">Make PNGs</span> to generate your PNG files.  You will get a message saying "Generating document(s)...", then a short animation with a message that says "Open your document(s) here:".  See below:

<p align="center" class="screen-shot">
<img class="image-border" alt="open your docuemnts" src="../../../assets/images/auto_png_download.png">
</p>

You have 2 options here:
1. Clicking the underlined text in the middle (a link to the .zip file) will download the resulting .zip file to your device. 
2. Clicking the far right icon <span class="inline-icon"><i class="fa-regular fa-clone"></i></span> will copy the URL for the .zip file to your copy/paste buffer.


{: .note }
> If you get a message saying "No questions picked for this location" - you need to go back to the <span class="inline-accordion">Questions and Answers</span> section and make sure you have both at least one Question and at least one Answer per question.

{: .note }
> To show the Print/Download options again, close, then open the <span class="inline-accordion">Print/Download</span> accordion.

### PNG Zip Files
The .zip files generated when you create PNG images instead of PDF contains several files.
* **directory.json** - this file is a directory listing of all questions and answers in the .zip file.  The json file (a file for a programmer) contains information about each question and answer - including the file names corresponding to each Question and Answer.  If you open it in a text editor, it is readable.  Here is an example of the PNG files generated from our Chicken example:
```
{
  "location": "QR-vote location",
  "questions": [
    {
      "id": "q_0",
      "question": "Which chicken do you like better?",
      "answers": [
        {
          "id": "q_0_a_0",
          "text": "Lady Feathers",
          "image": "q_0_a_0.png",
          "size": {
            "width": 1024,
            "height": 1024
          }
        },
        {
          "id": "q_0_a_1",
          "text": "Yellow Fella",
          "image": "q_0_a_1.png",
          "size": {
            "width": 1024,
            "height": 1024
          }
        },
        {
          "id": "q_0_a_2",
          "text": "Joker",
          "image": "q_0_a_2.png",
          "size": {
            "width": 1024,
            "height": 1024
          }
        }
      ],
      "image": "q_0.png"
    }
  ]
}
```
For QR-Contest, the "location" will always show up as "QR-vote location" (this has more meaning in QR-Answers).  The Questions each have an index (the order they were entered in the <span class="inline-accordion">Questions and Answers</span> section).  Each Answer also has an index.  Both of these indeces start at 0 (sorry, a computer thing...).  A Question is noted by the letter "q"; an Answers is noted by the letter "a".  Given the file names would be crazy long if we used the text of the question and answers, we thought it better to use numbers.  So, if you want to find out what the 3rd answer in your first question looks like, you come up with it like this:  Start with "q" (Question), then the index (0 since the first one starts at 0, not 1), add "a" for Answer, then the answer index, which for the 3rd one is 2; then put underscores (_) between each item.  So, the file name of the first Question's 3rd answer is:  "q_0_a_2.png".  We also print out the Question text - the file name is constructed the same way:  q_0.png  is the first Question.  The json file also has the size of each image.  

{: .note }
> You can read up on json (why would you?), but a quick summary is this:  each 'object' starts and ends with matched curly brackets { }; each array (list) starts and ends with square brackets [ ].  We also output a tsv (tab separated value) file with the directory if that is easier for you to use in Excel or another spreadsheet.

* Question files (see above), for example **q_0.png**
* The Answer files for each question, for example  **q_0_a_0.png** is the first answer to the first question

### Avery ®
<span class="inline-icon"><i class="fa-regular fa-circle-dot"></i></span> Avery® - Selecting this option will allow you to output your Answers to Avery® labels/documents.  It works just like PNG above, but you are able to choose a different Avery label Template for each Question's Answers.  You may see more Avery Templates by going to <a href="https://www.avery.com/templates" target="_blank">Avery® Templates</a>.  For example, if you want to print your first Question's Answers on Avery® Label 94100 - they will be 4" by 4" square labels.  If you choose, Avery® 5160, you will get a 2.63" by 1" label for each Answer.  We currently support US sizes (Letter), but will be adding A4 sizes shortly. The visual representation on the screen will match the aspect ratio of the chosen label.  If you change the Template choice, you will be asked which Questions or Answers you would like to apply the change to.  You may change for all Questions' Answers in this Contest, or just this Question's Answers.  Typically, you probably will only have one Question in a Contest, but it is possible to have more than one, so modifying the Template will affect only the choice from the popup.

{: .note }
> If you choose Avery as the output type, the Questions themselves will not be printed - for example <i>"Which photo do you like more?"</i> from below.  You can print a PDF with the actual Question text, or just print it using Word or some other Text editor.  We thought it would look funny to print the Question on a label, but if you think not, let us know...  Also, like PDFs, make sure you choose Actual Size in your printer dialog so that the labels print precisely where they are supposed to.

You may control every visual aspect of each of your Answers by using the same process as described above in the PNG section.

<p align="center" class="screen-shot">
<img class="image-border" alt="Avery label choice" src="../../../assets/images/avery_choice.png">
</p>

The only other option not in the PNG layout described above is the <span class="inline-icon"><i class="fa-regular fa-square-check"></i></span> Safe checkbox.  If you select the checkbox, there will be a 1/8" dotted nmargin put around the actual label size so that you don't overrun your label dimensions if the paper isn't placed precisely in the printer.   If you uncheck the Safe checkbox, you may move any text, photo or QR code to the absolute edge of the label.

<p class="fs-2">Avery and all Avery brands, product names and codes are trademarks of Avery Products Corporation.</p>

### PDF
<span class="inline-icon"><i class="fa-regular fa-circle-dot"></i></span> PDF - Selecting this option will allow you to output your Answers to a PDF, but you may manually layout each area of the PDF vs. the "Auto PDF" choice.  

1. Select the size dropdown and choose whether you want Landscape or Portrait (US Letter) orientation and how many Answers per page you would like to have.  The Questions and Question Page Header are printed on each page if there are more answers than fit on a single page.

<p align="center" class="screen-shot">
<img class="image-border" alt="Manual PDF size choices" src="../../../assets/images/pdf_man_size.png">
</p>

In Lanscape orientation, 1 per page will fill the entire page (except where the Question, Header and bottom logos print).  The 2 per page will place them side by side; 3 per page will put them side by side in a single row; 4 per page will divide the page into 2 rows of 2; 5 per page will put 3 in the top row and 2 in the bottom (centered); 6 per page will make 2 rows of 3 across.  In Portrait orientation, 1 per page will fill the page; 2 per page will put them in a column; 3 per page will be 1 column; 4 per page will split into 2 rows and columns; 5 per page will make 3 rows - 2 in the 1st 2 rows and 1 in the bottom row; 6 per page will have 3 rows of 2.  Play with it, you'll figure it out.
<br><br>
The area you are designing is one of the cells - all cells are the same size depending on what orientation and 'per page' you choose, the aspect ratio of the design surface will change and match the output aspect ratio.  Keep in mind that for this style of layout, there are no margins between the cells - so you should leave some white space around the edges of the design surface or add a colored background.
<br><br>
You are able to layout each and every cell if you like, or layout the first one and choose <span class="inline-button">Apply current layout to all...</span>.   However, if you are doing a 'serious' research project, you may want to make sure all choices look the same so that the layout doesn't dissuade or draw someone's attention to something other than the Answer...


The customizations work like the PNG and Avery® label layouts described in detail above.

### HTML
<span class="inline-icon"><i class="fa-regular fa-circle-dot"></i></span> HTML - Selecting this option will allow you to output your Answers to HTML page(s), but you may manually layout each area of the HTML.  

1. Select the Answers per page dropdown and choose whether you want Landscape or Portrait (US Letter) orientation and how many Answers per page you would like to have.  The Questions and Question Page Header are printed on each page if there are more answers than fit on a single page.

<p align="center" class="screen-shot">
<img class="image-border" alt="Manual PDF size choices" src="../../../assets/images/html_size.png">
</p>

In Lanscape orientation, 1 per page will fill the entire page (except where the Question, Header and bottom logos print).  The 2 per page will place them side by side; 3 per page will put them side by side in a single row; 4 per page will divide the page into 2 rows of 2; 5 per page will put 3 in the top row and 2 in the bottom (centered); 6 per page will make 2 rows of 3 across.  In Portrait orientation, 1 per page will fill the page; 2 per page will put them in a column; 3 per page will be 1 column; 4 per page will split into 2 rows and columns; 5 per page will make 3 rows - 2 in the 1st 2 rows and 1 in the bottom row; 6 per page will have 3 rows of 2.  Play with it, you'll figure it out.
<br><br>
The area you are designing is one of the cells - all cells are the same size depending on what orientation and 'per page' you choose, the aspect ratio of the design surface will change and match the output aspect ratio.  Keep in mind that for this style of layout, there are no margins between the cells - so you should leave some white space around the edges of the design surface or add a colored background.
<br><br>
You are able to layout each and every cell if you like, or layout the first one and choose <span class="inline-button">Apply current layout to all...</span>.   However, if you are doing a 'serious' research project, you may want to make sure all choices look the same so that the layout doesn't draw someone's attention to something other than the Answer...


The customizations work like the PNG and Avery® label layouts described in detail above.
### SVG
<span class="inline-icon"><i class="fa-regular fa-circle-dot"></i></span> SVG - Selecting this option will allow you to output your Answers to SVG (scalable vector graphics) files, but you may manually layout each area of the SVG.  

1. Choose the width and height of the SVG.

<p align="center" class="screen-shot">
<img class="image-border" alt="Manual PDF size choices" src="../../../assets/images/svg_size.png">
</p>

The area you are designing is one of the cells.  Each SVG is whatever size you choose for each one.  By default, it will output to all the same size, unless you change the size on an individual answer.
<br><br>
You are able to layout each and every cell if you like, or layout the first one and choose <span class="inline-button">Apply current layout to all...</span>.   However, if you are doing a 'serious' research project, you may want to make sure all choices look the same so that the layout doesn't draw someone's attention to something other than the Answer...

The customizations work like the PNG and Avery® label layouts described in detail above.

### STL (Experimental)
<span class="inline-icon"><i class="fa-regular fa-circle-dot"></i></span> STL - Selecting this option will allow you to output your Answers to STL (Stereolithography) files, but you may manually layout each area of the STL like above.  STL is a 3D printing format supported by most Slicers for 3D printers.  We use a Creality Combo Color in the office as our QR printer.

1. Choose the width and height of the STL in millimeters (mm). You may control the base thickness by setting the base height in mm.  You may also control the height of the printed QR code, text and image (if any) with the top value in mm.  You should try to choose an output size large enough that the QR code details print reasonably well so they can be scanned.

<p align="center" class="screen-shot">
<img class="image-border" alt="Manual STL size choices" src="../../../assets/images/stl_size.png">
</p>

What we do is use the slicer and put a PAUSE at the layer where the 'top' starts.  That way we can print a 'white' bottom, then switch the fillament to black or another color so that the QR code and image print in black.  See this photo; the bottom is white, the top is black (corresponding to the dimensions chosen above). The photo doesn't do the 3D print justice, but you get the idea.

<p align="center" class="screen-shot">
<img class="image-border" alt="STL Side View" src="../../../assets/images/stl_side_view.png">
</p>

The images are handled with a dithering algorithm to convert the greyscale of the image to black and white dots (or a lithophane).  If you click on the image, you will see some settings for how the image scales, centers, etc.  There is also a dropdown to determine what dithering algorithm you would like to use.  The default is Min Error, which does a descent job.  

<p align="center" class="screen-shot">
<img class="image-border" alt="Dither choices" src="../../../assets/images/stl_dither.png">
</p>

If you are printing to a lithophane (kind of a 3d relief), choose Lithophane.  We default the lithophane size to 108 x 144 mm, 1.2mm base and .8mm top.  Then we print it all in white (or a light color).  You can get a 'light box' from Bambu Labs that will hold this and backlight it for you - which looks and work great.  The <a href="../../../assets/images/Lithophane%20frame.stl" target="_blank">Lithophane Frame</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/" target="_blank">Creative Commons (4.0 International License)</a>. See below photo.

<p align="center" class="screen-shot">
<img class="image-border" alt="Lithophane light box" src="../../../assets/images/stl_lithophane.png">
</p>

You'll need to experiment with your slicer settings to make sure the QR code is readable.  If you print something too small, a phone will not be able to scan the QR code.  So, be sure to test it after you print it, if it does not work, increase the size.  Below is a photo of the side view of a 3D print.  The bottom 

The area you are designing is one of the cells.  Each STL is whatever size you choose for each one.  By default, it will output to all the same size, unless you change the size on an individual answer.
<br><br>
You are able to layout each and every cell if you like, or layout the first one and choose <span class="inline-button">Apply current layout to all...</span>.   However, if you are doing a 'serious' research project, you may want to make sure all choices look the same so that the layout doesn't draw someone's attention to something other than the Answer...

The customizations work like the PNG and Avery® label layouts, etc. described in detail above.