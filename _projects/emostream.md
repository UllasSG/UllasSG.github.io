---
title: "EmoStream: Concurrent Emoji Broadcast"
collection: projects
permalink: /projects/emostream
excerpt: 'A scalable real-time system designed to process billions of emoji reactions during live sports events using Kafka and Spark.'
date: 2024-02-01
venue: 'Personal Project'
tech_stack: 'Kafka, Apache Spark, Flask'
github_url: 'https://github.com/UllasSG/emostream'
---

## Project Overview
A high-performance, scalable system designed to process billions of emoji reactions during live sports events using distributed computing technologies.

## Key Features
- **Real-time Processing**: Apache Spark micro-batch aggregation at 2-second intervals
- **Message Queuing**: Kafka for reliable stream processing and message distribution
- **High Concurrency**: Flask-based asynchronous API handling thousands of simultaneous requests
- **Load Testing**: Comprehensive testing framework to validate system performance

## Technical Highlights
- Distributed architecture supporting massive scale emoji processing
- Fault-tolerant design with automatic recovery mechanisms
- Performance metrics: 1M+ reactions per minute with sub-100ms latency
- Horizontal scaling capabilities for traffic spike management