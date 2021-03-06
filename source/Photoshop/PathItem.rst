.. _PathItem:

================================================
PathItem
================================================


Description
-----------

A path or drawing object, such as the outline of a shape or a straight or curved line, which contains sub paths that comprise its geometry.




Properties
^^^^^^^^^^

+-----------------------------------------------------+------------------------------------------+
| :ref:`kind<PathItem.kind>`                          | The type of path.                        |
+-----------------------------------------------------+------------------------------------------+
| :ref:`name<PathItem.name>`                          | The name of the path item.               |
+-----------------------------------------------------+------------------------------------------+
| :ref:`parent<PathItem.parent>` readonly             | The object's container.                  |
+-----------------------------------------------------+------------------------------------------+
| :ref:`subPathItems<PathItem.subPathItems>` readonly | The sub path objects for this path item. |
+-----------------------------------------------------+------------------------------------------+
| :ref:`typename<PathItem.typename>` readonly         | The class name of the object.            |
+-----------------------------------------------------+------------------------------------------+







Methods
^^^^^^^

+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`add<PathItem.add>`                           | Adds an element.                                                                |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`deselect<PathItem.deselect>`                 | Unselects the selection, no path items are selected.                            |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`duplicate<PathItem.duplicate>`               | Duplicate this object.                                                          |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`duplicate<PathItem.duplicate>`               | Duplicates this path item.                                                      |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`fillPath<PathItem.fillPath>`                 | Fills the area enclosed by the path.                                            |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`makeClippingPath<PathItem.makeClippingPath>` | Makes this path item the clipping path for this document.                       |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`makeSelection<PathItem.makeSelection>`       | Makes a selection object, whose border is the path, from this path item object. |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`remove<PathItem.remove>`                     | Deletes this object.                                                            |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`removeAll<PathItem.removeAll>`               | Deletes all elements.                                                           |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`select<PathItem.select>`                     | Makes this path item the active or selected path item.                          |
+----------------------------------------------------+---------------------------------------------------------------------------------+
| :ref:`strokePath<PathItem.strokePath>`             | Strokes the path.                                                               |
+----------------------------------------------------+---------------------------------------------------------------------------------+






.. container:: hide

   .. toctree::
      :hidden:
      :maxdepth: 1

      PathItem/parent.rst
      PathItem/typename.rst
      PathItem/name.rst
      PathItem/subPathItems.rst
      PathItem/kind.rst
      
      

      PathItem/add.rst
      PathItem/duplicate.rst
      PathItem/remove.rst
      PathItem/removeAll.rst
      PathItem/duplicate.rst
      PathItem/makeSelection.rst
      PathItem/fillPath.rst
      PathItem/strokePath.rst
      PathItem/makeClippingPath.rst
      PathItem/select.rst
      PathItem/deselect.rst
      
      
      
      