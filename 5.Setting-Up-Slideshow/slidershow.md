CREATING A SLIDER
=================
Introduction
------------
StrikingR has 5 different types of sliders

 1. 5 different built-in sliders which use a custom post type to show individual slides:
 2. The Revolution Slider built-in as a plugin
 3. The Portfolio Images Widget, which is a swipable, responsive slider which draws upon the portfolio custom post to display portfolio featured images, with all of the filtering options of this custom post.
 4. The Carousel and Product Carousel, which are swipable, responsive carousels available by shortcode only.  The Carousel can show images (placed in a slideshow), and the featured image of each post in a post or portfolio category (s).  The Product Carousel is different.  It can grab the individual products from a custom post type based ecommerce plugin, such as Woocommerce, WP-Ecommerce, or Easy Digital Downloads, etc.
 5. Testimonial slider – shortcode only.  Rotating testimonials including avatar/picture of person providing the testament.
 
**There is no limit to the number of slideshows in StrikingR**.  You can have 10 slideshows on a page if desired, and as many in a website as can be dreamed up!  The Roundabout & Accordion slider are for available solely in the Feature Header Area. Three sliders -> Nivo, Ken Burner and Revolution Slider are also available via shortcode to be placed anywhere in webpage content.

Basic Slide Creation
--------------------
Slides for the 4 sliders listed in #1 above are created using the **Slider items** / **Add New** menu link in the Wordpress Dashboard.  Click on “Add New” will bring you to the **Add New Slider Item** panel, which is used to create a single new slide for any of the 4 built in sliders.  The image below illustrates all the important aspects of this panel:

![Add new slider][1]

A single slider item requires all the following elements in order to be able to be used in a slideshow:

 - A title in the title field.
 - A category to be grouped within
 - A featured image – which is the actual image that will show in the slideshow
 - A order number to set the order of the slides (optional)

### Featured Image ###
The featured image of any post type in Wordpress is the image that is “attached” to the post and which can be shown independently from the rest of the post content.  How it is displayed depends upon how a theme is built for its post types and its templates.  For StrikingR slider items, use the Featured Image Metabox to attach 1 image only to the slider item, and this image is the image displayed in a slideshow.  Do not put any images into the post content field.  The StrikingR code draws upon the Featured Image only for displaying a slider image.

### Slideshow Grouping by Categories ###
Slider items should be are grouped into categories.  The actual selection process for showing slides in a slider is by choosing a category to display, not by choosing single slides.  

> Exameple: 
if there are 4 images to be shown in the Home webpage of thesite, then there should be 4 separate slider items created, one for each image, and they would be grouped into one category, most likely called “homepage” or something similar.  As you will see below, you will then select this category “homepage” using a setting in the **Page Options Metabox** when deciding upon the contents of a slideshow.

### Slideshow Order ###
The order of which the slide show items are presented can be influenced by adjusting its order attribute.  Slider items in a category normally will display in the order of their creation (which is order by Wordpress id#).  But using the order attribute, the order can be reset to a sequential format with each slide showing according to the number position assigned to it. 

Individual Slider Item Settings
-------------------------------
Below the slider item content editor is the Slideshow Item Options metabox. This metabox has 2 admin tabs:

 1. Easy Slideshow Creator
 2. Single Slide Options

The Easy Slideshow Creator tab is explained in the next section below.  The Single Slide Option admin tab is used when creating individual slider items for the 4 built-in sliders as detailed in the 2 preceding pages.

![Single slider settings][2]
 
All of the settings in Single Slide Options are optional, and used as follows:

### Slide Caption (Optional): ###
All of the slider support captions.  The caption by default will be the Slider Item Title drawn from the Title field.  However, any content placed in the caption field will be displayed instead of the title.  If you do not see a caption being displayed, go to the Slideshow Panel / admin tab for the slider type, and check to see that the caption setting is enabled.  Shortcoded sliders have their own separate caption On/Off setting.

### URL (optional) / Link Target ###
Slider items have the ability to have clicking on the picture link to another target in the site, or externally.

Use the URL setting to make a selection per the above image.  When one of the options is clicked up, for example Link to Page, a new selector will appear with a scrollable list of pages from which to select for the linking url.  

And as usual, one can also set the way in which one links using the Link Target setting.

### Displaying the slideshow created above ###
So now undoubtedly we have created 3 or 4 slides, and grouped them all in a category.  Each slide has a title, a featured image, has been grouped into the category, and perhaps has a custom caption, and might even be linking to somewhere else in the website if clicked upon.  So how to display?

At the outset of this slider section it was indicated that certain sliders are only available in the feature header area, and others are also shortcoded. Following are the instructions for each option:

Displaying a slideshow in the feature header of a webpage
---------------------------------------------------------
Below any page or post in editing is found the **Page General Options** Metabox containing 3 admin tabs with settings.  We need the **Feature Header Settings** tab as it contains all the settings for choosing what content to show in the Feature Header area.

![Feature header type slideshow][3]

As per the above diagram, go to this tab, and select Slideshow in the **Feature Header Type** setting.  Next go further down and you will see 3 other settings:  Slideshow Source, Slideshow Number, and Slideshow Type.  Here is where the slideshow output is determined for this webpages feature header area.

Scroll the list in the Slideshow source to find what you want to display.  Notice that it shows slide categories, and also Blog Post Categories and Portfolio Categories.   The “Built-In” sliders can also show the featured images of Blog and Portfolio posts!

After making the appropriate selections, “Update” the panel you are editing, and then go view the webpage, and now the slideshow selected will display in the feature header area.

![Page slideshow options][4]

The Easy Slideshow Creator
--------------------------
Sometimes there is a desire to just drag and drop some images to quickly create an image slideshow.  With no need for linking abilities, or to embed videos or other advanced functions.  For Striking Responsive a new custom slideshow formation ability was added – the **Easy Slideshow Creator** to facilitate quick drag and drop image slideshow creation.  It is the first admin tab found in the Slideshow Item Options Metabox found below the content editor:

![Easy slideshow creator][5]

### How does it work? ###
The first step is to **Add A New Slider Item** and give it a Title, and IMPORTANTLY - > give it a unique category.  If you  When you have finished all settings you goto the  Easy slideshow tab in the slider item settings panel and hit the Add images button.

![Add images for easy slideshow creator][6]

A window will popup from the wordpress media library and multiple image can be selected to add to that single slider item. 

![Select images][7]

Once done selecting (or uploading) your images for the slideshow click on the "Add Images" button of the wordpress  media library. You will return to the single slider item and all selected images will now show in a listed way. You can drag them around  within the list to alter its order within the actual slideshow at the front of your website.

After the insert of all your images you might see something that looks like this.

![Easy creator images][8]

As mentioned before one can have the ability to list captions within slider items. When the caption has been set to the caption of the image the slideshow will pull the caption as entered in the wordpress media library for each particular image. In order to avoid swapping back and forth from the slider item -> easy slideshow creator to the media library we added the ability to directly change the image title, caption or description while you are working  and adding images in the easy slideshow creator. Click on the edit button and you will get the ability to edit all those indiviual image settings.

![Edit slideshow image][9]

> **Note**:  
We still advise to add the individual slider item to its own category which makes selecting the slideshow in a page more easy for you.

![Select slider categories][10]

Once you have created the slider item and added all the images in the easy slideshow creator, created  a category and added that slider item to that category you are done and you can publish the slider item.

### The next step ###
The next step is to watch your slideshow. For this you need to create a page and in that page in the striking Page General Options in the Featured Header Settings Tab you make sure to set its type to Slideshow.

![Feature header type][11]

You also need to select in that same  Featured Header Settings Tab the slideshow  category and the slider of your choice. As said we have 5 different sliders buildin that support the Striking Slider item custom post type.

![Slideshow source][12]

Publish the page and watch it in the front of your website. If all done correctly you might see this magnificent slideshow.

![Slideshow type][13]


  [1]:https://raw.github.com/strikingdoc/Striking/master/images/5/add_new_slider.png
  [2]:https://raw.github.com/strikingdoc/Striking/master/images/5/slideshow_metabox.png
  [3]:https://raw.github.com/strikingdoc/Striking/master/images/5/feature_header_slideshow.png
  [4]:https://raw.github.com/strikingdoc/Striking/master/images/5/page_slideshow_options.png
  [5]:https://raw.github.com/strikingdoc/Striking/master/images/5/easy_slideshow_creator.png
  [6]:https://raw.github.com/strikingdoc/Striking/master/images/5/creator_add_images.png
  [7]:https://raw.github.com/strikingdoc/Striking/master/images/5/select_images.png
  [8]:https://raw.github.com/strikingdoc/Striking/master/images/5/slideshow_images.png
  [9]:https://raw.github.com/strikingdoc/Striking/master/images/5/edit_slideshow_image.png
  [10]:https://raw.github.com/strikingdoc/Striking/master/images/5/slider_categories.png
  [11]:https://raw.github.com/strikingdoc/Striking/master/images/5/feature_header_type.png
  [12]:https://raw.github.com/strikingdoc/Striking/master/images/5/slideshow_source.png
  [13]:https://raw.github.com/strikingdoc/Striking/master/images/5/slideshow_type.png