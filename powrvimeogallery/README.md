# 🎉 Welcome to POWr Vimeo Gallery for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrvimeogallery',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrvimeogallery', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrvimeogallery/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Vimeo Gallery CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrvimeogallery/powrvimeogallery.zip)
2. Unzip the downloaded plugin  `powrvimeogallery.zip`  and put the resulting `powrvimeogallery` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrvimeogallery

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrvimeogallery';



## How to create and edit POWr Vimeo Gallery:

After the POWr Vimeo Gallery for CKEditor plugin is installed, it's easy to create and update Vimeo Gallery!

1. Easily add a Vimeo Gallery within the CKEditor by clicking the `Insert Vimeo Gallery` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Vimeo Gallery will then appear within the Editor. Click `Edit Vimeo Gallery` to open the POWr Editor and create and update your Vimeo Gallery.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
