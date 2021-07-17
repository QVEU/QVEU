---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: Aerial.png

widget2:
    title: "About The QVEU"
    url: 'http://qveu.github.io/QVEU/info/'
    image: PV.png
    text: 'The <em>QVEU</em> is an experimental and computational virology laboratory in the Laboratory of Viral Diseases at NIH-NIAID in Bethesda, MD.'

widget3:
  title: "Lab Members"
  url: 'https://github.com/QVEU/labmembers/'
  image: CVB.png
  text: 'Meet the Lab.'

widget3:
    title: "Publications"
    image: EV71.png
    url: 'https://scholar.google.com/citations?hl=en&user=FDehpokAAAAJ&view_op=list_works&sortby=pubdate'
    text: "See what's new from the QVEU."

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
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
