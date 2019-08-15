# 🎉 Welcome to POWr Resume for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrresume',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrresume', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrresume/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Resume CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrresume/powrresume.zip)
2. Unzip the downloaded plugin  `powrresume.zip`  and put the resulting `powrresume` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrresume

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrresume';



## How to create and edit POWr Resume:

After the POWr Resume for CKEditor plugin is installed, it's easy to create and update Resume!

1. Easily add a Resume within the CKEditor by clicking the `Insert Resume` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Resume will then appear within the Editor. Click `Edit Resume` to open the POWr Editor and create and update your Resume.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
