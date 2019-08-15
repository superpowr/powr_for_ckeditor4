# 🎉 Welcome to POWr List for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrlist',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrlist', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrlist/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr List CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrlist/powrlist.zip)
2. Unzip the downloaded plugin  `powrlist.zip`  and put the resulting `powrlist` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrlist

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrlist';



## How to create and edit POWr List:

After the POWr List for CKEditor plugin is installed, it's easy to create and update List!

1. Easily add a List within the CKEditor by clicking the `Insert List` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The List will then appear within the Editor. Click `Edit List` to open the POWr Editor and create and update your List.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
