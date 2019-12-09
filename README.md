# Warning

This is my personal playground-fork of the original [DocFX assistant](https://github.com/tintoy/docfx-assistant) project, to play with.  
Goal is to support DocFx's xrefmap.yml properly and is not supposed to be compatbile with the original project.  
This project is in HACK / alpha state. Use at your own risk (or better do not ;) ).

# DocFX assistant

An extension for VS Code that provides tools for authoring content using Microsoft DocFX.

![DocFX Assistant in action](docs/images/DocFX-in-action.gif)

## Usage

When you're editing Markdown or YAML and the workspace contains a DocFX project, type `@` or press `ctrl+space` to invoke the completion provider and bring up a pick-list of available topic UIDs.

It will also underline inline-style and (`@xxx`) and XRef-style (`<xref:xxx>`) links for UIDs into hyperlinks pointing to the documents where they are defined. If a link is not underlined, then it points to a non-existent topic.

To refresh the list of available topics, use the "DocFX: Refresh topic UIDs" command.
