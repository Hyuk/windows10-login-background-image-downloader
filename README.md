# Windows10 Login Background Downloader

```
robocopy "%UserProfile%\AppData\Local\Packages\Microsoft.Windows.ContentDeliveryManager_cw5n1h2txyewy\LocalState\Assets" "%UserProfile%\Desktop\Bing Wallpaper" /MIN:102400 /M
rename "%UserProfile%\Desktop\Bing Wallpaper\*" "*.jpg"
```