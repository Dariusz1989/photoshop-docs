ArtLayer.applyCustomFilter {#ArtLayer.applyCustomFilter}
==========================

> void **applyCustomFilter** (int **characteristics**, int **scale**,
> int **offset**)

Parameters
----------

  --------------------- ----------------------------------------------------------------
  **characteristics**   The custom filter characteristics. This is an array of 25 values
                        that corresponds to a left-to-right, top-to- bottom traversal of
                        the array presented in the Custom dialog in the user interface
                        (Filter \> Other \> Custom).

  **scale**             The value by which to divide the sum of the brightness values of
                        the pixels included in the calculation.

  **offset**            The value to be added to the result of the scale calculation.
  --------------------- ----------------------------------------------------------------

Description
-----------

Applies the custom filter.