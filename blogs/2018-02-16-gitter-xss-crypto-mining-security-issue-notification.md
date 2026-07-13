---
title: "Gitter XSS Crypto Mining Security Issue Notification"
url: "https://blog.gitter.im/2018/02/16/gitter-xss-cryptocoin-mining-security-issue-notification/"
date: "2018-02-16"
author: "Eric Eastwood"
feed_url: "https://blog.gitter.im/feed"
---
Issue Summary An XSS exploit in our KaTeX parser was used to embed a JavaScript crypto miner in clients via an exploitative message. The exploitative message was spread across 25 rooms and 146 users read those messages. The messages were available for about 1 hour ( minutes after being reported ) before being cleaned up across the board. User Remediation Steps To check if you are affected, open
