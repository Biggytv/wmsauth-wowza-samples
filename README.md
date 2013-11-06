Code snippets for WMSAuth hot-linking protection
=====================

WMSAuth is a feature set of WMSPanel, the admin and reporting panel. This feature set can be applied to **Wowza Media Server** and **Nimble Streamer**. It allows restriction of your media access by:
- hot-linking re-publishing protection;
- geo-location and IP ranges;
- connections count.

This protection and restriction may be 

Read more about it in this blog post: http://blog.wmspanel.com/2012/09/wowza-geo-ip-range-connections-lock.html

Current sample code snippets are provided for quick and seamless integration of hot-linking protection.

- "CSharp" contains snippet for C# modofying RTSP stream URL
- "java" contains Java snippet for RTSP
- "javascript" has NodeJS JavaScript sample snippet
- "php" has snippet for PHP processing of RTSP URL
- "php-jwplayer" has a snippet which contains JWPlayer with HLS and RTMP streams
- "php-rtmp-flowplayer" is a sample for flowpayer with RTMP stream
- "python" is obviously a Python sample

Please read the following posts describing Wowza re-streamign protection integration for your web site:
- http://blog.wmspanel.com/2012/05/protecting-wowza-from-re-publishing-re.html
- http://blog.wmspanel.com/2012/07/wmsauth-rtmp-protection-sample.html
- http://blog.wmspanel.com/2012/05/integrating-wmsauth-to-your-website.html

These code samples can also be applied to WMSAuth for Nimble Streamer. This functionality allows hot-linking protection and domain locking for HTTP Live Streaming, Smooth Streaming and progressive downoad. 
- http://blog.wmspanel.com/2013/11/nimble-streamer-protect-hotlinking-domain-lock.html
