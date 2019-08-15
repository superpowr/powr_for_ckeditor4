# 🎉 Welcome to POWr Banner Slider for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrbannerslider',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrbannerslider', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrbannerslider/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Banner Slider CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrbannerslider/powrbannerslider.zip)
2. Unzip the downloaded plugin  `powrbannerslider.zip`  and put the resulting `powrbannerslider` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrbannerslider

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrbannerslider';



## How to create and edit POWr Banner Slider:

After the POWr Banner Slider for CKEditor plugin is installed, it's easy to create and update Banner Slider!

1. Easily add a Banner Slider within the CKEditor by clicking the `Insert Banner Slider` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Banner Slider will then appear within the Editor. Click `Edit Banner Slider` to open the POWr Editor and create and update your Banner Slider.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
