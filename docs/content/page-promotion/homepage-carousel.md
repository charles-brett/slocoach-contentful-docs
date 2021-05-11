# **Homepage Carousel**

## **Overview**

The homepage carousel is a slideshow of items defined using the [Page Promotion](/content-models/#page-promotion) content model.

#### **Fields**

The carousel requires the following fields (See [Page Promotion Content Model](/content-models/#page-promotion) for more info):

- <small><strong>Promotion Title:</strong> Not displayed, just used for a user friendly name in Contentful - "Homepage Carousel"</small>
- <small><strong>Promotion Identifier:</strong>  The unique identifier for this content - "homepage_carousel"</small>
- <small><strong>Type:</strong> The type of this promotion content - Carousel</small>
- <small><strong>Page Tiles:</strong> 2-5 page tiles that will appear in the slideshow (See below)</small>

Each page tile requires the following fields (See [Page Tile Content Model](/content-models/#page-tile) for more info):

- <small><strong>URL:</strong> The path that clicking on the Name will take you to e.g. "/coaches/billy-vunipola" or "/groups/some-group"</small>
- <small><strong>Image:</strong> An image that will be used as the background for this slide</small>
- <small><strong>Name:</strong> The name of this slide e.g. "Billy Vunipola" or "Some Group"</small>
- <small><strong>Title:</strong> The title of this slide e.g. "I want to improve my tackling" or "I want to meet new people"</small>
- <small><strong>Description:</strong> The description of this slide. e.g. "England and British & Irish Lions Forward" or "A Place for Some People"</small>

An example of what this will end up as is :

> I want to improve my tackling<br/>
**Billy Vunipola** _[links to /coaches/billy-vunipola]_, England and British & Irish Lions Forward
