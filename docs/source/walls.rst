Walls
===========

.. image:: images/MaterialAssignment.gif

Assign  materials on the faces of your object to control how the system will create your buiding.


Empty Wall A and B Material
---------------------

Your building can have 2 kind of base wall materials. To control wich one to use, simply apply the corresponding ID material, **ID_EmptyWallA** or **ID_EmptyWallB**

.. image:: images/EmptyMaterial.gif

Wall A to G
------------
The walls setting allow you to spawn 7 kind of object collection on your buildings. Represented by the letters A to G.
For instance, to use the collection you pick for wall A, simply assign the **ID_WallA** materials

.. image:: images/CollectionAssignment.gif

For each letter, you can find the the same set of options.

Select the collection you want to assign on the Wall A materials.


**Use Boolean** : If this is unchecked, face where the ID_Wall material is assigned will disappear and a random object from the collection will replace it.

.. image:: images/UseBoolean.gif

**Use wall B material**: By default, the material you setup in the Empty Wall A will be used. This setting will make it use the Empty Wall B instead.

.. image:: images/UseBMaterial.gif

**Seed**:Change this setting to offer another random distribution of your objects.

.. image:: images/WallSeed.gif

**Density**: Reduce this number to randomly remove some of the objects.

.. image:: images/WallDensity.gif

**Offset**: Move your objects in or out of the face.

.. image:: images/WallOffset.gif

**Deform**: Deform the objects to fit the original face shape.

.. image:: images/WallDeform.gif

**Inset**: Option only available if Deform is activated. This option allow to insset the original face before applying the deform. MAking your object smaller.

.. image:: images/WallInset.gif

.. autosummary::
   :toctree: generated

   lumache
