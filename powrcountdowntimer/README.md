# 🎉 Welcome to POWr Countdown Timer for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrcountdowntimer',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrcountdowntimer', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrcountdowntimer/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Countdown Timer CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrcountdowntimer/powrcountdowntimer.zip)
2. Unzip the downloaded plugin  `powrcountdowntimer.zip`  and put the resulting `powrcountdowntimer` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrcountdowntimer

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrcountdowntimer';



## How to create and edit POWr Countdown Timer:

After the POWr Countdown Timer for CKEditor plugin is installed, it's easy to create and update Countdown Timer!

1. Easily add a Countdown Timer within the CKEditor by clicking the `Insert Countdown Timer` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Countdown Timer will then appear within the Editor. Click `Edit Countdown Timer` to open the POWr Editor and create and update your Countdown Timer.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
