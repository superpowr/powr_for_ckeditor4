# 🎉 Welcome to POWr File Embed for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrfileembed',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrfileembed', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrfileembed/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr File Embed CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrfileembed/powrfileembed.zip)
2. Unzip the downloaded plugin  `powrfileembed.zip`  and put the resulting `powrfileembed` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrfileembed

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrfileembed';



## How to create and edit POWr File Embed:

After the POWr File Embed for CKEditor plugin is installed, it's easy to create and update File Embed!

1. Easily add a File Embed within the CKEditor by clicking the `Insert File Embed` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The File Embed will then appear within the Editor. Click `Edit File Embed` to open the POWr Editor and create and update your File Embed.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
