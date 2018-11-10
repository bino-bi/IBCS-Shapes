# IBCS-Shapes
Library of IBCS Shapes for draw.io

About
-----
IBCS-Shapes is a Library of IBCS® related shapes for [draw.io](https://www.draw.io).  
[draw.io](https://www.draw.io) is an online diagramming web site that delivers the source in this project.

A [draw.io repository](https://github.com/jgraph/drawio) can be found on github. 
draw.io uses the [mxGraph library](https://github.com/jgraph/mxgraph) as the base of the stack, with the [GraphEditor example](https://github.com/jgraph/mxgraph/tree/master/javascript/examples/grapheditor) from mxGraph as the base of the application part.

License
-------
International Business Communication Standards (IBCS®) is under [CC BY-SA license](https://www.ibcs.com/de/creative-commons-faq/).
The IBCS Association is thus the current owner of the copyright in the IBCS® Standards.

Running draw.io
---------------
One way to run draw.io is to fork this project, [publish the master branch to GitHub pages](https://help.github.com/categories/github-pages-basics/) and the [pages sites](https://jgraph.github.io/drawio/src/main/webapp/index.html) will have the full editor functionality (sans the integrations).

Another way is to use the Dockerfile in [/etc/docker](etc/docker/) or to download [draw.io Desktop](https://get.draw.io).

The full packaged .war of the client and servlets is built when the project is tagged and available on the [releases page](https://github.com/jgraph/draw.io/releases).


Using Library
-------------
Loading example diagram
The file [Example-1.1](https://www.dropbox.com/s/1nvfk36cyzwdznj/Template-1.1?dl=0) is an example diagram which you can load 
directly into draw.io. It is using the IBCS-Shapes library. 
![example](https://user-images.githubusercontent.com/327346/48302973-762b9e00-e504-11e8-942a-1cb9c02f691e.png)

Loading library
Load the library [IBCS-1.1](https://www.dropbox.com/s/xr0eje8louzzy92/IBCS-1.1.xml?dl=0)
by *Edit -> Open Library...*


![loadlib](https://user-images.githubusercontent.com/327346/48303018-4cbf4200-e505-11e8-862b-6bc00d32d6c7.png)


### Data Point

To change the value of a column/ bar *right click on the bar -> Edit Data...*

![editdata](https://user-images.githubusercontent.com/327346/48303113-7cbb1500-e506-11e8-8888-a2696850e5c8.png)

![editdata2](https://user-images.githubusercontent.com/327346/48303116-88a6d700-e506-11e8-867b-64ff508edf04.png)

### Title

To change the title (Department, KPI, Measure, Scenario) *right click on the bar -> Edit Data...*

![edittitle](https://user-images.githubusercontent.com/327346/48303156-066ae280-e507-11e8-9e78-6231241ff32a.png)


### Message

To change the report message *right click on the bar -> Edit Data...*

![editmessage](https://user-images.githubusercontent.com/327346/48303163-200c2a00-e507-11e8-83de-dde6b3056178.png)


Supported Browsers
------------------
draw.io supports IE 11, Chrome 32+, Firefox 38+, Safari 9.1.x, 10.1.x and 11.0.x, Opera 20+, Native Android browser 5.1.x+, the default browser in the current and previous major iOS versions (e.g. 11.2.x and 10.3.x) and Edge 23+.
