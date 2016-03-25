# Infor Mingle or Sharepoint 2013+ - Upload a file by using the REST API and jQuery


 The following project uses the SharePoint 2013 REST API and jQuery AJAX requests to upload a file to the Documents library and to change properties of the list item that represents the file. The context for this solution is that's running on the server. Similar to SharePoint-hosted add-in that uploads files to the add-in web. 
 
 Also can be used with Infor Mingle with Sharepoint 2013
 
##Requirements:
 ===========================
 * Sharepoint 2013+
 * Write permissions to the Documents library for the user running the code. If you're developing a SharePoint Add-in, you can specify  * Write add-in permissions at the List scope
 * Browser support for the FileReader API (HTML5)
 * A reference to the jQuery library in your page
   * '''javascript
   <script src="https://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.9.1.min.js" type="text/javascript"></script>
'''
	
	
##Page Markup and Usage:
=============================
'''<input id="getFile" type="file"/><br />
<input id="displayFileName" type="text" value="Enter a unique filename name" /><br />
<input id="addFileButton" type="button" value="Upload" onclick="uploadFile()"/>
'''
