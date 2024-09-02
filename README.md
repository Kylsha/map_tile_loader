# MapTileLoader

QGIS plugin which download and stitch TMS imagery.
This simple tool allows QGIS users to download stitched chunks of tile map services provided in plugin.

![](https://pereverzev.info/maptileloader/process.gif)

### Quickstart guide

1. Open QGIS, add some tile map service layer to current project and launch a MapTileLoader plugin.
Select a `Source` from combobox, then set the download zoom level. 

>[!NOTE]
>The more zoom is, the more detailed picture will be in output and the more time it takes to download.

2. Press `  +  ` button to draw a bounding box of downloading area. This box can be also saved and loaded (buttons `Save frame` and `Load frame`) as custom files for further downloads of another sources. 

3. Point the save path. It is recommended to be an empty folder in order to keep your data safe.

4. Check a tick `Add image on load` if downloaded image should be added to project right after it is ready.

5. Finally press `Download` button to start downloading process.

