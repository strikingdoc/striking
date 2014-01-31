Set Up Portfolios
=================
Portfolio item is a single entity of your portfolio collections. It can be a photo, a project, a design or a product etc.

With portfolio shortcode you can showcase a collection of portfolio items in a page. You can also determine the basics of your portfolio in the **Striking -> Portfolio options page.

Creating A portfolio item
-------------------------

You want to add a new portfolio item, follow the steps below:

1.  Go to **Portfolio items-> Add New**.
2.  Select a **Featured Image**. It will show as thumbnail in the portfolio items list.

 > Learn from [wordpress offical document](http://en.support.wordpress.com/featured-images/) about how to add a featured image.
 
 > Go to **Striking -> Portfolio**, locate **Featured Image** module, you can change the featured image settings.

3.  Locate **Portfolio Item Options** module. Change the settings to you prefer.
4.  Then fill the title, and add the detail of portfolio to the content editor. You can also add the description text that will show in the portfolio items list page to the <span class="module">Excerpt** module.</span>
5.  Once you have done, click **Publish** button.

### Giving Portfolio item a Parent Page on Breadcrumbs ###

If you want to give portfolio item a parent page on breadcrumbs, you should follow the steps below:

1.  Go to **Striking -> Portfolio**. Locate the **Portfolio General** module.
2.  Choose the page you want to be the parent page of portfolio items on the breadcrumbs in the **Breadcrumbs Parent Page** dropdown. This will used as global configuration.
3.  when you are editing or creating a portfolio item, you can set portfolio breadcrumbs parent page either. 
In the edit page or add page, Locate the **Portfolio Item Option** meta box.

 > If you can't find <span class="module">Portfolio Item Options** meta box, locate the top of the page, click the **Show on screen** button. Select the metabox to make sure the option to be shown. 
 
4.  Choose the page you want to be the parent page of this portfolio item on the breadcrumbs in the **Breadcrumbs Parent Page** dropdown. This will override the global configuration which set above.

### Changing Permalink Slug ###

When you using Wordpress **Permalink settings**, the url of a single portfolio item page will be http://www.domain.com/portfolio/{portfolio-name}.

Sometimes, we want change portfolio in the url to another. http://www.domain.com/image/{portfolio-name} for example, Just follow the steps below:

1.  Go to **Striking -> Portfolio** in the backend.
2.  Locate <span class="module">Portfolio Rewrite URL** Module.</span>
4.  Change Permalink Slug to you want.
5.  Click **Save Changes**

## Show Your Portfolio items ###

After you create portfolio items, you'll need a portfolio index page to group them, please follow the steps below:

1.  Create a new page by going to **Page -> Add New**
2.  Then use **Shortcode Generator** to generate the shortcode for portfolio. After configuration, remember click **Insert** Button. 

 > Check out [here](#setting_up_pages|using_shortcode) to learn more about **Shortcode Generator**. 
3.  Then **Publish** the page.

### Example shortcodes ###
#### Show a portfolio items list without page navigation. ####

    `[portfolio nopaging="true"]`

#### Show a Sortable portfolio items list. ####

    `[portfolio sortable="true"]`

#### Show the portfolio items list with specific categories. ####

    `[portfolio cat="document,image"]`

#### Show a Sortable portfolio items list with specific categories. ####

    `[portfolio sortable="true" cat="document,image,video"]`
 > In this way, the order of the tabs will be document, image, video.

#### Only show the portfolio items list with specific ids. ####

    `[portfolio ids="200,300"]`
 > You can get the id of the portfolio item from the url of the portfolio item edit page.
etc: in the url ( **localhost/wordpress/wp-admin/post.php?post=**1235**&action=edit** ), the id is 1235.

#### Don't group the lightbox of the portfolio items on portfolio list page. ####

		`[portfolio group="false"]

 > It's useful when you want display a set of 'gallery' portfolio items, each lightbox will only display it's own images.

Different Portfolio item Types
------------------------------

Portfolio item has six types, They will help you to show your portfolio item in different ways on the portfolio list page.

### Image ###

It will pop up a lightbox with a image when click the thumbnail of portfolio item. Normally, the feature image of portfolio item will be shown in lightbox without setting.

If you want to show the different image from the thumbnail, you can use **Fullsize Image for Lightbox option in **Portflio Item Options.

### Gallery ###

If you want to show many images for this portfolio when click on a single portfolio item. This type will help you:

1.  Fisrt, you must select this type in the **Portfolio Type dropdown menu. When you select this type, the **Portfolio Gallery will be shown on the edit page.
2.  Click the **Add Image button in the **Portfolio Gallery module.
3.  Upload a image for your portfolio by normal wordpress upload steps and then click **Insert Into Gallery button to add it to the gallery.
4.  After updating, these images will be shown in the lightbox when you click the thumbnail of portfolio item.

### Video ###

If you want to show video when click on a single portfolio item, You can use this type to show it. After you select this type and input a video url ( flash, youtube or vimeo) in **Video Link for Lightbox. When you click the thumbnail of portfolio item, it will popup a video box.

### Document ###

If just want the portfolio item on the portfolios list page just link to the single portfolio item, you can set portfolio type to 'Document'.

### Lightbox ###

If you want to display a external site iframe, or display some text on the lightbox, you can set portfolio type to 'Lightbox'.

### Link ###

You can choose this type. Then set **Link for Portfolio item and **Link Target options. The visitor can go to the page of the url you set when clicking the thumbnail of portfolio item.`