JavaFX-AlienRallye
==================


This article describes how to parse the content of a SVG path element and create a set of JavaFX <code>PathElement</code>s which are added to a <code>javafx.scene.shape.Path</code>. The idea behind this is that the JavaFX Path can be used to create a <code>PathTransition</code>. I used the Apache Batik parser to split the SVG path element and wrote my own <code>PathHandler</code> to create the <code>PathElement</code>s.
Further informations and the documentation to this project can be found here [JavaFX-AlienRallye][]

## Contributing
[Pull requests][] are welcome.

## License
The JavaFX - Alien Rallye application is released under version 2.0 of the [Apache License][].


[Apache License]: http://www.apache.org/licenses/LICENSE-2.0
[Pull requests]: http://help.github.com/send-pull-requests
[JavaFX-AlienRallye]: http://www.hameister.org/JavaFX_SVGPath.html
