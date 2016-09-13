# mt76x2e-feed
An OpenWRT/LEDE package feed for packages related to the [mt76x2e proprietary Ralink wifi driver](https://github.com/i80s/mtk-sources).

This feed contains Makefiles derived from https://github.com/rssnsj/openwrt-xiaomi-mini with a few patches to allow them to build against [LEDE](https://lede-project.org). To use it in your build, add the following line to the feeds.conf file in your buildroot:

``src/git https://github.com/jheretic/mt76x2e-feed.git``
