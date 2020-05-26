# How to use

## Scroll And Load widget

- Locate the "Scroll And Load" widget in the widget panel, under category "SCROLL AND LOAD", and place it anywhere on the page.
  * It should not be placed in a section or inner section on it's own, or you will just have a empty section.

## Apply Type 

- Infinite Scroll

- Load More

  * "Assign Load More ID" and apply Elementor button widget.
  
## Pagination For

- Elementor Pro Archive Posts

  * Set pagination for "Archive Posts" to "Previous/Next" or "Numbers + Previous/Next".
  
- Elementor Pro Posts

  * Set pagination for "Posts" to "Previous/Next" or "Numbers + Previous/Next".
  
- Elementor Pro Single Post

  * Read "Assign Single Post ID".
  
- Elementor Pro Archive Products
  
- Elementor Pro Products

  * Enable pagination for "Products".
	
## Custom Selectors

- Navigation Selector

  * ID or class of the pagination container.
  
- Next Selector

  * ID or class of the next anchor in the pagination container.
  
- Content Selector

  * ID or class of the items container.
  
- Item Selector

  * ID or class of the item inside the items container.
  
## Image Ratio

- If post thumbnail has image ratio.

  * Should only be used with Elementor Pro Archive Posts and Elementor Pro Posts.
  
  * Should only be used if "Masonry" setting is set to "Off".
     
## Bottom Offset

- If your site has a footer.

  * This only applies to "Infinite Scroll". The higher the number the sooner new items will load. 
   
## Animation Time

- The items render animation time when new items are loaded.

## JetSmartFilters

- Enable for JetSmartFilters compatibility.

  * Only works with Elementor Pro Archive Posts, Elementor Pro Posts, Elementor Pro Archive Products and Elementor Pro Products.
  
  * Only works with pagination base "page".
  
  * Set filter setting "Apply type" to "AJAX" and "Apply on" to "Value change".
   
## Assign Load More ID

- Insert a section or inner section on the page and give it ID or class (E.g. load-more-container). And insert a Elementor button widget inside.

- In the input for "Assign Load More ID" insert ID (E.g. #load-more-container) or class (E.g. .load-more-container).

  * Mandatory if you have applied type "Load More".
   
## Assign Loading Image ID

- Insert a section or inner section on the page and give it ID or class (E.g. loading-image-container). And insert a image widget inside.

- In the input for "Assign Loading Image ID" insert ID (E.g. #loading-image-container) or class (E.g. .loading-image-container).

  * Optional.
   
## Assign No More Items ID

- Insert a section or inner section on the page and give it ID or class (E.g. no-more-items-container). And insert a heading or text widget inside.

- In the input for "Assign No More Items ID" insert ID (E.g. #no-more-items-container) or class (E.g. .no-more-items-container).

  * Optional.
  
## Assign Single Post ID

- Go to "Templates" and "Add New". Select "Single" and "Post".

- Insert a section on the page and give it ID or class (E.g. single-post-container). And insert "Post Title" widget, "Post Content" widget and "Scroll And Load" widget inside.

- In the input for "Assign Single Post ID" insert ID (E.g. #single-post-container) or class (E.g. .single-post-container).

  * Sections for "Assign Load More ID", "Assign Loading Image ID" and "Assign No More Items ID" should NOT be placed inside this section (E.g. single-post-container). They should be added to their own sections after this section (E.g. single-post-container).

# Changelog

- Version 1.0.0

  * Fixed: Elementor post thumbnail missing image ratio on more load.
  
  * Fixed: Scrolling to the bottom of the page is now possible when using "Infinite Scroll". Changed "Bottom Offset" default value.
  
  * Added: Image ratio changed to user setting.
  
  * Added: Elementor Pro Single Post.
  
  * Removed License
  
