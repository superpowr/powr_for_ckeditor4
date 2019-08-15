# 🎉 Welcome to POWr Weebly Demo for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrweeblydemo',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrweeblydemo', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrweeblydemo/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Weebly Demo CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrweeblydemo/powrweeblydemo.zip)
2. Unzip the downloaded plugin  `powrweeblydemo.zip`  and put the resulting `powrweeblydemo` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrweeblydemo

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrweeblydemo';



## How to create and edit POWr Weebly Demo:

After the POWr Weebly Demo for CKEditor plugin is installed, it's easy to create and update Weebly Demo!

1. Easily add a Weebly Demo within the CKEditor by clicking the `Insert Weebly Demo` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Weebly Demo will then appear within the Editor. Click `Edit Weebly Demo` to open the POWr Editor and create and update your Weebly Demo.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
