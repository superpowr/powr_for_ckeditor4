# 🎉 Welcome to POWr Video Gallery for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrvideogallery',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrvideogallery', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrvideogallery/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Video Gallery CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrvideogallery/powrvideogallery.zip)
2. Unzip the downloaded plugin  `powrvideogallery.zip`  and put the resulting `powrvideogallery` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrvideogallery

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrvideogallery';



## How to create and edit POWr Video Gallery:

After the POWr Video Gallery for CKEditor plugin is installed, it's easy to create and update Video Gallery!

1. Easily add a Video Gallery within the CKEditor by clicking the `Insert Video Gallery` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Video Gallery will then appear within the Editor. Click `Edit Video Gallery` to open the POWr Editor and create and update your Video Gallery.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
