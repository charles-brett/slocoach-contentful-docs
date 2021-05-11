# **SLOCOACH Content Models**

## **Content Wrapper**

#### Overview

The content wrapper model will be used to define a generic piece/pieces of content that can be loaded in a certain slot (e.g. The Homepage Promotion could contain a [Page Promotion](#page-promotion) object of type carousel)

#### Fields

> <small>All fields may or may not be used by a specific implementation of this content model. The required fields for a piece of content, and what they are used for, can be found here : @TODO ADD LINK TO CONTENT PAGE</small>

##### **Title**

<span style="color:red;margin: -20px -2px;display: block;"><sup><sub>REQUIRED</sub></sup></span>

<small>The unique title for this content wrapper</small>

##### **Content Identifier**

<span style="color:red;margin: -20px -2px;display: block;"><sup><sub>REQUIRED</sub></sup></span>

<small>The unique identifier for this content wrapper. This must only contain lowercase alphanumeric characters and underscores (e.g. some_identifier)</small>

##### **Content**

<span style="color:red;margin: -20px -2px;display: block;"><sup><sub>REQUIRED</sub></sup></span>

<small>A collection of content related to this wrapper</small>

<small>Currently accepted content model types include :</small>

- <small>Page Promotion</small>
- <small>Page Section</small>

## **Page Promotion**

#### Overview

The page promotion model will be used as a template for main page promotions, generally at the head of a page (e.g. The homepage carousel will use Page Promotion as it's content model).

#### Fields

> <small>All fields may or may not be used by a specific implementation of this content model. The required fields for a piece of content, and what they are used for, can be found here : @TODO ADD LINK TO CONTENT PAGE</small>

##### **Promotion Title**

<span style="color:red;margin: -20px -2px;display: block;"><sup><sub>REQUIRED</sub></sup></span>

<small>The unique title for this promotion</small>

##### **Promotion Identifier** 

<span style="color:red;margin: -20px -2px;display: block;"><sup><sub>REQUIRED</sub></sup></span>

<small>The unique identifier for this promotion. This must only contain lowercase alphanumeric characters and underscores (e.g. some_identifier)</small>

##### **Type**

<span style="color:red;margin: -20px -2px;display: block;"><sup><sub>REQUIRED</sub></sup></span>

<small>The type of promotion, selected from a list of options</small>

<small>Current options include :</small>

- <small>Carousel</small>

##### **Page Tiles**

<small>A collection of [Page Tile](#page-tile) Objects</small>

------------------------------------------------------------------------------------------------------------------------

## **Page Tile**

#### Overview

The page tile model defines a template for a data item to be included in a [Page Promotion](#page-promotion)

#### Fields

> <small>All fields may or may not be used by a specific implementation of this content model. The required fields for a piece of content, and what they are used for, can be found here : @TODO ADD LINK TO CONTENT PAGE</small>

##### **URL**

<small>The path to link to inside the page tile, if the promotion type allows for it. (e.g. /coaches/billy-vunipola)</small>

##### **Name**

<small>The name of the entity used by the implementation of this tile. (e.g. Billy Vunipola)</small>

##### **Image**

<small>The image to be used by the implementation of this page tile</small>

##### **Title**

<small>The title to be used by the implementation of this page tile</small>

##### **Description**

<small>The title to be used by the implementation of this page tile</small>

------------------------------------------------------------------------------------------------------------------------

## **Page Section**

#### Overview

The page section model will be used as a template for generic section content (e.g. The 'What you get' and 'How it works' sections use this).

#### Fields

> <small>All fields may or may not be used by a specific implementation of this content model. The required fields for a piece of content, and what they are used for, can be found here : @TODO ADD LINK TO CONTENT PAGE</small>

##### **Title**

<span style="color:red;margin: -20px -2px;display: block;"><sup><sub>REQUIRED</sub></sup></span>

<small>A unique title for this page section</small>

##### **Section Identifier**

<span style="color:red;margin: -20px -2px;display: block;"><sup><sub>REQUIRED</sub></sup></span>

<small>The unique identifier for this section. This must only contain lowercase alphanumeric characters and underscores (e.g. some_identifier)</small>

##### **Single Media**

<small>A single piece of media for use by the implementation of this section</small>

##### **List Items**

<small>A collection of [Section List Item](#section-list-item) objects</small>

------------------------------------------------------------------------------------------------------------------------

## **Section List Item**

#### Overview

The section list item model defines a template for a data item to be included in a [Page Section](#page-section)

#### Fields

> <small>All fields may or may not be used by a specific implementation of this content model. The required fields for a piece of content, and what they are used for, can be found here : @TODO ADD LINK TO CONTENT PAGE</small>

##### **Title**

<small>A single piece of media for use by the implementation of this section list item</small>

##### **Description**

<small>A single piece of media for use by the implementation of this section</small>

