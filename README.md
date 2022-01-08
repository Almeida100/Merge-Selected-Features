# Merge-Selected-Features
QGis already has a menu tool for this purpose, but this plugin performs the operation much faster, especially when the number of selected features is in the order of hundreds or thousands. 
This plugin allows you to merge selected features in a polygon vector layer. It produces a new polygon vector layer, named "Calculated", with the merged features that the user has previously selected. Non selected features are maintained unaltered. 
Merging only takes place when there are two or more selected features. When there are any selected features (or only one feature selected) in the polygon vector layer, the produced "Calculated" layer is exactly like the original.
To run the plugin, go to Processing Toolbox -> Merge Selected Features -> Merge Selected Features Vers 0.1
