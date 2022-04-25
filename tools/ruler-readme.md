# Ruler
gLabels is missing a ruler at least in version 3.99.
I did a feature-request for that: https://github.com/jimevins/glabels-qt/issues/141

Until this is implemented, my tiny ruler might help.

## How to...
1. create a new image object on your label inside the labeleditor
2. search for the downloaded ruler_25cm.svg as image-source
3. go to position/size of the image-object
4. enable the "keep ratio" option
5. click reset size-button

Now, the image should be at original size of 25cm length. You can place it anywhere you need to measure. It helps putting object quickly to a certain position or relative to other objects.

-> This workflow could be improoved by e.g. drag&drop a file, keep ratio as default and import images in original size. This is reported as issue/request: https://github.com/jimevins/glabels-qt/issues/153
