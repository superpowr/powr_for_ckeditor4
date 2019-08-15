# 🎉 Welcome to POWr Local Dev for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrlocaldev',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrlocaldev', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrlocaldev/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Local Dev CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrlocaldev/powrlocaldev.zip)
2. Unzip the downloaded plugin  `powrlocaldev.zip`  and put the resulting `powrlocaldev` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrlocaldev

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrlocaldev';



## How to create and edit POWr Local Dev:

After the POWr Local Dev for CKEditor plugin is installed, it's easy to create and update Local Dev!

1. Easily add a Local Dev within the CKEditor by clicking the `Insert Local Dev` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Local Dev will then appear within the Editor. Click `Edit Local Dev` to open the POWr Editor and create and update your Local Dev.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
