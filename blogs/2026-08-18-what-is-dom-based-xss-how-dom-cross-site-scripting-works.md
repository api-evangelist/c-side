---
title: "What Is DOM-Based XSS? How DOM Cross-Site Scripting Works"
url: "https://cside.com/blog/what-is-dom-based-xss"
date: "2026-08-18"
author: "Simon Wijckmans"
feed_url: "https://cside.com/blog/rss.xml"
---
DOM-based XSS is a cross-site scripting attack where the vulnerability lives entirely in client-side JavaScript: the page's own code reads attacker-controlled input and writes it into the DOM unsafely. This guide explains how it differs from reflected and stored XSS, common sources and sinks, and how to detect it.
