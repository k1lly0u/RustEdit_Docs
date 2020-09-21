This repository is setup for documentation for RustEdit that is displayed in the about/help menu in editor.


New topics can be created by making a new Markdown document, when done add the topic name and the link to the raw file to the manifest.


The editor downloads the manifest when the Help menu is opened and populates the topic list. When a user clicks a topic it downloads that document and parses the contents to Unity UI. 

It has (almost) complete Markdown support including images, code blocks (no syntax highlighting), tables and hyperlinks


It's open for community contribution, if you have anything you want to add create a PR
