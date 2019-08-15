# 🎉 Welcome to POWr FAQ for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrfaq',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrfaq', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrfaq/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr FAQ CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrfaq/powrfaq.zip)
2. Unzip the downloaded plugin  `powrfaq.zip`  and put the resulting `powrfaq` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrfaq

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrfaq';



## How to create and edit POWr FAQ:

After the POWr FAQ for CKEditor plugin is installed, it's easy to create and update FAQ!

1. Easily add a FAQ within the CKEditor by clicking the `Insert FAQ` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The FAQ will then appear within the Editor. Click `Edit FAQ` to open the POWr Editor and create and update your FAQ.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
