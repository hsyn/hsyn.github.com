---
layout: article
title: Reduce size of a PDF on Mac OS without losing quality
comments: true

image:
  teaser: finder-mac-os.png
---

Are you in a hurry to attach that PDF file to a web form or email and just realised that it exceeds the maximum file size allowed?


I will be showing you how to reduce the file size of your PDF without losing a lot of quality in it's content. You don't need to install any extra software to achieve this. Let's do this.

## ColorSync Utility

Open spotlight and search for ColorSync Utility application. Click on `Filters` tab. You will see around 8 options in that list. One of them is named _Reduce File Size_

Click on dark gray oval icon to the right of that option. You will see a list starting with _Duplicate Filter_


<figure>
  <a href="#"><img src="/images//duplicate_colorsync_filter.png"></a>
  <figcaption>Duplicate File Reduce Filter.</figcaption>
</figure>

Duplicated filter will be added to end of the list.


Double click on the name and rename it to something more meaningful than _Reduce File Size Copy_ I renamed mine to _Reduce File Size (75%)_

Expand filter options by clicking on the triangle icon on the left.

Set these values;

- Image sampling
  - Scale: 75
  - Max: 1024
- Image Compression
  - Quality: Max

<figure>
  <a href="#"><img src="/images//new_filter_values.png"></a>
  <figcaption>New filter values.</figcaption>
</figure>


Now you are ready to use your new filter.

Click on File tab on menu bar and select Open. Keyboard shortcut if you want is CMD + letter O.

Select the PDF file you want and you will see the file opened in ColorSync app.

Click on File menu again and select Export option. Give your file a new name and click on Quartz Filter. You will see your newly created filter in that list. Select that and export the file.

Check the new size of the file and apply the same procedure again if you want to reduce the size even more.

<figure>
  <a href="#"><img src="/images//export_with_filter.png"></a>
  <figcaption>New filter values.</figcaption>
</figure>

Cheers!
