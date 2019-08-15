# 🎉 Welcome to POWr Wix Dev for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrwixdev',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrwixdev', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrwixdev/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Wix Dev CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrwixdev/powrwixdev.zip)
2. Unzip the downloaded plugin  `powrwixdev.zip`  and put the resulting `powrwixdev` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrwixdev

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrwixdev';



## How to create and edit POWr Wix Dev:

After the POWr Wix Dev for CKEditor plugin is installed, it's easy to create and update Wix Dev!

1. Easily add a Wix Dev within the CKEditor by clicking the `Insert Wix Dev` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Wix Dev will then appear within the Editor. Click `Edit Wix Dev` to open the POWr Editor and create and update your Wix Dev.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
