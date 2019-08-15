# 🎉 Welcome to POWr Plan Comparison for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrplancomparison',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrplancomparison', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrplancomparison/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Plan Comparison CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrplancomparison/powrplancomparison.zip)
2. Unzip the downloaded plugin  `powrplancomparison.zip`  and put the resulting `powrplancomparison` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrplancomparison

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrplancomparison';



## How to create and edit POWr Plan Comparison:

After the POWr Plan Comparison for CKEditor plugin is installed, it's easy to create and update Plan Comparison!

1. Easily add a Plan Comparison within the CKEditor by clicking the `Insert Plan Comparison` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Plan Comparison will then appear within the Editor. Click `Edit Plan Comparison` to open the POWr Editor and create and update your Plan Comparison.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
