# 🎉 Welcome to POWr Facebook Feed for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrfacebookfeed',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrfacebookfeed', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrfacebookfeed/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Facebook Feed CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrfacebookfeed/powrfacebookfeed.zip)
2. Unzip the downloaded plugin  `powrfacebookfeed.zip`  and put the resulting `powrfacebookfeed` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrfacebookfeed

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrfacebookfeed';



## How to create and edit POWr Facebook Feed:

After the POWr Facebook Feed for CKEditor plugin is installed, it's easy to create and update Facebook Feed!

1. Easily add a Facebook Feed within the CKEditor by clicking the `Insert Facebook Feed` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Facebook Feed will then appear within the Editor. Click `Edit Facebook Feed` to open the POWr Editor and create and update your Facebook Feed.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
