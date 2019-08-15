# 🎉 Welcome to POWr Donation Button for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrdonationbutton',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrdonationbutton', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrdonationbutton/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Donation Button CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrdonationbutton/powrdonationbutton.zip)
2. Unzip the downloaded plugin  `powrdonationbutton.zip`  and put the resulting `powrdonationbutton` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrdonationbutton

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrdonationbutton';



## How to create and edit POWr Donation Button:

After the POWr Donation Button for CKEditor plugin is installed, it's easy to create and update Donation Button!

1. Easily add a Donation Button within the CKEditor by clicking the `Insert Donation Button` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Donation Button will then appear within the Editor. Click `Edit Donation Button` to open the POWr Editor and create and update your Donation Button.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
