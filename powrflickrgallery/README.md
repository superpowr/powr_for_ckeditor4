# 🎉 Welcome to POWr Flickr Gallery for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrflickrgallery',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrflickrgallery', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrflickrgallery/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Flickr Gallery CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrflickrgallery/powrflickrgallery.zip)
2. Unzip the downloaded plugin  `powrflickrgallery.zip`  and put the resulting `powrflickrgallery` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrflickrgallery

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrflickrgallery';



## How to create and edit POWr Flickr Gallery:

After the POWr Flickr Gallery for CKEditor plugin is installed, it's easy to create and update Flickr Gallery!

1. Easily add a Flickr Gallery within the CKEditor by clicking the `Insert Flickr Gallery` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Flickr Gallery will then appear within the Editor. Click `Edit Flickr Gallery` to open the POWr Editor and create and update your Flickr Gallery.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
