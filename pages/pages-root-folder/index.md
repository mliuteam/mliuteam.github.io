---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: logo.png
widget1:
  title: "Prof. Ming Liu"
  url: '/mingliu/'
  image: mliu.jpg
  text: ' Dr. Ming Liu is a "Tengfei" professor at School of Electrical and Information Engineering, and director of the laboratory for Integrated Multiferroic Materials and Devices. '
widget2:
  title: "Research Articles"
  url: '/publications/'
  text: 'The articles of Ph.D student Mingming Zhu and graduate student Shishun Zhao were elected as the cover articles on the Advanced Functional Materials and Advanced Materials. '
  image: amcover2.png
widget3:
  title: "Opportunities"
  url: '/opening/'
  image: teaching.jpg
  text: 'Available positions: we are currently seeking postdoctoral researchers,Ph.D, graduate and undergraduate students in the fields of magnetics, multiferroics, and spintronics. '
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
permalink: /index.html

#callforaction:
 # url: '/about/'
  #text: 
  #style: 
 


#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#

homepage: true
---

<!--<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>-->

<!--<div class="row t30 b20 homepage">
<div class="small-12 columns">
<img src="{{ site.urlimg }}chatu.png"">
</div>
</div>-->