# 🎉 Welcome to POWr Holiday Countdown for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrholidaycountdown',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrholidaycountdown', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrholidaycountdown/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Holiday Countdown CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrholidaycountdown/powrholidaycountdown.zip)
2. Unzip the downloaded plugin  `powrholidaycountdown.zip`  and put the resulting `powrholidaycountdown` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrholidaycountdown

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrholidaycountdown';



## How to create and edit POWr Holiday Countdown:

After the POWr Holiday Countdown for CKEditor plugin is installed, it's easy to create and update Holiday Countdown!

1. Easily add a Holiday Countdown within the CKEditor by clicking the `Insert Holiday Countdown` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Holiday Countdown will then appear within the Editor. Click `Edit Holiday Countdown` to open the POWr Editor and create and update your Holiday Countdown.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
