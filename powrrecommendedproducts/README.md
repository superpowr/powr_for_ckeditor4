# 🎉 Welcome to POWr Recommended Products for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrrecommendedproducts',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrrecommendedproducts', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrrecommendedproducts/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Recommended Products CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrrecommendedproducts/powrrecommendedproducts.zip)
2. Unzip the downloaded plugin  `powrrecommendedproducts.zip`  and put the resulting `powrrecommendedproducts` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrrecommendedproducts

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrrecommendedproducts';



## How to create and edit POWr Recommended Products:

After the POWr Recommended Products for CKEditor plugin is installed, it's easy to create and update Recommended Products!

1. Easily add a Recommended Products within the CKEditor by clicking the `Insert Recommended Products` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Recommended Products will then appear within the Editor. Click `Edit Recommended Products` to open the POWr Editor and create and update your Recommended Products.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
