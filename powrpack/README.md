# 🎉 Welcome to POWr Pack for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrpack',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrpack', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrpack/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Pack CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrpack/powrpack.zip)
2. Unzip the downloaded plugin  `powrpack.zip`  and put the resulting `powrpack` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrpack

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrpack';



## How to create and edit POWr Pack:

After the POWr Pack for CKEditor plugin is installed, it's easy to create and update Pack!

1. Easily add a Pack within the CKEditor by clicking the `Insert Pack` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Pack will then appear within the Editor. Click `Edit Pack` to open the POWr Editor and create and update your Pack.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
