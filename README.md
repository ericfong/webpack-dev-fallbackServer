webpack-dev-server that support fallbackBase file serving

For Cordova / Phonegap

    webpackDevServe(middleware, null, 7777);
    webpackDevServe(middleware, "platforms/ios/www", 7779);
    webpackDevServe(middleware, "platforms/android/assets/www", 7778);
