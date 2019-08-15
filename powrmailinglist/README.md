# 🎉 Welcome to POWr Mailing List for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrmailinglist',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrmailinglist', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmailinglist/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Mailing List CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmailinglist/powrmailinglist.zip)
2. Unzip the downloaded plugin  `powrmailinglist.zip`  and put the resulting `powrmailinglist` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrmailinglist

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrmailinglist';



## How to create and edit POWr Mailing List:

After the POWr Mailing List for CKEditor plugin is installed, it's easy to create and update Mailing List!

1. Easily add a Mailing List within the CKEditor by clicking the `Insert Mailing List` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Mailing List will then appear within the Editor. Click `Edit Mailing List` to open the POWr Editor and create and update your Mailing List.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
