### 1.3.0

#### NEW FEATURES
* Conversion functions `linescan_to_stack()` and `stack_to_linescan()` useful for FCS data.


### 1.2.0

#### MINOR IMPROVEMENTS
* Improved the description of the package in DESCRIPTION, vignette and README.
* Added a hex sticker.
* Limited support for tiled images thanks to new author Kent Johnson.
* `write_tif()` is now slightly (<10%) faster.
* `write_tif()` messages are now more informative.


### 1.1.0 

#### NEW FEATURES
* `count_imgs()` counts the number of images in a TIFF file without reading the images themselves.
* `read_tags()` reads the tags from TIFF images without reading the images themselves.

#### MINOR IMPROVEMENTS
* Now includes citation information.
* C code is more readable.
* `display()` is more flexible, accepting 3 and 4-dimensional arrays, just displaying the first frame from the first channel.


### 1.0.0

#### PEER REVIEW
* The package is now peer reviewed by ROpenSci.


### 0.3.0

#### MINOR IMPROVEMENTS
* Improve README and vignette with more tangible and fun example.

#### BUG FIXES
* Fix windows `libtiff` issues (thanks to Jeroen Ooms).
* Found some ImageJ-written TIFFs that weren't being read correctly and fixed that.
* Fix `protection stack overflow` error for TIFFs with many images.


### 0.2.0
* First CRAN release.

#### MINOR IMPROVEMENTS
* Include handy shortcuts for 2- and 3-dimensional arrays.
* Messasges to inform the user about what kind of image is being read/written.


### `ijtiff` 0.1.0

* First github release.
