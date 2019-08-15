# 🎉 Welcome to POWr Wix UI Local for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrwixuilocal',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrwixuilocal', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrwixuilocal/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Wix UI Local CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrwixuilocal/powrwixuilocal.zip)
2. Unzip the downloaded plugin  `powrwixuilocal.zip`  and put the resulting `powrwixuilocal` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrwixuilocal

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrwixuilocal';



## How to create and edit POWr Wix UI Local:

After the POWr Wix UI Local for CKEditor plugin is installed, it's easy to create and update Wix UI Local!

1. Easily add a Wix UI Local within the CKEditor by clicking the `Insert Wix UI Local` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Wix UI Local will then appear within the Editor. Click `Edit Wix UI Local` to open the POWr Editor and create and update your Wix UI Local.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
