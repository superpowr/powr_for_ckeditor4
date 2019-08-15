# 🎉 Welcome to POWr Menu for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrmenu',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrmenu', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmenu/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Menu CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmenu/powrmenu.zip)
2. Unzip the downloaded plugin  `powrmenu.zip`  and put the resulting `powrmenu` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrmenu

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrmenu';



## How to create and edit POWr Menu:

After the POWr Menu for CKEditor plugin is installed, it's easy to create and update Menu!

1. Easily add a Menu within the CKEditor by clicking the `Insert Menu` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Menu will then appear within the Editor. Click `Edit Menu` to open the POWr Editor and create and update your Menu.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
