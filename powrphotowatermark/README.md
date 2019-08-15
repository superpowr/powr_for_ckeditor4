# 🎉 Welcome to POWr Photo Watermark for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrphotowatermark',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrphotowatermark', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrphotowatermark/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Photo Watermark CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrphotowatermark/powrphotowatermark.zip)
2. Unzip the downloaded plugin  `powrphotowatermark.zip`  and put the resulting `powrphotowatermark` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrphotowatermark

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrphotowatermark';



## How to create and edit POWr Photo Watermark:

After the POWr Photo Watermark for CKEditor plugin is installed, it's easy to create and update Photo Watermark!

1. Easily add a Photo Watermark within the CKEditor by clicking the `Insert Photo Watermark` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Photo Watermark will then appear within the Editor. Click `Edit Photo Watermark` to open the POWr Editor and create and update your Photo Watermark.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
