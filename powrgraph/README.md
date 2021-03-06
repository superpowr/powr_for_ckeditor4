# 🎉 Welcome to POWr Graph for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrgraph',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrgraph', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrgraph/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Graph CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrgraph/powrgraph.zip)
2. Unzip the downloaded plugin  `powrgraph.zip`  and put the resulting `powrgraph` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrgraph

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrgraph';



## How to create and edit POWr Graph:

After the POWr Graph for CKEditor plugin is installed, it's easy to create and update Graph!

1. Easily add a Graph within the CKEditor by clicking the `Insert Graph` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Graph will then appear within the Editor. Click `Edit Graph` to open the POWr Editor and create and update your Graph.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
