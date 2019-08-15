# 🎉 Welcome to POWr Browser Notification for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrbrowsernotification',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrbrowsernotification', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrbrowsernotification/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Browser Notification CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrbrowsernotification/powrbrowsernotification.zip)
2. Unzip the downloaded plugin  `powrbrowsernotification.zip`  and put the resulting `powrbrowsernotification` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrbrowsernotification

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrbrowsernotification';



## How to create and edit POWr Browser Notification:

After the POWr Browser Notification for CKEditor plugin is installed, it's easy to create and update Browser Notification!

1. Easily add a Browser Notification within the CKEditor by clicking the `Insert Browser Notification` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Browser Notification will then appear within the Editor. Click `Edit Browser Notification` to open the POWr Editor and create and update your Browser Notification.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
