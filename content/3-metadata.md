---
title: Metadata
nav: Metadata
topics:
---

-----------------

## How do we describe things?

We use the simple [Dublin Core Metadata Practices](https://en.wikipedia.org/wiki/Dublin_Core), which provide us a standard for how we format our metadata and make the information readable for a large audience. This section will cover the details of the different formats and guidelines for all common sections of a metadata spreadsheet that technicians will encounter. 

Not all of the fields listed below will appear on every metadata spreadsheet. Some metadata spreadsheets will have extra fields depending on the subject material. As a general rule, though, these are the most common fields you will encounter when entering metadata. It may seem like a lot of information, but each field serves a purpose for both preservation and access.

If you have questions, please refer to CDIL staff.

---

### Metadata Fields for Students to Fill In

##### title 
- *required*
- The name of an item. This is either the given title of an item or a short, descriptive set of words to identify the item.  
- All words after the first word in the title should be lower case unless referring to a proper noun such as a name or place (Dylan Fuller, Empire State Building, Idaho, etc.)
- For questions on how to title photographs in a series, please refer to CDIL staff.
- Example values: `Hecla Mine`; `Students playing baseball`

##### description
- *required* 
- A detailed, 1-3 sentence accounting of the item, communicating what it is and its contents.
- This includes small details such as "mountains can be seen in the background", and should include names when known. 
- All descriptions should be in complete sentences, with a single space between sentences. Descriptions should be no more than 1-3 sentences.
- Example value: `Students on lawn in front of old Gault Hall, which was torn down in 2003 to make room for the current Living Learning Center.`

##### subject
- *required* 
- Words or phrases that describe or relate to the material. Think of how you would search for the item. What key words would you use to find what is described/depicted in the item? 
- Subjects allow researchers and people interested in searching for one thing in particular to narrow the collections down to their interests. 
- Use the [Getty Art and Architecture Thesaurus](http://www.getty.edu/research/tools/vocabularies/aat/) to locate subject terms. 
- Multiple entries (2-4) are encouraged when possible, and should be separated with a semi-colon. Some collections have a controlled vocabulary related to the subject material, so be sure to check with a supervisor before you start assigning subjects.
- Example values: `children; parades; automobiles`; `cows (mammals); farming (function)`

##### creator
- The individual or entity that created the item. 
- For articles or publications, this is the author. 
- For photographs, either the photographer or the studio. 
- Use format: Last name, First name
    - If additional names are included, use this order: Last name, First name "Nickname" Middle name Maiden name.
- Example values: `Riegger, Hal`; `Barnard Studio (Wallace, Idaho)`

##### date  
- Refers to the date the item was created/published. 
- If you know the exact date for an item, fill it in using the yyyy-mm-dd format.
- If you only know the year and month, simply leave off the day: 1955-12. Likewise, if you only know the year, just enter the year: 1955. 
- If there is no year included with the item, you can estimate the date to the nearest decade if you know enough information about the content of the image or item. 
    - For example, if you think a photo was probably taken in the 1950s based on a car or clothing pictured, you can put '1950' or '1955' in the data cell. Be sure to fill in 'yes' for the 'date is approximate' cell in this situation.
- Example values: `1955-12-08`; `1955-12`; `1955`

##### date is approximate
- This field lets anyone looking at the collection know that we are certain of our estimation, not that our estimation is the accurate date.
- Only fill out 'yes' if the Year, Year-Month, or an actual estimation is provided. If date is accurate, leave blank.
- Example value: `yes`

##### location
- The geographic location(s) / place names to which the item is tied. 
- 'City, State' format, but can sometimes extend to 'City, County, State, Country' depending on the collection (check with a supervisor to be sure). 
- Separate multiple location entries for a single record with a semicolon (;).
- Example values: `Boise, Idaho`; `Potlatch, Latah County, Idaho`; `Jakarta, Indonesia`

##### latitude 
- A geographic coordinate specifying the north-south position of an item.
- Latitude and longitude can be found using [Google Maps](www.maps.google.com) or [iTouchMap](itouchmap.com/latlong.html). 
    - On [Google Maps](www.maps.google.com), search for the approximate location then right click on a point. Select the lat/long displayed at the top of the menu. This will copy the values to your clipboard.
    - On [iTouchMap](itouchmap.com/latlong.html), search or move the map to approximate location, then hold Shift and click on the spot. The lat/long will display below.
- Copy and paste the coordinates from either of these sites into the field in the metadata sheet. 
- The lat/long values will need to be split into the two fields. 
- Example value: `46.731634`

##### longitude
- A geographic coordinate specifying the east-west position of an item. Follow "latitude" instructions above to locate longitude data.
- Example value: `-117.165625`

##### identifier
- The unique identifier assigned to the object by the object’s (usually physical) source collection in Special Collections.
- This is usually found on the folder or box the object is in. 
- Example value: `ARG-02-16-1993`

##### format original
- This field specifies the format of the physical object that was digitized. 
- There is no controlled vocabulary for this field. Choose a word or phrase that best describes the format, and try to be consistent across items in a single collection.
- Example values: `black-and-white photograph, color photograph, article, scrapbook, newspaper clipping, magazine`  

##### format
- *required* 
- The digital format of the item. 
- This field lets the viewer know what format the uploaded material is.
- Choose from one of the following options: 
    - Image: `image/jpeg`
    - Document: `application/pdf`
    - Audio: `audio/mp3`
    - Video: `video/mp4`

---

### Metadata Fields for Staff to Fill In

##### filename
- *required* 
- Identifier PLUS extension (.jpg, .tif, .pdf, .wav, etc.) 
- The value must exactly match the actual filename, including capitalization. This value is case-sensitive!
- Our digital content management system uses this field to correctly link the digitized item to the corresponding metadata entry. 
- When possible, a pre-set formula will add the correct extension to each identifier entered in previous columns to save from any re-entry errors. 
- Filename will be generated by staff in most cases. 

##### source
- The physical source of the material being scanned. 
- Sometimes this is a single physical collection here at U of I and sometimes this is from several collections (check with your supervisor to identify the source of the items you are describing). 
- This will sometimes include the physical collection's collection number or call number,so people are able to find the item in person if they want to.
- Generally follows the pattern "collection name, organization name".
- Example value: `Idaho Cities and Towns Photographs, PG 5, University of Idaho Library Special Collections and Archives`

##### type
- This field indicates what type of content the material contains. 
- Choose from the following options: 
    - `Text`: Any typed or written material.
    - `Image;StillImage`: Photographs, negatives, etc.
    - `Image;MovingImage`: Video.
    - `Sound`: Audio recording.
- You may only choose one value for the type field. If you encounter an item with multiple types of content, choose the option that describes the item best.
- Example values: `Image;StillImage`; `Image;MovingImage`; `Text`; `Sound`

##### relation
- This field indicates if there are any relationships between resources. 
- An example of this would be if a collection contains material from another collection, or is similar to material in another collection. 
- This is not an often used field, and will usually be populated by the Digital Projects Manager. 

##### digital collection
- This field contains the name of the digital collection to which all of the material you are working with belongs. 
- It lets those viewing the item know where they can find more materials related to this item in case they found it by searching for a subject, or through another linked entry. 
- This also provides a connection with the physical material and helps individuals to know where it is located. 

##### contributing institution
- Most of our digital collections are owned by the University of Idaho Library, but some of them originate from other institutions or individuals. Some digital collections are combinations of U of I Library materials and materials from other institutions. 
- Citing the contributing Institution notes attribution as well as protects U of I from potential copyright issues. 

##### language
- A three-letter code for the language used in the material. 
- Use the [ISO 639-2 Codes for the Representation of Names and Languages](https://www.loc.gov/standards/iso639-2/php/code_list.php) to identify the correct language code.
- Multiple language codes should be separated by a semi-colon.
- Example value: `eng`, `fre`, `spa`

##### rights
- A copyright statement that consists of a free-text statement and a standardized rights statement. 
- These statements indicate to viewers and researchers if permissions are required to use the material in publication, and how to attribute the item once used. 
- Example copyright value: `Educational use includes non-commercial use of text and images in materials for teaching and research purposes. Digital reproduction rights granted by the University of Idaho Library. For other uses beyond free use, please contact the University of Idaho Library Special Collections and Archives Department.`
- Example public domain value: `Material has passed into public domain. Digital reproduction permission has been granted by University of Idaho Library. For more information, please contact University of Idaho Library Special Collections and Archives Department.`

##### rightsstatement
- This field is a standardized rights statement, designated in the form of a URI. 
- It should be presented as a [creativecommons.org](https://creativecommons.org/) URI or a [rightsstatements.org](https://rightsstatements.org/en/) URI. 
- Example value: `http://rightsstatements.org/vocab/NoC-US/1.0/`

##### original file name
- Refers to either the collection of numbers and letters that designate its location within the Library or the original file name that may have been edited to fit our standards here at the Library. 

------------
