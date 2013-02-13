= Ant build structure for asciidoc toolchain =

This folder has the following files and structure:
├── README.md - this file
├── build.properties.sample - example build.properties file which points to what to build and how to build it via asciidoc tool chain. File has to be renamed to build.properties before things will work.
├── build.xml - ant build script
└── src - where the document source files are located.
    ├── acronyms.asciidoc - acronyms file.
    ├── <name-of-research-document>.asciidoc - Main source file which will be built by the document tool chain, as such our target.
    ├── bib.asciidoc - bibliography file.
    └── glossary.asciidoc - glossary file.

To make life a little easier, the ant script looks for a global properties file, "doc-build.properties" in your home directory first. This means you can set almost all the properties there instead of the local 'build.properties' file. This leaves only the 'name.project' property to be set on a per document basis.
