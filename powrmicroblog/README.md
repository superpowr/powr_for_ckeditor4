# 🎉 Welcome to POWr Microblog for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrmicroblog',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrmicroblog', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmicroblog/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Microblog CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmicroblog/powrmicroblog.zip)
2. Unzip the downloaded plugin  `powrmicroblog.zip`  and put the resulting `powrmicroblog` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrmicroblog

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrmicroblog';



## How to create and edit POWr Microblog:

After the POWr Microblog for CKEditor plugin is installed, it's easy to create and update Microblog!

1. Easily add a Microblog within the CKEditor by clicking the `Insert Microblog` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Microblog will then appear within the Editor. Click `Edit Microblog` to open the POWr Editor and create and update your Microblog.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
