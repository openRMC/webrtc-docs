This area hosts research notes, these are little sippets of text which represents some research on a topic within the area of WebRTC. 

== Text Formatting of the Notes ==
Each research note is written in [Asciidoc](http://www.methods.co.nz/asciidoc/). The reason for using AsciiDoc formatting is to follow the process of write once, use everywhere mentality. AsciiDoc can be easily translated in to many different formats including HTML, LATEX, PDF, EPUB, man page. This process encourages authors to write content in distinct blocks which could then be re-used in documentation, articles, web pages, man pages at a later stage, without the need to constantly cut and paste text from different locations, and potential keeps all written items on the project in synchorisation.

== WebRTC Research Document ==
The root document within this set is in the folder webrtc-research-document. Within this folder there are the following files

├── README.md - Explaining the contents of the folder.
├── build.properties.sample - example build.properties file which points to what to build and how to build it via the asciidoc tool chain.iThis File has to be renamed to build.properties before things will work.
├── build.xml - ant build script.
└── src - where the document source files are located.
    ├── images - A directory to host any images related to the document.
    ├── <name-of-research-document>.asciidoc - Main source file which will be built by the document tool chain, as such our target.
    ├── resources - A directory to host .pdf, .doc, .odt or other formatted text documents which are used within the main target.

=== Build a PDF of the research document ===
In order to build a full pdf or html version of the webrtc-research-document, asciidoc along with the asciidoc toolchain program must be installed on your system. 

    $ ant pdf
    $ snt html

== Deployed Document ==
The latest released version of this document is hosted on the openRMC site at

== Discussion Forum ==
The discussion forum for this document is hosted at

https://groups.google.com/forum/?fromgroups#!forum/openrmc-discuss 

== Licensing and Contributions ==
This work is licensed as specified in the file LICENSE.txt. 

To contribute to this work on openRMC, please see page [Contributing](http://www.openrmc.org/contributing-to-openrmc). 

The openRMC is a i[meritocratic, consensus-based community project](http://www.openrmc.org/governance-model) which allows anyone to contribute and gain additional responsibilities.
