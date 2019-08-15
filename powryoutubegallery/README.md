# 🎉 Welcome to POWr YouTube Gallery for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powryoutubegallery',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powryoutubegallery', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powryoutubegallery/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr YouTube Gallery CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powryoutubegallery/powryoutubegallery.zip)
2. Unzip the downloaded plugin  `powryoutubegallery.zip`  and put the resulting `powryoutubegallery` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powryoutubegallery

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powryoutubegallery';



## How to create and edit POWr YouTube Gallery:

After the POWr YouTube Gallery for CKEditor plugin is installed, it's easy to create and update YouTube Gallery!

1. Easily add a YouTube Gallery within the CKEditor by clicking the `Insert YouTube Gallery` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The YouTube Gallery will then appear within the Editor. Click `Edit YouTube Gallery` to open the POWr Editor and create and update your YouTube Gallery.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
