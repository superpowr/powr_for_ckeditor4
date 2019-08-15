# 🎉 Welcome to POWr Contact Form for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrcontactform',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrcontactform', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrcontactform/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Contact Form CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrcontactform/powrcontactform.zip)
2. Unzip the downloaded plugin  `powrcontactform.zip`  and put the resulting `powrcontactform` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrcontactform

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrcontactform';



## How to create and edit POWr Contact Form:

After the POWr Contact Form for CKEditor plugin is installed, it's easy to create and update Contact Form!

1. Easily add a Contact Form within the CKEditor by clicking the `Insert Contact Form` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Contact Form will then appear within the Editor. Click `Edit Contact Form` to open the POWr Editor and create and update your Contact Form.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
