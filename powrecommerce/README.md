# 🎉 Welcome to POWr Ecommerce for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrecommerce',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrecommerce', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrecommerce/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Ecommerce CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrecommerce/powrecommerce.zip)
2. Unzip the downloaded plugin  `powrecommerce.zip`  and put the resulting `powrecommerce` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrecommerce

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrecommerce';



## How to create and edit POWr Ecommerce:

After the POWr Ecommerce for CKEditor plugin is installed, it's easy to create and update Ecommerce!

1. Easily add a Ecommerce within the CKEditor by clicking the `Insert Ecommerce` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Ecommerce will then appear within the Editor. Click `Edit Ecommerce` to open the POWr Editor and create and update your Ecommerce.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
