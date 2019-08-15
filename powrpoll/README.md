# 🎉 Welcome to POWr Poll for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrpoll',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrpoll', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrpoll/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Poll CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrpoll/powrpoll.zip)
2. Unzip the downloaded plugin  `powrpoll.zip`  and put the resulting `powrpoll` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrpoll

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrpoll';



## How to create and edit POWr Poll:

After the POWr Poll for CKEditor plugin is installed, it's easy to create and update Poll!

1. Easily add a Poll within the CKEditor by clicking the `Insert Poll` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Poll will then appear within the Editor. Click `Edit Poll` to open the POWr Editor and create and update your Poll.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
