**NutilWeb**
==============

Nutil quantifies features per atlas-region based on the atlas files from WebAlign and the segmentation files from ilastik. It generates:

1. Reports with quantifications per atlas-region (counts and percentage coverage)
2. Plots showing percentage coverage per atlas-region
3. Images showing the features superimposed on the atlas maps
4. Coordinate files that may be viewed with Meshview

Fill in the form to analyse your data.

.. image:: images/NutilWeb.PNG

Segmentations
-------------

.. note::
   The segmentations must comply with _sXXX naming convention.


* Generate segmentations with the ilastik software. 
* Place these in a folder titled "seg_dir", zip and upload the "seg_dir.zip" to the collab bucket.
* Navigate to this folder for the Segmentation files.
* Colour refers to the colour assigned to the features in the segmentations. For example, red in the example below. 


Atlas files
------------

* Register the section images to the reference atlas using WebAlign.
* Download the atlas files from WebAlign using the "Export overlays" button: this creates a zipped folder containing the relevant atlas files. 


FlatChecker

https://www.nesys.uio.no/FlatChecker/ 



