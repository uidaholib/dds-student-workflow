---
title: Scanning Procedures
nav: Scanning
---

-------------------

{% capture text %}**Before you scan**:
Make sure that hands are clean and dry when handling materials for scanning or any type of digitization work; all materials should be handled with care, and cotton gloves worn when instructed by a supervisor. These items cannot be replaced or easily repaired if destroyed or damaged.{% endcapture %}
{% include alert.html text=text color="danger" %}

1. Why?
2. File naming
3. Scanning images

## Why do we scan?

Digitizing materials by scanning them with a flatbed, large format, or feed scanner is sometimes the safest and most effective means of preserving the information in an item and allowing others to access it. Scanning items at a high resolution allows the item to be used in different ways without needing to make any manipulations to the actual item. This is why we aim for a minimum 600 dpi image; it provides a scalable image that can be used for large or small reprints while maintaining the original details of the item.

## Scanning Images

1. Turn on scanner at station. Open EpsonScan scanning software. 

2. Place item to be scanned along the left side of the scanning bed (the glass plate), leaving a slight border between item and edge. 

3. Position the Color Separation Guide so that the “saturated” bar is beside the item being scanned (along the bottom edge of the item is fine). Be sure to leave a ⅛-inch gap between the guide and the item.

4. Close the scanner lid and press “Preview” in EpsonScan. Once the preview scan is finished, use the cursor to draw the selection window around the item and as much of the Color Separation Guide as is needed to color balance the item. There should not be a lot of space between the item and the edges of the selection window; see below:

    Insert example images
5. Scanned images should be at least 6,000 pixels on the long edge. This measurement is located at the bottom left of the preview panel. The color filter should be set to ‘none’:
    Insert example image

6. Once your settings are correct, press “Scan”. The “File Save Settings” window will pop up and you will need to:

- Click “Other” and then “Browse to select the file you want your scanned images to be saved to. This should be the tif folder you already created.
- Set up the File Name prefix. This should reflect the collection, box number, item number, and any other identifying characteristics like page numbers. See [File Naming] for complete details. The Start Number should be at 001 if you’re starting a new project, or set to the next sequential number if you’re in the middle of a project. 
    Example image
- In the Image Format section, the file type should be set to TIFF (*.tif).

7. Press “OK” and the scan will begin. 

## GitHub Pages 

One amazingly useful GitHub feature is [GitHub Pages](https://guides.github.com/features/pages/).
It provides free static web hosting from any repository.
Gh-pages is intended to host relatively simple sites for your GitHub portfolio, project, or documentation.
Because it is free and a valuable transferable skill, this is a great option for teaching and learning.

Many organizations are using GitHub to collaboratively create and publish public workshop websites. 
For example: 

- [Programming Historian](http://programminghistorian.org/)
- [Software Carpentry](https://software-carpentry.org/), [Data Carpentry](http://www.datacarpentry.org/), [Library Carpentry](https://librarycarpentry.org/)
- this site!

{% capture text %}Note:
There are *soft* limits and guidelines for gh-pages usage: sites should be < 1GB, use < 100GB bandwidth per month, and make < 10 builds per hour.
If your site exceeds these quotas, GitHub will send you a notice asking you to modify the repository.
All content must follow the [community guidelines](https://help.github.com/articles/github-community-guidelines/), e.g. no violence, obscene sex, or illegal stuff.{% endcapture %}
{% include alert.html text=text color="danger" %}
