# 🎉 Welcome to POWr Image Resizer for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrimageresizer',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrimageresizer', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrimageresizer/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Image Resizer CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrimageresizer/powrimageresizer.zip)
2. Unzip the downloaded plugin  `powrimageresizer.zip`  and put the resulting `powrimageresizer` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrimageresizer

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrimageresizer';



## How to create and edit POWr Image Resizer:

After the POWr Image Resizer for CKEditor plugin is installed, it's easy to create and update Image Resizer!

1. Easily add a Image Resizer within the CKEditor by clicking the `Insert Image Resizer` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Image Resizer will then appear within the Editor. Click `Edit Image Resizer` to open the POWr Editor and create and update your Image Resizer.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
