# 🎉 Welcome to POWr Reviews for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrreviews',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrreviews', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrreviews/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Reviews CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrreviews/powrreviews.zip)
2. Unzip the downloaded plugin  `powrreviews.zip`  and put the resulting `powrreviews` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrreviews

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrreviews';



## How to create and edit POWr Reviews:

After the POWr Reviews for CKEditor plugin is installed, it's easy to create and update Reviews!

1. Easily add a Reviews within the CKEditor by clicking the `Insert Reviews` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Reviews will then appear within the Editor. Click `Edit Reviews` to open the POWr Editor and create and update your Reviews.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
