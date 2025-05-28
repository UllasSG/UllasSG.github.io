---
title: "EmoStream: Concurrent Emoji Broadcast"
excerpt: "Scalable emoji reaction processing system for live events.<br/><img src='/images/emostream-pic.jpg' style='width:500px; height:300px;'>"
collection: portfolio
---

Designed a scalable system to process billions of emoji reactions during live sports events.

- Utilized Kafka for queuing and Spark for real-time micro-batch aggregation at 2-second intervals
- Built asynchronous API using Flask to receive emoji POST data from multiple clients simultaneously
- Implemented load testing to simulate thousands of emoji interactions with high concurrency
