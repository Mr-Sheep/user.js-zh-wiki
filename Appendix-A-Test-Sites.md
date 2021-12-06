下面的列表包含了测试你的浏览器的各种网站。你应该在这些网站上启用Javascript（JS），以使测试呈现最坏的情况。在现实中，你可以用uBlock Origin等扩展程序控制网站上的JS和XSS（跨网站脚本），以减少指纹攻击的可能性。

### :small_orange_diamond: 浏览器对比 [Defaults]
- [PrivacyTests.org](https://privacytests.org/) - **h**ttps://privacytests.org/ <sup>[github](https://github.com/arthuredelstein/privacytests.org)</sup>

### :small_orange_diamond: 指纹识别

这些都是很好的来源，可以一次性抓取你的结果信息，但是[不要太看重他们的熵值](https://github.com/arkenfox/user.js/wiki/4.1-Extensions#small_orange_diamond-%EF%B8%8F-anti-fingerprinting-extensions-fk-no) 因为这些数据是有污点的，而且不要以为你是一个指纹专家，参见[测试你的指纹](https://matt.traudt.xyz/p/SkxEFK1m.html#testing-your-fingerprint)

- [Am I Unique?](https://amiunique.org/) - **h**ttps://amiunique.org/
- [Cover Your Tracks](https://coveryourtracks.eff.org/) - **h**ttps://coveryourtracks.eff.org/ [formerly Panopticlick] <sup>[github](https://github.com/EFForg/cover-your-tracks)</sup>
- [CreepJS](https://abrahamjuliot.github.io/creepjs/index.html) - **h**ttps://abrahamjuliot.github.io/creepjs/index.html <sup>[github](https://github.com/abrahamjuliot/creepjs)</sup>
   - Additional tests listed in the footer
- [Device Info](https://www.deviceinfo.me/) - **h**ttps://www.deviceinfo.me/
- [DuckDuckGo](https://privacy-test-pages.glitch.me/privacy-protections/fingerprinting/) - **h**ttps://privacy-test-pages.glitch.me/privacy-protections/fingerprinting/ <sup>[github](https://github.com/duckduckgo/privacy-test-pages)</sup>
   - there are also additional various privacy tests on the landing page
- [FingerprintJS](https://fingerprintjs.github.io/fingerprintjs/) Basic Version - **h**ttps://fingerprintjs.github.io/fingerprintjs/
- [Vytal](https://vytal.io/) - **h**ttps://vytal.io/

### :small_orange_diamond: 多项测试  [单页面]
- [Do I Leak?](https://www.doileak.com/) - **h**ttps://www.doileak.com/
- [HTML5 Test](https://html5test.com/) - **h**ttps://html5test.com/
- [IP/DNS Leak](https://ipleak.net/) - **h**ttps://ipleak.net/
- [IP Duh](https://ipduh.com/anonymity-check/) - **h**ttps://ipduh.com/anonymity-check/
- [Permissions](https://permission.site/) - **h**ttps://permission.site/
   * [GitHub](https://github.com/chromium/permission.site) - **h**ttps://github.com/chromium/permission.site
- [Whoer](https://whoer.net/) - **h**ttps://whoer.net/

### :small_orange_diamond: 多项测试 [多页面]
- [BrowserLeaks](https://www.browserleaks.com/) - **h**ttps://www.browserleaks.com/
- [CanvasBlocker Test Pages](https://canvasblocker.kkapsner.de/test/) - **h**ttps://canvasblocker.kkapsner.de/test/
- [Privacycheck](https://privacycheck.sec.lrz.de/index.html) - **h**ttps://privacycheck.sec.lrz.de/index.html
   * [ETag](https://privacycheck.sec.lrz.de/passive/fp_etag/fp_etag.php) - **h**ttps://privacycheck.sec.lrz.de/passive/fp_etag/fp_etag.php
### :small_orange_diamond: 加密 / Ciphers / SSL/TLS / 证书
- [JA3](https://ja3er.com/) - **h**ttps://ja3er.com/
- [BadSSL](https://badssl.com/) - **h**ttps://badssl.com/
- [DCSec](https://cc.dcsec.uni-hannover.de/) - **h**ttps://cc.dcsec.uni-hannover.de/
- [Qualys SSL Labs](https://www.ssllabs.com/ssltest/viewMyClient.html) - **h**ttps://www.ssllabs.com/ssltest/viewMyClient.html
- [Fortify](https://www.fortify.net/sslcheck.html) - **h**ttps://www.fortify.net/sslcheck.html
- [How's My SSL](https://www.howsmyssl.com/) - **h**ttps://www.howsmyssl.com/
- [GRC Fingerprint](https://www.grc.com/fingerprints.htm) - **h**ttps://www.grc.com/fingerprints.htm

### :small_orange_diamond: Mozilla's Safe Browsing, Tracking Protection <sup>[github](https://github.com/mozilla/itisatrap)</sup>
- [Attack](https://itisatrap.org/firefox/its-an-attack.html) - **h**ttps://itisatrap.org/firefox/its-an-attack.html
- [Blocked](https://itisatrap.org/firefox/blocked.html) - **h**ttps://itisatrap.org/firefox/blocked.html
- [Malware](https://itisatrap.org/firefox/unwanted.html) - **h**ttps://itisatrap.org/firefox/unwanted.html
- [Phishing](https://itisatrap.org/firefox/its-a-trap.html) - **h**ttps://itisatrap.org/firefox/its-a-trap.html
- [Tracking](https://itisatrap.org/firefox/its-a-tracker.html) - **h**ttps://itisatrap.org/firefox/its-a-tracker.html

### :small_orange_diamond: 其他
- [AudioContext](https://audiofingerprint.openwpm.com/) - **h**ttps://audiofingerprint.openwpm.com/
- [Cache Fingerprinting](https://cookieless-user-tracking.herokuapp.com/) - **h**ttps://cookieless-user-tracking.herokuapp.com/
   * It does this by assigning a unique variable in a cached script (see [#436](https://github.com/arkenfox/user.js/issues/436#issuecomment-392069853))
   * Article: https://robertheaton.com/2014/01/20/cookieless-user-tracking-for-douchebags/
- [CSS Exfil Vulnerability](https://www.mike-gualtieri.com/css-exfil-vulnerability-tester) - **h**ttps://www.mike-gualtieri.com/css-exfil-vulnerability-tester
- [CSS History Leak](https://earthlng.github.io/testpages/visited_links.html) <sup>1</sup> - **h**ttps://earthlng.github.io/testpages/visited_links.html
- CSS Media: disable JS, resize the browser with the tests open
   * [@media window size leak](https://demos.traudt.xyz/css/media/index.html) - **h**ttps://demos.traudt.xyz/css/media/index.html
   * [screen & inner window measurements](https://arthuredelstein.github.io/tordemos/media-query-fingerprint.html) - **h**ttps://arthuredelstein.github.io/tordemos/media-query-fingerprint.html
- [DNS Leak](https://www.dnsleaktest.com/) - **h**ttps://www.dnsleaktest.com/
- [DNS Spoofability](https://www.grc.com/dns/dns.htm) - **h**ttps://www.grc.com/dns/dns.htm
- [Firefox Storage Test](https://firefox-storage-test.glitch.me/) - **h**ttps://firefox-storage-test.glitch.me/
- [HTML5](https://www.youtube.com/html5) - **h**ttps://www.youtube.com/html5
- [IPv6 Leak](https://ipv6leak.com/) - **h**ttps://ipv6leak.com/
- [Keyboard Events](https://w3c.github.io/uievents/tools/key-event-viewer.html) - **h**ttps://w3c.github.io/uievents/tools/key-event-viewer.html
   * [Hotkeys Testing](https://rawgit.com/jeresig/jquery.hotkeys/master/test-static-01.html) - **h**ttps://rawgit.com/jeresig/jquery.hotkeys/master/test-static-01.html
- [Ping Spotter](https://armin.dev/apps/ping-spotter/) - **h**ttps://armin.dev/apps/ping-spotter/
- [Popup Killer](https://www.kephyr.com/popupkillertest/index.html) - **h**ttps://www.kephyr.com/popupkillertest/index.html
- [Punycode](https://www.xn--80ak6aa92e.com/) - **h**ttps://www.xn--80ak6aa92e.com/ (www . apple . com)
   * [Article](https://www.xudongz.com/blog/2017/idn-phishing/) by author of PoC
- [Redirects](https://jigsaw.w3.org/HTTP/300/Overview.html) - **h**ttps://jigsaw.w3.org/HTTP/300/Overview.html
- [Referer Headers](https://www.darklaunch.com/tools/test-referer) - **h**ttps://www.darklaunch.com/tools/test-referer
- [rel=noopener](https://mathiasbynens.github.io/rel-noopener/) - **h**ttps://mathiasbynens.github.io/rel-noopener/
- [WebRTC](https://browserleaks.com/webrtc) - **h**ttps://browserleaks.com/webrtc

<sup>1</sup> 这是一个 PoC (概念验证). 你需要将 `layout.css.visited_links_enabled` 的值改为 `true`。 你还需要一个正常的窗口 (不是隐私浏览模式)。该PoC只包括少数几个网站。为了获得最佳效果：
 *  在一个普通的火狐浏览器中打开一个正常的窗口。清楚所有内容 (Ctrl-Shift-Del).
 * 进入一些网站: e.g. https://www.cnn.com/ and https://www.foxnews.com/
 * 前往 [测试页面](https://earthlng.github.io/testpages/visited_links.html) 花30秒玩个小游戏