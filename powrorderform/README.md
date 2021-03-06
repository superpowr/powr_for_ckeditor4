# 🎉 Welcome to POWr Order Form for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrorderform',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrorderform', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrorderform/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Order Form CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrorderform/powrorderform.zip)
2. Unzip the downloaded plugin  `powrorderform.zip`  and put the resulting `powrorderform` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrorderform

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrorderform';



## How to create and edit POWr Order Form:

After the POWr Order Form for CKEditor plugin is installed, it's easy to create and update Order Form!

1. Easily add a Order Form within the CKEditor by clicking the `Insert Order Form` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Order Form will then appear within the Editor. Click `Edit Order Form` to open the POWr Editor and create and update your Order Form.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
