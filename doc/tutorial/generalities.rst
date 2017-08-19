.. _tuto-generalities:

Generalities
==================

What is ToolMap?
---------------------

ToolMap is a cost-free, open-source software dedicated for digitizing data and producing complex multi-layer GIS projects.

It was developped in response to the need to create projects with:

  * A faultless and accurate topological structure.
  * A correct and homogenized semantic attribution.

How does it work?
---------------------

ToolMap perform its duty based on two basic and undissociable principles:

:The data model: describing the nature and spatial relationships between the possible different features.
:The digitizing process: allowing only two types of geometries, lines and points to represent all two-dimensional "real-world" objects. No polygon layer exists in ToolMap; they are built from the combination of lines delinaeting surfaces. Digitizing all lines, line feature (strictly speaking) and borders of polygons within one single layer yields the following advantages:

    * No redundancy in the digitzing process: geometric shapes referring to multiple object types are digitized and stored only once.
    * Perfect match between geometric shapes occurring in different thematic GIS layers: all objects are extracted from the same construction layers.


.. image:: img/test_tuto.png

In the next part, we will see where are the data we used for this tutorial.