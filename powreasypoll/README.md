# 🎉 Welcome to POWr Easy Poll for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powreasypoll',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powreasypoll', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powreasypoll/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Easy Poll CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powreasypoll/powreasypoll.zip)
2. Unzip the downloaded plugin  `powreasypoll.zip`  and put the resulting `powreasypoll` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powreasypoll

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powreasypoll';



## How to create and edit POWr Easy Poll:

After the POWr Easy Poll for CKEditor plugin is installed, it's easy to create and update Easy Poll!

1. Easily add a Easy Poll within the CKEditor by clicking the `Insert Easy Poll` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Easy Poll will then appear within the Editor. Click `Edit Easy Poll` to open the POWr Editor and create and update your Easy Poll.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
