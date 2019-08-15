# 🎉 Welcome to POWr Image Slider for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrimageslider',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrimageslider', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrimageslider/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Image Slider CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrimageslider/powrimageslider.zip)
2. Unzip the downloaded plugin  `powrimageslider.zip`  and put the resulting `powrimageslider` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrimageslider

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrimageslider';



## How to create and edit POWr Image Slider:

After the POWr Image Slider for CKEditor plugin is installed, it's easy to create and update Image Slider!

1. Easily add a Image Slider within the CKEditor by clicking the `Insert Image Slider` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Image Slider will then appear within the Editor. Click `Edit Image Slider` to open the POWr Editor and create and update your Image Slider.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
