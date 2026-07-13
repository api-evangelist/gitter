---
title: "Drop Database Migration in Core Data"
url: "https://blog.gitter.im/2016/09/05/drop-database-migration-in-core-data/"
date: "2016-09-05"
author: "Andy Trevorah"
feed_url: "https://blog.gitter.im/feed"
---
Core Data supports migrating persistent stores (databases) from one model (schema) to the next without losing the existing content. It involves keeping versions of your model and the required mappings between them. However if you have a REST based app, then you are probably fine with not having to migrate the user's content as you can just fetch it all again from the server. You can do this in a
