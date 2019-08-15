# 🎉 Welcome to POWr Popup for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrpopup',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrpopup', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrpopup/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Popup CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrpopup/powrpopup.zip)
2. Unzip the downloaded plugin  `powrpopup.zip`  and put the resulting `powrpopup` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrpopup

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrpopup';



## How to create and edit POWr Popup:

After the POWr Popup for CKEditor plugin is installed, it's easy to create and update Popup!

1. Easily add a Popup within the CKEditor by clicking the `Insert Popup` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Popup will then appear within the Editor. Click `Edit Popup` to open the POWr Editor and create and update your Popup.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
