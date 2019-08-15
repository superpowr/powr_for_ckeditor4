# 🎉 Welcome to POWr Weebly Staging for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrweeblystaging',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrweeblystaging', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrweeblystaging/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Weebly Staging CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrweeblystaging/powrweeblystaging.zip)
2. Unzip the downloaded plugin  `powrweeblystaging.zip`  and put the resulting `powrweeblystaging` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrweeblystaging

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrweeblystaging';



## How to create and edit POWr Weebly Staging:

After the POWr Weebly Staging for CKEditor plugin is installed, it's easy to create and update Weebly Staging!

1. Easily add a Weebly Staging within the CKEditor by clicking the `Insert Weebly Staging` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Weebly Staging will then appear within the Editor. Click `Edit Weebly Staging` to open the POWr Editor and create and update your Weebly Staging.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
