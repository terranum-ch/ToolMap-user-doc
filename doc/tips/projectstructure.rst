Project Structure
=======================

This section explains what a good data structure for ToolMap projects and their data might look like.

.. image:: img/folder_structure.svg


#. Contains the ToolMap project as a directory. Good practice dictates that no other documents should be placed in this directory. Having all the ToolMap projects in the same sub-folder allows to bypass the limitation imposed by MariaDB (see: :ref:`database_limitation`).
#. This directory can contain support data, such as raster or shapefiles
#. This folder can be configured as an export directory for shapefiles
#. A folder for backups
#. Other data, for example the data model or PDF documents


