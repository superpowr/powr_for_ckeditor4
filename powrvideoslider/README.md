# 🎉 Welcome to POWr Video Slider for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrvideoslider',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrvideoslider', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrvideoslider/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Video Slider CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrvideoslider/powrvideoslider.zip)
2. Unzip the downloaded plugin  `powrvideoslider.zip`  and put the resulting `powrvideoslider` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrvideoslider

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrvideoslider';



## How to create and edit POWr Video Slider:

After the POWr Video Slider for CKEditor plugin is installed, it's easy to create and update Video Slider!

1. Easily add a Video Slider within the CKEditor by clicking the `Insert Video Slider` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Video Slider will then appear within the Editor. Click `Edit Video Slider` to open the POWr Editor and create and update your Video Slider.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
