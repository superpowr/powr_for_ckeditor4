# 🎉 Welcome to POWr Staging Dev for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrstagingdev',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrstagingdev', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrstagingdev/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Staging Dev CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrstagingdev/powrstagingdev.zip)
2. Unzip the downloaded plugin  `powrstagingdev.zip`  and put the resulting `powrstagingdev` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrstagingdev

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrstagingdev';



## How to create and edit POWr Staging Dev:

After the POWr Staging Dev for CKEditor plugin is installed, it's easy to create and update Staging Dev!

1. Easily add a Staging Dev within the CKEditor by clicking the `Insert Staging Dev` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Staging Dev will then appear within the Editor. Click `Edit Staging Dev` to open the POWr Editor and create and update your Staging Dev.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
