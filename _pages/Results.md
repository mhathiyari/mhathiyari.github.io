---
layout: archive
title: "SideProject"
permalink: /SideProject/
author_profile: true
---
### Results
Multiple images is captured of the same scene in sucession by the user. The device used to caputre the images was a handheld mobile phone camera. About 30 images like seen in the collage bellow, we used as input to the alogorithm
![collage of crowded place](/images/collage_of_images.JPG)
<table style="border: none; border-collapse: collapse;" border="0" cellspacing="0" cellpadding="0" width="100%" align="center">
 <tr>
   <td>
    <p align="center">
    <img width=100% src="/images/collage_of_images.JPG" alt="Formation attacked by cannonballs"/>
    </p>
    </td>
     <td>
    <p align="center">
![collage of crowded place](/images/collage_of_images.JPG)
    </p>
    </td>
  </tr>
</table>
{% include base_path %}
{% for post in site.pages %}
{% include archive-single.html %}
{% endfor %}
