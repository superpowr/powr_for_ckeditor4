# 🎉 Welcome to POWr Photo Editor for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrphotoeditor',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrphotoeditor', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrphotoeditor/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Photo Editor CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrphotoeditor/powrphotoeditor.zip)
2. Unzip the downloaded plugin  `powrphotoeditor.zip`  and put the resulting `powrphotoeditor` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrphotoeditor

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrphotoeditor';



## How to create and edit POWr Photo Editor:

After the POWr Photo Editor for CKEditor plugin is installed, it's easy to create and update Photo Editor!

1. Easily add a Photo Editor within the CKEditor by clicking the `Insert Photo Editor` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Photo Editor will then appear within the Editor. Click `Edit Photo Editor` to open the POWr Editor and create and update your Photo Editor.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
