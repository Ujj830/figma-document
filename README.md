# Figma Documentation 📖

This is a document for using [Figma](https://www.figma.com/) effectively

<a name=top></a>

<details>
    <summary><h5>
        Table of Contents 📚
        </h5></summary>
        <ul>
<li><p><a href='#about'>About</a></p>
</li>
<li><p><a href='#overview'>Overview</a></p>
<ul>
<li><a href='#navbar'>Navbar</a></li>
<li><a href='#sidebar'>Sidebar</a></li>
<li><a href='#main-overview'>Main Overview</a></li>
</ul>
</li>
<li><p><a href='#figma-design'>Figma Design</a></p>
<ul>
<li><p><a href='#Header1'>Header</a></p>
</li>
<li><p><a href='#layer-manager'>Layer Manager</a></p>
</li>
<li><p><a href='#create-design'>Create Design</a></p>
</li>
<li><p><a href='#prototyping'>Prototyping</a></p>
<ul>
<li><a href='#micro-interactions'>Micro Interactions</a></li>
<li><a href='#interactions'>Interactions</a></li>
<li><a href='#flow'>Flow</a></li>
</ul>
</li>
<li><p><a href='#demo'>Demo</a></p>
</li>
<li><p><a href='#export'>Export</a></p>
</li>
</ul>
</li>
<li><p><a href='#figjam'>FigJam</a></p>
<ul>
<li><a href='#Header2'>Header</a></li>
<li><a href='#toolbar'>Toolbar</a></li>
<li><a href='#interactivity'>Interactivity</a></li>
<li><a href='#creating'>Creating</a></li>
</ul>
</li>
<li><p><a href='#sharingcollaborating'>Sharing/Collaborating</a></p>
</li>
<li><p><a href='#helpful-commands'>Helpful Commands/Shortcuts</a></p>
</li>
<li><p><a href='#pricing'>Pricing</a></p>
</li>
<li><p><a href='#fonts'>Fonts</a></p>
</li>
</ul>
</details>

<!---

* [About](#About)

* [Overview](#Overview)
  * [Navbar](#Navbar)
  * [Sidebar](#Sidebar)
  * [Main Overview](#Main Overview)
* [Figma Design](#Figma Design)
  * [Header](#Header1)
  * [Layer Manager](#Layer Manager)
  * [Create Design](#Create Design)
  * [Prototyping](#Prototyping)
    * [Interactions](#Interactions)
    * [Micro Interactions](#Micro Interactions)
    * [Flow](#Flow)
  * [Demo](#Demo)
  * [Export](#Export)
* [FigJam](#FigJam)
  * [Header](#Header2)
  * [Toolbar](#Toolbar)
  * [Interactivity](#Interactivity)
  * [Creating](#Creating)
* [Sharing/Collaborating](#Sharing/Collaborating)
* [Helpful Commands](#Helpful Commands)
* [Pricing](#Pricing)
* [Fonts](#Fonts)

-->

<a name=About></a>

# About

Figma is an online tool that helps people design things like websites and apps. It's popular because it lets multiple people work on the same design at the same time, making teamwork easy. Think of it like a shared workspace where everyone can draw, edit, and make changes together, all in one place.

<a name=Overview></a>


<a name=Sidebar></a>

#### Sidebar

Moving on to the sidebar, you can see in order of top to bottom

* your recent files (will be default to this page)
* current drafts
* explore community templates and plugins
* advert to upgrade to figma
* a list of teams you are in or have created and the projects belonging to that team (ie for the above example (red) Team project is a project under my team Calgary heist)
* a button to create a new team

⚠ Note: a team can have multiple project which can contain multiple project files

##### Create new team

If you want to create a new team, click create team from above and follow the prompts

<a name=Main Overview></a>

#### Main Overview

![recent]()

In you main overview (see above), we have options to (from top to bottom):

1. create a new design or FigJam file or import a figma file (a file with the .fig file extension)
2. select FigJam template for FigJam file (may have been removed by the time of viewing because FigJam is currently in Beta)
3. select recent project files with helpful widgets to help you find the files you want, ie a filter, sort by or list view 

<a name=Figma Design></a>

## Figma Design

Figma design file is what most people know Figma for and will the focus of this section. Assuming you created a new blank design file from the previous steps, you will be brought to a page that looks like the following:


We will explore this 1 piece at a time starting with the header strip

<a name=Header1></a>

### Header

First let's name our FigJam file. This is done by clicking on the Untitled text in the header (red section below)

If you want to change the team or project is under, click on drafts and select a team/project or create a new team/project

If you click on the arrow in the red section (see above), you can

* see the version history much like the one found in Google Docs
* publish this project's styles and components
* export currently selected item
* duplicate current project file
* rename current project file (same as clicking on the project name text)
* move project to a different team (same as clicking the current project text (currently Jam Project))
* delete file

---

1. in the brown section of the header you will find a headphone icon if you've selected a team which will allow you to do a voice chat the team assuming you have the feature enabled by having the Figma Professional tier
2. other collaborators (and yourself) that are currently viewing the file
3. share button to share a link for someone else to view or edit [see [#share](#share) for more info]
4. play button to enter into the first flow (see [#flow](#flow))
5. zoom level

---

In the blue section we have the Figma icon that opens the options (most of these options can also be accessed through the quick search - accessible by hitting <kbd>ctrl-p</kbd>) and the rest are tools we will be doing into more details in [Create Design](#Create Design)


Within the options, we have the options in order of top to bottom:

1. Back to [recent view](#Main Overview)

2. Quick action (command palette)

3. 
   * new files
   * place image (can also be done by dragging images in or using copy and paste from clipboard)
   * save current board (in a .fig file)
   * save current version as a named point so you can revert back to this named state later
   * view history of project
   * export selected
   * export all the frames/artboards

4. The rest of the options like Edit, View, Object, Vector, Text, and Arrange are basically useless as it can be quickly accessible using shortcuts or other places that are more convenient than going into this dialog box

5. Plugin shows the plugins you currently have installed (these are global to your account) as well as the options to browse for other plugins

6. Integrations are usually tied to another 3rd party service like live embed in Confluence apps
7. Preferences have a lot of useful options like snaps

8. User libraries (shared assets)

9. Get desktop app will redirect you to the download of the desktop app

10. Help and account has a bunch of miscellaneous features

<a name=Layer Manager></a>

### Layer Manager

#### Create

Figma works much like photoshop or illustrator where the canvas is laid out in artboards/frames. To create an artboard/frame click on the # icon in the header. Then in the left sidebar you will see a list of frames under the design tab (see below)

Expanding each one out, you will see different options for each, for example, of the 2 most common one - phone and desktop, select desktop and you will see a variety of options. I will pick MacBook 14". Once you click on it, a new artboard/frame will show up on the canvas

Your artboard will act as the base layer although you can have things outside of artboards. 

Alternatively once you # icon in the header, you can draw out a rectangle in the canvas to create a frame. 

If you drag or draw a frame in another frame, the new frame will most likely be a child of the parent frame. You can be certain of this if you look in the Layers tab in the left add see the same structure as below


Also note that frames can hold multiple frames and those frames inside can hold multiple frames and so on

#### Rename

If you want to rename a frame either double click on the frame's header text in the canvas or in the Layers outline

<a name=Create Design></a>

### Create Design

To start creating a design (UI part), using the the frame we created previously. First we will create a hero for the website

#### Text/Image

1. To create some header text hit the T icon on left in the header, then click on where you want to place it in the design

2. This will open up a textbox and you can start typing

3. When you create the text or any other object you will see the changeable bounding box and some helper alignment lines (dotted above)

   If you want to change the size of the bounding box, drag the white square handles. In addition if hover just outside the corner of the white squares you can then rotate the object

4. You will notice that the font size says the same despite changing the bounding box. To actually change the size go to the design section in the right and you will see all the options to change the text including (going line by line):


   * font used

   * font type (ie bold, light, regular, italics, etc)

   * font size

   * line height

   * letter spacing

   * paragraph spacing

   * toggle between auto height, auto height, and fixed size (fixed width, but no more)

   * text align

   * align vertically

   * the three dots contain more settings like letter casing, superscript/subscript, etc


5. You will notice as you move things around, you will get snapping guides to help you align with other objects

   If you wish to disable snapping, press <kbd>ctrl-p</kbd> and search snap and then uncheck snap to object

6. Next if we want to place an image (of jam) we can drag in the image file into the canvas (this includes svg file or gifs)

#### Objects

1. Next we may want to create a call to action button

   1. To start off, create a textbox

   2. next if we click on the rectangle in the header we can see the dropdown for a bunch of shapes and an option to place an image

   3. we select the rectangle and drag out a rectangle to our liking

   4. If you covered the text, you see it again by changing the ordering of the objects by pressing <kbd>ctrl-[</kbd> with the rectangle selected. This will bring the object behind/back a layer. If you do <kbd>ctrl-]</kbd>, you will move it forward a layer. This can also be done by moving the object in the layers tab up or down

      ![ordering](img/ordering.gif)

   5. Now we can look at some ways to change the look of the button

   6.  Now we can explore the design tab in full detail

      ![colored](img/colored.jpg)

      * Starting from the top (brown section), we have the alignment tickets. This aligns the current objects to the artboard (all items individually unless they are grouped)
      * the x and y position of the object, the width/height (and a lock aspect ratio toggle), angle and if it is a shape, there will be a rounded corner option
      * constraints to the object (mostly used when resizing artboard/parent element) and if it will be fixed while scrolling
      * layer mix type (much like Photoshop's)
      * Fill and stroke color (can change if stroke is dotted and the way join edges as well if you hit the 3 dots)
      * Effects (also like Photoshop, ie drop shadow)
      * Export [see [#Export](#Export)]

   7. For our button we need to round the corner so turn it to the max (45 for me). If you want to decouple the corner (ie round on all corners except 1, click on the fullscreen icon on below and change the respective corner [see below])

      ![corners](img/corners.png)

   8. Next we want to select the color to be a cool blue to contrast the red. We select the fill color and will see the color picker pop up. 

      ![colorPicker](img/colorPicker.png)

      Within the color picker we can select the color directly or paste in the values. We can also see a quick palette of colors. In addition if we click solid on the top right we can change it to a gradient (currently supported gradients are linear, circular/radial, angular, and diamond)

      We can also change the opacity using the slider below the color slider

   9. We can then add a stroke by clicking the + icon (this is also the way to add a fill). Optionally add a drop shadow by hitting the + button in the effects section


#### Grouping

1. We then want to group the hero components and center it

   1. select all the components

   2. hit <kbd>ctrl-g</kbd> which groups the selected objects

   3. align to the artboard center by hitting the second icon in the design panel (see below)


   4. now if we want to make edits in the group we need to double click to enter the group and click away/escape to exit the group

   5. to ungroup hit <kbd>ctrl-shift-g</kbd>

In addition to vectors we can create masks. This will make it so the object in the back acts like a frame for the front object and anything outside of the back object is cut off.


<a name=Prototyping></a>

### Prototyping

Now we will get into interacting with the Figma file (the UX part)

<a name=Interactions></a>

#### Interactions

To create general interaction (ie from page to page), we can select what we want, ie a button and go to the Prototype tab and now we should see a white circle on the right most side of the bounding box (will have a plus if we hover over it)

Now we can drag this to another artboard and it will automatically go to the other artboard on tap. Of course instead of navigate we can instead open it as an overlay (like a popup or modal) by clicking on the Navigate to dropdown

We also have the option to scroll to, open link of or go back

##### Animation

Additionally we can change the animation type when transitioning

These will be similar to ones you find in PowerPoint or Google slides

<a name=Flow></a>

#### Flow

To create a flow select an artboard, head to the Prototype tab and hit the add button on the Flow start point


Flows are made so you can different starting point when demoing [see [#demo](#demo)]. In fact they can be put into demo mode by hitting the arrow key in the flow. 


✨**Tip**: You can have multiple flows in 1 document, this might be useful if you have a mobile and a desktop version or you just want to start your demo off in different places instead of navigating to the page

<a name=Demo></a>

### Demo

Demos can be used to show potential stakeholders what screens are envisioned and how interactions will work. To enter into demo phase, click the play button on the right of the top header

After clicking on this, you will be launched into the interactive mode on a new window (this can then be shared with other people). Within the demo we can interact with the components we made in [#Interactions](#Interactions) 

---


### Export

To export a frame or whatever you have selected as svg, png, jpeg, or pdf, all that you want exported selected then go to Design->Export and select the export options

![export](img/export.png)

To export you project as .fig (Figma's proprietary file format) click on the Figma icon->File->Save local copy...

You can also export certain sections by using the slice tool under the same dropdown as frame in the header

![slice](img/slice.png)

Congrats on completing your first Design on Figma 🎉

<a name=Toolbar></a>

### Toolbar

![toolbar](img/toolbar.png)

The tool bar contains (from left to right):

* mouse to select or hand to pan the canvas
* pencil to draw on the canvas (has option for highlighting as well)
* shapes - they act the same as sticky notes
* sticky notes - basically a text box
* text box
* connector (to show flow of 1 idea to the next)
* stamps 
* other widgets, plugins, templates and more

These can be dragged onto the canvas to be placed or clicked to activate the tool and click on the canvas to instantiate an instance 


<a name=Sharing/Collaborating></a>

## Sharing/Collaborating

To share your Figma file click on the blue share button on the header and it will bring you to this popup.

Here you can invite people to view only or edit the file. Please note that by default anyone with the link can view it and you would need to click on **Anyone with the link** dropdown to change it to **Only people invited to this file**. Otherwise you can publish to the community using the second tab on the top ribbon or even embed the figma file as a widget (as HTML) by clicking on **Get embed code**

<a name=Pricing></a>

## Pricing

Figma has **3 tiers** for both Figma and FigJam. 

1. Free tier - usually for groups of 2 or forever alone
2. Figma Professional - for regular teams and team libraries and private/shared projects
3. Figma Organization - enterprise edition with SSO and organization level libraries

⚠ Note for **STUDENTS OR EDUCATORS**, Figma profession is **FREE** ⚠

![pricing](img/pricing.png)

<a name=Fonts></a>

## Fonts

Figma has many fonts coming from Google fonts. If you have a custom font in mind with the font files (most likely ttf or otf file) you need to:

1. download the [Figma desktop](https://www.figma.com/downloads/) app to edit custom text (although you can view it in the browser version)
2. or download the font installer [here](https://www.figma.com/downloads/) and reload all Figma tabs

<a name=Resources></a>

## Resources

General Figma docs: 

Installing Fonts: 

Figma desktop: 

Pricing: 




[**🔝 Back to Top**](#top)


Thanks <3 
