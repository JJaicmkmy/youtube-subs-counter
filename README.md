# YouTube-Subs-Counter
This app can add a widget to your desktop, so you can see your live subscriber count at any time.

![](https://cdn.jichi.io/2017-03-15-屏幕截图-2017-03-15-00.41.07.png)


## Configure
Go to `index.html`, edit https://akshatmittal.com/youtube-realtime/embed/#!/UC-lHJZR3Gqxm24_Vd_AJ5Yw with your channel ID.

then

```
npm install
npm start
```

You should see your live count on desktop now. If it is not in the right position, you should edit `x` and `y` in `index.js`.

To build the package, run

```
electron-packager /path/to/counter YouTube-Counter --mac --x64 --electron-version=1.6.2 --out=/path/to/output
```
Make sure to change the platform and version to the actual circumstance.

In theory, this should work in all platforms, however, I've used some APIs that only works with Mac, so you may have some problem to run in on Windows and Linux.
