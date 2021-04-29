---
title: Metadata
nav: Metadata
topics:
---

-----------------

## How do we describe things?

In the CDIL, we use the simple [Dublin Core Metadata Pratices](https://en.wikipedia.org/wiki/Dublin_Core), which provide us a standard for how we format our descriptions and make the information readable for a large audience. This section will cover the details of the different formats and guidelines for all common sections of a metadata sheet that technicians will encounter. 

Not all of the fields listed below will appear on every metadata sheet. Some metadata sheets will have extra fields depending on the subject material. As a general rule, though, these are the most common fields you will encounter when entering metadata. It may seem like a lot of information, but each field serves a purpose for both preservation and access.

### Common Metadata Fields

- **Title:** either the given title of an article or item, unique to that one item. For photographs in a series, this can be either “Founder’s Day parade [01]” (no quotation marks in entry) or a generalized brief description of the photograph. All words after the first word in the title should be lower case unless referring to a proper noun such as a name or place (Dylan Fuller, Empire State Building, Idaho, etc.)

- **Description:** a detailed accounting of the item. This includes small details such as “mountains can be seen in the background”, and should include names when known and list if either person or place is unknown in the material. All descriptions should be in complete sentences and single spaced between sentences.

- **Creator:** This is the individual or company that created the item. For articles or publications, this is the author. For photographs, either the photographer or the studio. Last name, first name “nickname” middle name maiden name, birthdate-death date if known. This is considered an enhancer for the material, and can be linked to records already available on the internet. This increases the usability and accessibility of our collections to a much broader audience.

- **Date:** refers to the date the item was created/published. This field is required and CANNOT BE LEFT BLANK. This entry is represented in YYYY-MM-DD format officially. Other acceptable formats include:
    - YYYY when no other information is provided
    - YYYY-MM when no day is provided
- YYYY/YYYY for a range where the event is continuously occurring

- **Date is Approximate:** This field lets anyone looking at the collection know that we are certain of our estimation, not that our estimation is the accurate date. Only fill out yes if the Year, Year-Month, or an actual estimation is provided. If date is accurate, leave blank.

- **Keywords:** words or phrases that describe or relate to the material. Think of keywords as how you the technician would search for the item. Another way to think of keywords is in terms of subjects. What subjects are described/depicted? These allow researchers and people interested in looking for one thing in particular to narrow the collections down to their interests. We use the Getty Art and Architecture Thesaurus for our keywords, which can be found bookmarked in Google Chrome on all of the computers in the lab. Multiple entries are encouraged when possible, and should be separated with a semi-colon. [Example: cows (mammals); farming (function)]. Some collections have a controlled vocabulary related to the subject material.

- **Relation:** This field indicates if there are any relationships between resources. An example of this would be if a collection contains material from another collection, or is similar to material in another collection. This is not an often used field, and will usually be populated by the Digital Projects Manager. Sometimes it gets cross-referenced as Spatial Coverage, but you will be notified before-hand.

- **Spatial Coverage:** Spatial coverage identifies the geographic and/or geospatial location of the item being described. If it is a photograph, list the location that is depicted; if it is an article or other textual material, list the location described. Locations should always be listed: Country—State—County—City—Identifier.

- **Latitude/Longitude:** geospatial coordinates on the surface of the Earth. To find these coordinates, please use [Google Maps](www.maps.google.com) or [iTouchMap](itouchmap.com/latlong.html). Copy/paste the coordinates from either of these sites into the field in the metadata sheet. If Excel tries to reformat it to only 2 or 3 decimal places, right-click on the Letter at the top of the column and select format. In the window that pops up, select number, and increase decimal places to 6. Sometimes this field is split into separate entries; other times it will be a combined entry.

- **Digital Collection:** This field contains the name of the digital collection to which all of the material you are working with belongs. It lets patrons, researchers, and those viewing the item know where they can find more materials related to this item in case they found it by searching for a subject, or through another linked entry. This also provides a connection with the physical material and helps individuals to know where it is located. The collection name will usually be completed by the Digital Projects Manager.

- **Contributing Institution:** Most of our digital collections are owned by the University of Idaho Library, but some of them originate from other institutions or individuals. Some digital collections are combinations of UI Library materials and materials from other institutions. Citing the contributing Institution notes attribution as well as protects UI from potential copyright issues. This field will always be filled in by the Digital Projects Manager unless it is specified in the collection on an individual item basis.

- **Source:** The original source of the material being scanned. Sometimes this is a single collection here at UI, sometimes it’s pieces of another collection presented in a different collection. A lot of the time, this will also be the call number or collection number or the physical reference of the item, so people are able to find the item in person if they want to.

- **Original File Name:** refers to either the collection of numbers and letters that designate its location within the library or the original file name that may have been edited to fit our standards here at the library. This field won’t always be on every metadata entry sheet.

- **Identifier:** file name, minus the extension (.jpg, .tif, .pdf, etc.) Identifiers let both viewer and the Digital Projects Manager recognize and find the digital item in the archive quickly. Without the correct identifier, the viewer is left to either the title or description to request a copy of the item, which can get difficult with the number of digital records the Library has.

- **Rights:** a copyright statement that consists of a free-text statement and a standardized rights statement. These statements indicate to viewers and researchers if permissions are required to use the material in publication, and how to attribute the item once used. A list of these can be found in your student folder in both Daily Scans on the Desktop and in your student folder in the W: drive. If you have any questions or aren’t certain of which statement applies to your project, ask the Digital Projects Manager.
Example of free-text statement: No Copyright. Material made available by donor/contributing institution/source (as applicable). For more information, please contact University of Idaho Library Special Collections and Archives Department at libspec@uidaho.edu.
Example of standardized rights statement: https://creativecommons.org/publicdomain/mark/1.0/

- **Format Original:** What was the item originally? A photograph? A newspaper clipping? This field specifies what the object was before digitization. Examples of original formats include: black-and-white photograph, color photograph, article, scrapbook, newspaper clipping, magazine, etc. There is no controlled vocabulary for this field.

- **Type:** This field indicates what the material contains. If it is an audio recording, input Sound; for video, input Image; MovingImage. Image refers to any form of picture or visual representation of an item, while Text can refer to any typed or written material. You may have multiple types per item, such as a newspaper clipping that contains an image and the related article.

- **Digital Format:** the digital format of the item. If the material is a PDF, the corresponding type is application/pdf; if the material is an image, the corresponding type is image/jpeg. Audio and video have similar entry styles. This field lets the viewer know what format the uploaded material is, and what they can expect when requesting the item for either publication or personal use. If you have questions, please refer to the Digital Projects Manager.

- **Language:** a three-letter abbreviation or code for the language used in the material. Most items in our digital collections are in English, or have an English translation attached to them. For this field, always input eng unless otherwise instructed.

- **Filename:** identifier PLUS extension (.jpg, .tif, .pdf, .wav, etc.) Our digital content management system uses this field to correctly link the digitized item to the corresponding metadata entry. When possible, a pre-set formula will add the correct extension to each identifier entered in previous columns to save from any re-entry errors.


## Components Includes

`workshop-template-b` contains a series of [Liquid "includes"](https://jekyllrb.com/docs/includes/) to add basic [Bootstrap components](https://getbootstrap.com/docs/4.1/components/) to your Markdown content.
Examples below demonstrate the includes.

--------

#### Figures 

`{% raw %}{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Library workshops!" width="75%" %}{% endraw %}`

{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Library workshops!" width="75%" %}

----------

#### Alerts

`{% raw %}{% include alert.html text="This is a Bootstrap [Alert](https://getbootstrap.com/docs/4.1/components/alerts/)" align="center" color="success" %}{% endraw %}`

{% include alert.html text="This is a [Bootstrap Alert](https://getbootstrap.com/docs/4.1/components/alerts/)" align="center" color="success" %}

-----------

#### Link Buttons 

`{% raw %}{% include button.html text="Bootstrap Docs" link="https://getbootstrap.com/docs/4.1/components/buttons/" color="info" %}{% endraw %}`

{% include button.html text="Bootstrap Docs" link="https://getbootstrap.com/docs/4.1/components/buttons/" color="info" %}

---------

#### Cards

```{% raw %}
{% capture text %}
1. Can add more complex text using markdown.
2. Use a Liquid capture to create the text.
3. It magically becomes a [Bootstrap Card](https://getbootstrap.com/docs/4.1/components/card/).
{% endcapture %}
{% include card.html text=text header="Example Card" title="Title example" img="uidaho-workshop.jpg" %}{% endraw %}
```

{% capture text %}
1. Can add more complex text using markdown.
2. Use a Liquid capture to create the text.
3. It magically becomes a [Bootstrap Card](https://getbootstrap.com/docs/4.1/components/card/).
{% endcapture %}
{% include card.html text=text header="Example Card" title="Title example" img="uidaho-workshop.jpg" %}

------------
