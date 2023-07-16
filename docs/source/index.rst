.. image:: docs/images/CoverIlustration.jpg

Welcome to the Auto-Building's documentation!
===================================


This addon is for Blender 3.5+ only!

The system is only using Geometry Node to work but you don't need to have any knowledge in this aspect of Blender to use it.

1.How it works
===================================

The idea is to take a simple low poly mesh and distribute/replace geometry on the faces to create a complex building. Complex, but easier to manipulate and change as everything is handled procedurally by the power of Geometry nodes!

You will have to build the parts of your buildings separetely and put their own respective collection (Windows, Doors, Balcony, Thing, etc)
Then you will need to setup the system to go pick the collection you want to use for this building by matching them to a material in the addon menu or in thgeometry node modifier. Now if you assign the same material to any face of your geometry, the same object you modelled before will spawn in its center.

/* IMAGE SHOWING COLLECTION AND MATERIAL MATCHING */

A lot more things can be done and this documentation will explain all the settings but feel free to open the Sample scene to see what's possible and how it works.



Lumache has its documentation hosted on Read the Docs.Lumache has its documentation hosted on Read the Docs.

**Lumache** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::
 Lumache has its documentation hosted on Read the Docs.
   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
