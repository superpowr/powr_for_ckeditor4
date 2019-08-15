# 🎉 Welcome to POWr RSS Feed for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrrssfeed',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrrssfeed', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrrssfeed/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr RSS Feed CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrrssfeed/powrrssfeed.zip)
2. Unzip the downloaded plugin  `powrrssfeed.zip`  and put the resulting `powrrssfeed` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrrssfeed

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrrssfeed';



## How to create and edit POWr RSS Feed:

After the POWr RSS Feed for CKEditor plugin is installed, it's easy to create and update RSS Feed!

1. Easily add a RSS Feed within the CKEditor by clicking the `Insert RSS Feed` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The RSS Feed will then appear within the Editor. Click `Edit RSS Feed` to open the POWr Editor and create and update your RSS Feed.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
