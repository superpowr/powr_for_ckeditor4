# 🎉 Welcome to POWr Survey for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrsurvey',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrsurvey', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrsurvey/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Survey CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrsurvey/powrsurvey.zip)
2. Unzip the downloaded plugin  `powrsurvey.zip`  and put the resulting `powrsurvey` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrsurvey

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrsurvey';



## How to create and edit POWr Survey:

After the POWr Survey for CKEditor plugin is installed, it's easy to create and update Survey!

1. Easily add a Survey within the CKEditor by clicking the `Insert Survey` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Survey will then appear within the Editor. Click `Edit Survey` to open the POWr Editor and create and update your Survey.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
