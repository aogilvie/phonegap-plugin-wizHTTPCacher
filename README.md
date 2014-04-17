phonegap-plugin-wizHTTPCacher
=============================

Ultimate disk cache mechanism for HTTP caching. Cordova plugin for Android and iOS.

This plugin wraps [SDURLCache](https://github.com/rs/SDURLCache) for iOS and overrides Android's HttpResponseCache to reduce HTTP request overhead.

> On iPhone OS, Apple did remove on-disk cache support for unknown reason. Some will say it's to save flash-drive life, others will arg it's to save disk capacity. As it is explained in the NSURLCacheStoragePolicy, the NSURLCacheStorageAllowed constant is always treated as NSURLCacheStorageAllowedInMemoryOnly and there is no way to force it back, the code is certainly gone on this platform. For whatever reason Apple removed this feature, you may be interested by having on-disk HTTP request caching in your application. SDURLCache gives back this feature to this iPhone OS for you.

--  [SDURLCache](https://github.com/rs/SDURLCache)
