---
title: "MongoDB-backed Spring Batch jobs and more in Spring Boot 4.1"
url: "https://spring.io/blog/2026/06/21/spring-boot-41-and-spring-batch"
date: "2026-06-21"
author: "joshlong"
feed_url: "https://spring.io/blog.atom"
---
Spring Boot 4.1 introduces native MongoDB support for Spring Batch's JobRepository via the new spring-boot-starter-batch-mongodb autoconfiguration, removing the prior need for a separate SQL database to store Batch metadata. The post walks an ETL example that keeps batch job state in MongoDB while reading from CSV and writing to PostgreSQL, covering auto-initialized collections, a two-step job, fault-tolerant retry, and GraalVM native image compilation.
