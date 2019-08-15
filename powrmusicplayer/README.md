# 🎉 Welcome to POWr Music Player for CKEditor 🎉

## How to install:

### Option 1: Add plugin from content delivery network (CDN):
HTML

    <textarea name="editor1" id="editor1" rows="10" cols="80"></textarea>

JavaScript:

    CKEDITOR.replace('editor1',{
      extraPlugins: 'powrmusicplayer',
      height: '800px',
    });
    CKEDITOR.plugins.addExternal('powrmusicplayer', "https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmusicplayer/", 'plugin.js');

### Option 2: Add plugin from local installation on your server:
1.  [Download POWr Music Player CKEditor Plugin](https://cdn.jsdelivr.net/gh/superpowr/powr_for_ckeditor4/powrmusicplayer/powrmusicplayer.zip)
2. Unzip the downloaded plugin  `powrmusicplayer.zip`  and put the resulting `powrmusicplayer` folder into the  `plugins`  folder of your CKEditor installation. Example:

	    http://example.com/ckeditor/plugins/powrmusicplayer

3.  Enable the plugin by using the  [`extraPlugins`](https://ckeditor.com/docs/ckeditor4/latest/api/CKEDITOR_config.html#cfg-extraPlugins)  configuration setting. Example:

	    config.extraPlugins =  'powrmusicplayer';



## How to create and edit POWr Music Player:

After the POWr Music Player for CKEditor plugin is installed, it's easy to create and update Music Player!

1. Easily add a Music Player within the CKEditor by clicking the `Insert Music Player` Icon. Insert more POWr Apps by clicking the `+ POWr` menu.

2. The Music Player will then appear within the Editor. Click `Edit Music Player` to open the POWr Editor and create and update your Music Player.

## Need help?
[Visit our help center](https://www.powr.io/knowledge-base) and get answers!
