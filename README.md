# glues2


******************************************
glues2: OpenGL Utility Library for OpenGL ES 2.0
******************************************


Summary
-------

A subset of glu functions for use in OpenGL ES 2.0 environments.
This was modified from iGLU 1.0.0 which was for the iphone, 
back when the iphone was gles1.0.
This is supposed to work for all platforms that support Open GL ES 2.0,  with limited funcionality.
It is an implementation of the `OpenGL Utility Library`__ (GLU).

__ http://www.opengl.org/documentation/specs/

older specs:
.. _iGLU: http://code.google.com/p/iphone-glu/
.. _iPhone OS: http://developer.apple.com/iphone/


License
-------
glues2 is based on iGLU.
iGLU is based on the GLU source included with Mesa_ 7.2, which in turn
derives from the `SGI OpenGL Sample Implementation`__.  All code
derived from SGI's source is licensed under the `SGI Free Software
License B`__ version 2.0. All other code is licensed under the `MIT
license`__.

.. _Mesa: http://mesa3d.sourceforge.net/
__ http://oss.sgi.com/projects/ogl-sample/
__ http://oss.sgi.com/projects/FreeB/
__ http://www.opensource.org/licenses/mit-license.php


Compiling
---------

it should later compile into libglues2

To use, invclude "glues2.h"

Comparison with Standard GLU
----------------------------

glues2 does not include GLU features that depend on OpenGL functionality
missing in `OpenGL ES 2.0`__.

Available features:

* a couple of Matrix manipulation
* Polygon tessellation

Missing features:

* Mipmapping
* Quadrics
* NURBS

For more information on these features, see the `GLU 1.3
specification`__.

__ http://www.khronos.org/opengles/1_X/
__ http://opengl.org/documentation/specs/glu/glu1_3.pdf
