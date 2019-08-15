# 🎉 Welcome to POWr Event Gallery for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powreventgallery',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powreventgallery', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powreventgallery/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Event Gallery CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powreventgallery/powreventgallery.zip)
2. Unzip the downloaded plugin  `powreventgallery.zip`  and put the resulting `powreventgallery` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powreventgallery

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powreventgallery';



## How to create and edit POWr Event Gallery:

After the POWr Event Gallery for CKEditor plugin is installed, it's easy to create and update Event Gallery!

1. Easily add a Event Gallery within the CKEditor by clicking the `Insert Event Gallery` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Event Gallery will then appear within the Editor. Click `Edit Event Gallery` to open the POWr Editor and create and update your Event Gallery.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
