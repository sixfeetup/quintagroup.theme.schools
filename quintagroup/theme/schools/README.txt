Schools is a free diazo theme for Plone 4.1

Features
--------

**Customizable logo**

 Chameleon diazo theme comes with default Plone logo.  You can replace it with your own as you would do it in default Plone: in ZMI customize  portal_skins -> sunburst_images -> logo.png.

**Configurable left/right column width** 

 Site Setup -> Diazo Theme -> Advanced Settings. In 'Parameter expressions' textarea change the 'columnonewidth' or/and 'columntwowidth' parameters values respectively.

**Improved thumbnail display view**

 Switch to Thumbnail view

**Top image**

 Replaceable header image for the whole site or site sections. To have new top image, add image with ``topimage`` shortname into desirable location on site. Default image size is 993*107px. 

 In case you upload higher image - it will not be completely displayed unlesss you configure ``logo_min_height`` value in 'Diazo theme' panel -> 'Parameter expressions' tab. Replace default value 107 with a new header height.

**Top portlet**

 Right top area is reserved for a portlet. The first portlet from right column is displayed there.

**Theme Colors**

 У темі можна змінити такі links colors: ``links_color``, ``hover_links_color``, and ``visited_links_color``. Щоб це зробити, потрібно перейти до Site Setup -> Diazo Theme -> Advanced Settings. In 'Parameter expressions' textarea change the 'links_color' or/and 'hover_links_color' or/and 'visited_links_color' parameters values respectively
  
**Carousel Banner**

 Rotating banners can be added in case you install Products.Carousel add-on. Custom Carousel display style applies automatically to carousel banner.
 
 To create a banner on the front page - go to the 'Carousel' tab in the task bar. Set carousel options and select 'Carousel Banner' from 'Add new...' drop-down menu. Upload image that will be used as one rotating banner, type its title and text (will be displayed under the image), and provide web address image title will be linked to. Add as many carousel banners as you need. 
  
 Optimum image dimensions are  397*288px. There are 4 demo images that might be used as demo banners - see 'src' folder within theme package (quintagroup -> theme -> schools).

**Portal Slogan**

 To change the theme slogan 'Free Theme for Plone' - go to Site Setup -> Diazo Theme -> Advanced Settings. In 'Parameter expressions' textarea change 'slogan' parameter value. If the parameter has no value, than the slogan will not be displayed on the website.

**Editable footer** 

  Customize: portal_view_customizations -> plone.footer

**Supported Add-Ons**
  Additional features can be activated:

* ``Products.Carousel``
   Adds adjusted styling to Carousel

* ``quintagroup.dropdownmenu``
   Adds adjusted styling dropdown menu

* ``Products.LinguaPlone``
   Adds multilingual functionality. Adjusted styling for language selectors.

* ``Products.PloneFormGen``
   Adds TTW Form Generator feature.

Dependencies
============

* plone.app.theming

Recommended
===========

Theme was tested with:

* Plone 4.1
* plone.app.theming 1.0b9
* Products.Carousel 2.1
* Products.ContentWellPortlets 4.1.0
* Products.PloneFormGen 1.7.0
* quintagroup.dropdownmenu 1.2.5
* Products.LinguaPlone 4.1.1

Home Directory
==============

http://skins.quintagroup.com/schools

Authors
=======

* Yuriy Hvozdovych
* Taras Peretiatko 
* Volodymyr Rudnytskyy
* Serhiy Valchuk  

Quintagroup: http://quintagroup.com, 2006-2012
