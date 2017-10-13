Spatial Data management
=======================

The data management is made through the :guilabel:`Data` menu, it contains the following elements:

  * :guilabel:`Link data...` (:kbd:`Ctrl+O`): reference a support layer which will be displayed in your project
  * :guilabel:`Unlink data...` (:kbd:`Ctrl+W`): unlink a layer
  * :guilabel:`Add Web data...` (:kbd:`Ctrl+Alt+W`): Add web data such as Google / Bing images
  * :guilabel:`Import data`: import data into one of your construction theme

.. _link-data:

Link data
-----------------

The :menuselection:`Data --> Link Data...` option allows loading some support themes for the vectorization of the construction layers. Those support themes can be vector data (\*.shp) or raster data (\*.tif, \*.JPG and Esri's binary GRID).

In the opposite of the construction layers, the support themes are not stocked in the project but only referenced.

Rotation
^^^^^^^^^^^^^^^^^^^^^

Some of your files may have rotation information, which is not yet supported by ToolMap. In that case you will see the following message:


.. image:: img/window-rotationwarning.png


#. rotation information
#. display option

This message will pop up every time you make an action regarding the layer (including trivial actions like zoom or pan), so be sure to convert your images into non-rotated rasters (see :ref:`rotation_warning`). If the rotation is insignificant, you may prefer to simply ignore the message by checking the option **Hide warnings for this layer**. This option prevent the appearance of the message for the current session, but it will pop again the next time you launch your project.

Unlink data
-----------------
The :menuselection:`Data --> Unlink data` option allows removing specified support layers from the project. Those layers aren't deleted but simply removed from the project.

.. image:: img/unlink-data.png

Add Web Data
-----------------

The :menuselection:`Data --> Add Web data` option allows adding web data as support layers. The list of supported web data are listed in the picture bellow.

.. image:: img/add-web-data.png

Import data
-----------------

The :menuselection:`Data --> Import data...` option allows you to import some existing information into your construction layers. You can only import lines or points geometries. The process is made in 3 different steps.

.. _datamanagement#Step1:

Step1
^^^^^^^^^^^^^^^^^^^^^

.. image:: img/window-importdata1.png

#. the File type option allows two types of data, choose the one you want to import
#. Go to the next step of the import or cancel the operation

Step2
^^^^^^^^^^^^^^^^^^^^^

If you choose to add a shapefile the following step comes ahead

.. image:: img/window-importdata2.png

#. Directory path of the shapefile
#. data information of the shapefile
#. allow to go back to :ref:`datamanagement#Step1` or to continue to Step 3

If you choose to add a CSV file the following step comes ahead

.. image:: img/window-importdata4.png

#. Directory path of the CSV file
#. Information on the CSV file
#. allow to go back or to continue to step 2.2

Step2.2
"""""""""""""""""""""""

The CSV files are composed of columns of data separated with commas, you will have to choose wich column you want to assign to the X and Y coordinates

.. image:: img/window-importdata5.png

#. List of the columns which can be assigned as X or Y coordinates
#. allows to go back or to continue to :ref:`datamanagement#Step3`

.. _datamanagement#Step3:

Step3
^^^^^^^^^^^^^^^^^^^^^

.. image:: img/window-importdata3.png

#. List of layers within the data will be imported (with the shapefile import the choice is restricted to the geometrical type of the data)
#. import the data or cancel the operation

Table of contents options
---------------------------

.. image:: img/window-tocoption.png

#. |img1| Activate the display of the layer |img2| Deactivate the display of the layer
#. Edition mode activated: the layer is underlined

contextual menu
^^^^^^^^^^^^^^^^^^^^^

The contextual menus are opened by right-clicking on a layer of the table of contents. They vary according to the selected layer.

Construction

.. image:: img/pdm-toc.png

Support

.. image:: img/pdm-toc2.png

* Name of the layer
* Edit this layer (construction layers only)
* Remove layer (support themes only)
* Move the selected layer in the table of contents

.. image:: img/pdm-tocmove.png

* Display management of the vertex (line and polygon layers type only)
* Symbology management. This option can also be activated by double-clicking on the layer. (see :ref:`symbology`)


.. |img1| image:: img/button-marked.png
.. |img2| image:: img/button-unmarked.png

