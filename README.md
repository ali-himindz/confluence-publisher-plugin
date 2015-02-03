# confluence-publisher-plugin
Jenkins Plugin to publish artifacts to Atlassian Confluence
This plugin allows you to publish build artifacts into a Confluence wiki page. Currently limited to uploading an artifact as an attachment to a page id.
To use it to embed in data into confluence wiki page:
1. Create a macro with the name "jenkins-between", set the Processing to "Unrendered"
2. In the macro body put tags pre /pre
3. In the Jenkins set the "Start Marker Token" to "pre" and "End Marker Token" as "/pre"
