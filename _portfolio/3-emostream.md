---
title: "EmoStream: Concurrent Emoji Broadcast"
excerpt: |
  Scalable emoji reaction processing system for live events.
  <div style='text-align: center; margin-top: 10px;'>
    <img src='/images/emostream-pic.jpg' style='max-width: 100%; width: 500px; height: auto; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);'>
  </div>
collection: portfolio
---

Designed a scalable system to process billions of emoji reactions during live sports events.

- Utilized Kafka for queuing and Spark for real-time micro-batch aggregation at 2-second intervals  
- Built asynchronous API using Flask to receive emoji POST data from multiple clients simultaneously  
- Implemented load testing to simulate thousands of emoji interactions with high concurrency  

[View on GitHub](https://github.com/UllasSG/EmoStream)
