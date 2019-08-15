# 🎉 Welcome to POWr Scroll To Top for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrscrolltotop',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrscrolltotop', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrscrolltotop/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Scroll To Top CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrscrolltotop/powrscrolltotop.zip)
2. Unzip the downloaded plugin  `powrscrolltotop.zip`  and put the resulting `powrscrolltotop` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrscrolltotop

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrscrolltotop';



## How to create and edit POWr Scroll To Top:

After the POWr Scroll To Top for CKEditor plugin is installed, it's easy to create and update Scroll To Top!

1. Easily add a Scroll To Top within the CKEditor by clicking the `Insert Scroll To Top` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Scroll To Top will then appear within the Editor. Click `Edit Scroll To Top` to open the POWr Editor and create and update your Scroll To Top.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
