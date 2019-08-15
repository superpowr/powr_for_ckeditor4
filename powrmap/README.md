# 🎉 Welcome to POWr Map for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrmap',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrmap', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmap/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Map CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmap/powrmap.zip)
2. Unzip the downloaded plugin  `powrmap.zip`  and put the resulting `powrmap` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrmap

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrmap';



## How to create and edit POWr Map:

After the POWr Map for CKEditor plugin is installed, it's easy to create and update Map!

1. Easily add a Map within the CKEditor by clicking the `Insert Map` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Map will then appear within the Editor. Click `Edit Map` to open the POWr Editor and create and update your Map.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
