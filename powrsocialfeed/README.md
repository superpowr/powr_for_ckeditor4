# 🎉 Welcome to POWr Social Feed for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrsocialfeed',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrsocialfeed', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrsocialfeed/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Social Feed CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrsocialfeed/powrsocialfeed.zip)
2. Unzip the downloaded plugin  `powrsocialfeed.zip`  and put the resulting `powrsocialfeed` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrsocialfeed

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrsocialfeed';



## How to create and edit POWr Social Feed:

After the POWr Social Feed for CKEditor plugin is installed, it's easy to create and update Social Feed!

1. Easily add a Social Feed within the CKEditor by clicking the `Insert Social Feed` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Social Feed will then appear within the Editor. Click `Edit Social Feed` to open the POWr Editor and create and update your Social Feed.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
