# 🎉 Welcome to POWr Social Media Icons for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrsocialmediaicons',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrsocialmediaicons', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrsocialmediaicons/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Social Media Icons CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrsocialmediaicons/powrsocialmediaicons.zip)
2. Unzip the downloaded plugin  `powrsocialmediaicons.zip`  and put the resulting `powrsocialmediaicons` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrsocialmediaicons

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrsocialmediaicons';



## How to create and edit POWr Social Media Icons:

After the POWr Social Media Icons for CKEditor plugin is installed, it's easy to create and update Social Media Icons!

1. Easily add a Social Media Icons within the CKEditor by clicking the `Insert Social Media Icons` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Social Media Icons will then appear within the Editor. Click `Edit Social Media Icons` to open the POWr Editor and create and update your Social Media Icons.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
