HsCharts
========

A chart drawing module for Haskell, using the Gloss drawing package.

Features
--------
* Axis with fixed or 'automatic' range.
* Linear and Logarithmic axis scale.
* Grids
* Chart types:
  - Line chart
  - Area chart
  - Scatter plot
  - Bubble chart
  - Bar chart
  - Box plot
  - Polar coordinate plotting

See the file `demo/Main.hs` for a usage example of each type of chart in the library.
![Chart examples](HsChartsDemo.png)

Requirements
------------
Gloss >= 1.2
http://hackage.haskell.org/package/gloss

Installation
------------
1. Download HsCharts-1.0.tar.gz
2. Unpack the tarball
3. Change the directory to the unpacked tarball directory, or `source/` if you're using the repository.
4. Run the command `cabal install`

Demo
----
To build and run the demo application, perform the following steps:

1. Go to the `demo/` directory.
2. Build and install the demo: `cabal install`
3. Start the demo using `HsChartsDemo`
 
License
-------
HsCharts is licensed under BSD3, see `LICENSE` for the complete license.

Credits
-------
Pier Janssen, Maciej Wichrowski
