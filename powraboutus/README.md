# 🎉 Welcome to POWr About Us for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powraboutus',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powraboutus', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powraboutus/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr About Us CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powraboutus/powraboutus.zip)
2. Unzip the downloaded plugin  `powraboutus.zip`  and put the resulting `powraboutus` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powraboutus

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powraboutus';



## How to create and edit POWr About Us:

After the POWr About Us for CKEditor plugin is installed, it's easy to create and update About Us!

1. Easily add a About Us within the CKEditor by clicking the `Insert About Us` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The About Us will then appear within the Editor. Click `Edit About Us` to open the POWr Editor and create and update your About Us.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
