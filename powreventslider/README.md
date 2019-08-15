# 🎉 Welcome to POWr Event Slider for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powreventslider',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powreventslider', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powreventslider/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Event Slider CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powreventslider/powreventslider.zip)
2. Unzip the downloaded plugin  `powreventslider.zip`  and put the resulting `powreventslider` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powreventslider

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powreventslider';



## How to create and edit POWr Event Slider:

After the POWr Event Slider for CKEditor plugin is installed, it's easy to create and update Event Slider!

1. Easily add a Event Slider within the CKEditor by clicking the `Insert Event Slider` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Event Slider will then appear within the Editor. Click `Edit Event Slider` to open the POWr Editor and create and update your Event Slider.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
