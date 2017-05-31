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
  title: "Prof. Zhongqiang Hu"
  url: '/zhongqianghu/'
  text: 'Dr. Zhongqiang Hu is a professor of Electrical Engineering
Electronic Materials Research Laboratory, Key Laboratory of the Ministry of Education & International Center for Dielectric Research'
  image: hzqhead.jpg
widget3:
  title: "Opportunities"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: teaching.jpg
  text: '<em>Available postdoc positions</em> 
  <p>We are currently seeking postdoctoral researchers in the fields of magnetics, multiferroics, and spintronics. </p>'
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


callforaction:
  #url: /info
  text: About the Integrated Ferroic Materials and Devices Research Group ›
  style: main color
permalink: /index.html

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#

homepage: true
---
<div class="row text-center" style="background: #fdb515;">
<h2>About laboratory</h2>
</div>

<!--<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>-->
