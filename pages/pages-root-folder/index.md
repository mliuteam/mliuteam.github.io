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
  text: ' <h6>Vice Dean of Graduate School at XJTU</h6>西安交通大学研究生院副院长
   <h6>Thousand Talent Program </h6> 中组部"青年千人计划"
  <h6>Hundred-Talent Program</h6> 陕西省"百人计划"
  <h6>Member of Xi&apos;an Municipal Committee of CPPCC</h6>西安市政协委员'
widget3:
  title: "Research Articles"
  url: '/publications/'
  text: '<p>The articles of Ph.D student Mingmin Zhu and graduate student Shishun Zhao were elected as the cover articles on the Advanced Functional Materials and Advanced Materials, which are modulation of spin dynamics via voltage control of spin-lattice coupling in multiferroics and quantitative ...</p>'
  image: amcover2.png
widget2:
  title: "Research"
  url: '/research/'
  image: spinronics800.png
  text: '<p>The Integrated Ferroic Laboratory designs and studies the dynamical behavior of magnetic, ferroelectric, and magneto-electric materials and micro/nano-structures. We are interested in new concepts for electric-field control of the electrical, magnetic, optical, and structural properties via strain, charge, ions...</p>'
widget4:
  title: "Opportunities"
  url: '/opportunities/'
  image: teaching.jpg
  text: '<p>Available Positions: We are always looking for top graduate students to join us for master and Ph.D. degrees. Applicants should have a B.S. or Masters in Physics, Electrical Engineering, Material Science, Chemicals, Mechanical Engineering or related field.The candidates should have strong motivation in exploring the unknown ...</p>'
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

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<!--<div class="row t30 b20 homepage">
<div class="small-12 columns">
<img src="{{ site.urlimg }}chatu.png"">
</div>
</div>-->