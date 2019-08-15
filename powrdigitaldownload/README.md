# 🎉 Welcome to POWr Digital Download for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrdigitaldownload',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrdigitaldownload', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrdigitaldownload/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Digital Download CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrdigitaldownload/powrdigitaldownload.zip)
2. Unzip the downloaded plugin  `powrdigitaldownload.zip`  and put the resulting `powrdigitaldownload` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrdigitaldownload

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrdigitaldownload';



## How to create and edit POWr Digital Download:

After the POWr Digital Download for CKEditor plugin is installed, it's easy to create and update Digital Download!

1. Easily add a Digital Download within the CKEditor by clicking the `Insert Digital Download` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Digital Download will then appear within the Editor. Click `Edit Digital Download` to open the POWr Editor and create and update your Digital Download.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
