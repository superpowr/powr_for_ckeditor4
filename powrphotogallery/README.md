# 🎉 Welcome to POWr Photo Gallery for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrphotogallery',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrphotogallery', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrphotogallery/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Photo Gallery CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrphotogallery/powrphotogallery.zip)
2. Unzip the downloaded plugin  `powrphotogallery.zip`  and put the resulting `powrphotogallery` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrphotogallery

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrphotogallery';



## How to create and edit POWr Photo Gallery:

After the POWr Photo Gallery for CKEditor plugin is installed, it's easy to create and update Photo Gallery!

1. Easily add a Photo Gallery within the CKEditor by clicking the `Insert Photo Gallery` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Photo Gallery will then appear within the Editor. Click `Edit Photo Gallery` to open the POWr Editor and create and update your Photo Gallery.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
