# 🎉 Welcome to POWr Instagram Feed for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrinstagramfeed',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrinstagramfeed', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrinstagramfeed/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Instagram Feed CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrinstagramfeed/powrinstagramfeed.zip)
2. Unzip the downloaded plugin  `powrinstagramfeed.zip`  and put the resulting `powrinstagramfeed` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrinstagramfeed

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrinstagramfeed';



## How to create and edit POWr Instagram Feed:

After the POWr Instagram Feed for CKEditor plugin is installed, it's easy to create and update Instagram Feed!

1. Easily add a Instagram Feed within the CKEditor by clicking the `Insert Instagram Feed` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Instagram Feed will then appear within the Editor. Click `Edit Instagram Feed` to open the POWr Editor and create and update your Instagram Feed.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
