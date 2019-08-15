# 🎉 Welcome to POWr Button for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrbutton',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrbutton', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrbutton/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Button CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrbutton/powrbutton.zip)
2. Unzip the downloaded plugin  `powrbutton.zip`  and put the resulting `powrbutton` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrbutton

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrbutton';



## How to create and edit POWr Button:

After the POWr Button for CKEditor plugin is installed, it's easy to create and update Button!

1. Easily add a Button within the CKEditor by clicking the `Insert Button` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Button will then appear within the Editor. Click `Edit Button` to open the POWr Editor and create and update your Button.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
