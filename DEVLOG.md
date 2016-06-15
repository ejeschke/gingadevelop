## Friday, June 10, 2016
* Worked on making the unit test for the ColorDist module Python 3 compatable. Including Python 2 print statements was causing the build to fail when using Python 3. Instead of using Python 3 compatable print statements, I chose to just remove the print statements all together.
* Wrote the `creating image files` notebook.

## Saturday, June 11, 2016
* Started rewriting and cleaning up the python notebook for `pyfits vs cfitio`. Discovered a test case (`iris.fits`) that taking too long to load with `pyfits`.

## Sunday, June 12, 2016
* Started rewriting and cleaning up the `python fadvise` notebook. Ran numerous tests to try to figure out any improvement contributed by `fadvise`, but could not find any.

## Monday, June 13, 2016
* Fleshed out observations, conclusions, and comments in notebooks so far. 
* Found out `iris.fits` was an improper image file, revised conclusions with the new result; ended up with no significant time difference, reversing previous statements about `iris.fits` being a problem case.

## Tuesday, June 14, 2016
* Wrote the `access speeds` notebook.
* Revised `ColorDist` testing module to have a test for each distrubtion.