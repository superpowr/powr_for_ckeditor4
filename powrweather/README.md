# 🎉 Welcome to POWr Weather for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrweather',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrweather', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrweather/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Weather CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrweather/powrweather.zip)
2. Unzip the downloaded plugin  `powrweather.zip`  and put the resulting `powrweather` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrweather

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrweather';



## How to create and edit POWr Weather:

After the POWr Weather for CKEditor plugin is installed, it's easy to create and update Weather!

1. Easily add a Weather within the CKEditor by clicking the `Insert Weather` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Weather will then appear within the Editor. Click `Edit Weather` to open the POWr Editor and create and update your Weather.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
