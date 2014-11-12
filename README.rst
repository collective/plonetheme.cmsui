PLONETHEME.CMSUI: Isolated CMSUI for clean theming experience
=============================================================

Idea is to provide an option for those that don't want to incorperate plones widgets, css, and UI into
their theme but still retain a "inplace" editing experience. You can use this lightweight theme package
as a base for your custom plone theme. Only minimal css is required to incorporate the toolbar in your
public theme which will only appear when users are logged in.


TODO
====

- get plonemin bundle branch into core
- handle any add/edit object forms
- fix toolbar css
- remove barcelenota code
- fix overlap of menus
- clean up ploneui detection. get this into core
- width of tinymce to match theme.html
- show sharing content styles between front and back end themes.
- include search in toolbar (should be in core)
- notifications in view mode
- some kind of top level nav in edit mode or home button? Also close button to make like psuedo overlay.
- perhaps remove bootstrap to make it a cleaner base theme
- experiment with using iframe for toolbar to reduce JS/CSS interference from random themes.

