# 🎉 Welcome to POWr Photo Filter for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrphotofilter',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrphotofilter', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrphotofilter/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Photo Filter CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrphotofilter/powrphotofilter.zip)
2. Unzip the downloaded plugin  `powrphotofilter.zip`  and put the resulting `powrphotofilter` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrphotofilter

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrphotofilter';



## How to create and edit POWr Photo Filter:

After the POWr Photo Filter for CKEditor plugin is installed, it's easy to create and update Photo Filter!

1. Easily add a Photo Filter within the CKEditor by clicking the `Insert Photo Filter` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Photo Filter will then appear within the Editor. Click `Edit Photo Filter` to open the POWr Editor and create and update your Photo Filter.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
