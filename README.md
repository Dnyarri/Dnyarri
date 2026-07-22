# The Toad's Slimy Mudhole

## where the Toad intercourses Python

Current profile contains various Python programs, mostly related to creating and editing images. Brief list of repositories, and corresponding content description, is given below:

### 2D Image handling

| Repository | Description | External info page |
| :-- | :-- | :-- |
| [PyPNM](https://github.com/Dnyarri/PyPNM "Displaying images and reading and writing PPM and PGM image files in pure Python") | Compact and omnicompatible pure Python module for working with images and [PNM](https://netpbm.sourceforge.net/doc/pnm.html) ([PPM](https://netpbm.sourceforge.net/doc/ppm.html) and [PGM](https://netpbm.sourceforge.net/doc/pgm.html)) image files. Full support for 16 bits per channel bitdepth included without any limitations, special methods, and other dances with tambourine. Initially developed for visualization of nested lists in memory as images, it inevitably acquired capabilities to read and save image data in the form of open PNM image file format. PyPNM is widely used for image data visualization in practically all other programs in this collection. | [🔽More info...](https://dnyarri.github.io/pypnm.html "PyPNM module description and operation manual") |
| [ScaleNx](https://github.com/Dnyarri/PixelArtScaling "Scale2x, Scale3x, Scale2xSFX and Scale3xSFX image rescaling in pure Python") | Scale2x, Scale3x, Scale2xSFX and Scale3xSFX image rescaling algorithms, implemented in pure Python. Started as a simple translation of [Wikipedia article](https://en.wikipedia.org/wiki/Pixel-art_scaling_algorithms) pseudocode, module survived through several optimizations, and evolved into something surprisingly performant for a Python being. | [🔽More info...](https://dnyarri.github.io/scalenx.html "ScaleNx module description and operation manual") |
| [imin](https://github.com/Dnyarri/imin "Barycentric and bilinear image interpolation in pure Python") | Barycentric and bilinear image interpolation (rescaling, rotation, arbitrary deformation), implemented in pure Python. While bilinear interpolation is common for image editing software, barycentric interpolation is rare, and seem to give interesting results, worth further investigations and, probably, practical usage. | [🔽More info...](https://dnyarri.github.io/imin.html "Barycentric and bilinear image interpolation module description and operation manual") |

### 3D Objects and scenes creation

| Repository | Description | External info page |
| :-- | :-- | :-- |
| [img2mesh](https://github.com/Dnyarri/img2mesh "Converting 2D image heightfields into 3D triangle meshes") | My childhood dream - program for converting 2D image height fields into 3D triangle meshes. Extruding logos or line drawings, adding bevels and knockouts via image filters, and so on. Primary export format is POV-Ray POV, however, Wavefront OBJ, stereolithography ASCII STL, and Autodesk ASCII DXF are supported as well. | [🔽More info...](https://dnyarri.github.io/img2mesh.html "img2mesh description and preview") |
| [POV-Ray Mosaic](https://github.com/Dnyarri/POVMosaic "Converting 2D image into 3D objects mosaic") | Program converting PNG or PPM image into POV‑Ray mosaic, consisting of various objects - spheres, cylinders, boxes, prisms, etc. - colored after source image pixels. Irreplaceable for entertaining and getting to people, currently POV‑Ray Mosaic spans all three regular plane partitions for [Euclidean tilings](https://en.wikipedia.org/wiki/List_of_regular_polytopes#Euclidean_tilings), namely 3⁶ (triangular tiling), 4⁴ (square tiling), and 6³ (hexagonal tiling. Ah, my favourite). | [🔽More info...](https://dnyarri.github.io/povzaika.html "POV-Ray Mosaic description and preview") |
| [POV-Ray Thread](https://github.com/Dnyarri/POVThread "Converting 2D image into colored textile simulation") | Program converting PNG or PPM image into 3D structure, simulating some textile/threads. Currently colored plain weave and cross stitch export are provided. | [🔽More info...](https://dnyarri.github.io/povthread.html "POV-Ray Thread description and preview") |

### Miscellanea

| Repository | Description | External info page |
| :-- | :-- | :-- |
| [The Toad's Batchroom](https://github.com/Dnyarri/batchfiles "PNG to ICO conversion, automating ffmpeg, optivorbis, LibreOffice etc.") | The Toad's Batchroom repository includes various Python scripts for automating ffmpeg, optivorbis, LibreOffice, folder NTFS LZX compression etc. Recent addition: PNG Sanctifier - a PNG to multisize ICO converter which, unlike other software, does not pretend to be smarter than you - it does not change your PNGs but simply inserts them into icon framework "as is". | [🔽More info...](https://dnyarri.github.io/batch.html "Batch scripts list and description") |

> [!NOTE]
> You are currently at main The Toad's Slimy Mudhole location. There is also a [Gitflic mirror](https://gitflic.ru/user/dnyarri "Gitflic mirror of The Toad's Slimy Mudhole Python software collection"), created for "just in case" reasons. You know, *cases happen*.

More detailed and illustrated descriptions of Python freeware above are given at [The Toad's Slimy Mudhole website](https://dnyarri.github.io).
