---
title: "Today I will… find hidden latency across a distributed .NET application"
url: "https://devblogs.microsoft.com/visualstudio/today-i-will-find-hidden-latency-across-a-distributed-net-application/"
date: "2026-09-08"
author: "Justin Yoo"
feed_url: "https://devblogs.microsoft.com/visualstudio/feed/"
---
When a distributed application feels slow, the user sees one delay. The code behind that delay may run across a web frontend, backend services, databases, and external APIs. If you profile only the frontend while the backend is slow, the profiler can show that the frontend is healthy without revealing the actual bottleneck.
