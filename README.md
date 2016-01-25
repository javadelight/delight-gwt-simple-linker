# delight-gwt-simple-linker

A simple linker for using GWT on the server side.

This project is based on the file [ServerSingleScriptLinker.java](https://github.com/thatcher/env-js/blob/master/htmlparser/gwt2/src/com/envjs/gwt/linker/ServerSingleScriptLinker.java) from the project [env-js](https://github.com/thatcher/env-js/).

## Usage

Add the project as maven dependency to your project, or copy over the SimpleLinker.java file into your project.

Then, in your module defintion file (.gwt.xml), add the following lines

    <define-linker name="simple" class="delight.gwt.simplelinker.SimpleLinker" />
    <add-linker name="simple" />
    

 
