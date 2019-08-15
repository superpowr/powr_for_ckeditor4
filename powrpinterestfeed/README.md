# 🎉 Welcome to POWr Pinterest Feed for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrpinterestfeed',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrpinterestfeed', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrpinterestfeed/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Pinterest Feed CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrpinterestfeed/powrpinterestfeed.zip)
2. Unzip the downloaded plugin  `powrpinterestfeed.zip`  and put the resulting `powrpinterestfeed` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrpinterestfeed

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrpinterestfeed';



## How to create and edit POWr Pinterest Feed:

After the POWr Pinterest Feed for CKEditor plugin is installed, it's easy to create and update Pinterest Feed!

1. Easily add a Pinterest Feed within the CKEditor by clicking the `Insert Pinterest Feed` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Pinterest Feed will then appear within the Editor. Click `Edit Pinterest Feed` to open the POWr Editor and create and update your Pinterest Feed.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
