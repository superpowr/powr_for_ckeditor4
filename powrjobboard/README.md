# 🎉 Welcome to POWr Job Board for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrjobboard',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrjobboard', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrjobboard/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Job Board CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrjobboard/powrjobboard.zip)
2. Unzip the downloaded plugin  `powrjobboard.zip`  and put the resulting `powrjobboard` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrjobboard

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrjobboard';



## How to create and edit POWr Job Board:

After the POWr Job Board for CKEditor plugin is installed, it's easy to create and update Job Board!

1. Easily add a Job Board within the CKEditor by clicking the `Insert Job Board` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Job Board will then appear within the Editor. Click `Edit Job Board` to open the POWr Editor and create and update your Job Board.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
