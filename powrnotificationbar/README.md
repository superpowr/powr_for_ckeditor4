# 🎉 Welcome to POWr Notification Bar for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrnotificationbar',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrnotificationbar', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrnotificationbar/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Notification Bar CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrnotificationbar/powrnotificationbar.zip)
2. Unzip the downloaded plugin  `powrnotificationbar.zip`  and put the resulting `powrnotificationbar` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrnotificationbar

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrnotificationbar';



## How to create and edit POWr Notification Bar:

After the POWr Notification Bar for CKEditor plugin is installed, it's easy to create and update Notification Bar!

1. Easily add a Notification Bar within the CKEditor by clicking the `Insert Notification Bar` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Notification Bar will then appear within the Editor. Click `Edit Notification Bar` to open the POWr Editor and create and update your Notification Bar.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
