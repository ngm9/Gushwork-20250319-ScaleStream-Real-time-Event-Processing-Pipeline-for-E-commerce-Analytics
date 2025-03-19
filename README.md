
                    # ScaleStream: Real-time Event Processing Pipeline for E-commerce Analytics

                    ## Time to complete: 48h

                    ## Scenario
                    Retail Giant is a major online marketplace that processes millions of user interactions daily. They need a real-time analytics system to track user behavior, product performance, and sales trends to make data-driven decisions.

You've been tasked with building 'ScaleStream' - a scalable event processing pipeline that can ingest, process, and analyze high volumes of event data from their e-commerce platform. The system needs to handle peak loads of up to 10,000 events per second during flash sales and holiday seasons.

The pipeline should process various event types (page views, add-to-cart actions, purchases, product reviews, etc.) and store aggregated metrics in a database for real-time dashboards and reporting. The system must be fault-tolerant, handle backpressure effectively, and scale horizontally as traffic increases.

You'll need to implement a producer-consumer architecture using AWS services, optimize database operations for high throughput, and ensure the system can recover gracefully from failures without data loss. The solution should include monitoring capabilities to track system performance and identify bottlenecks.

                    ## Outcomes
                    ['Design and implement a producer service that simulates high-volume event generation (minimum 1,000 events/second) with configurable event types and rates', 'Create a scalable consumer architecture using AWS SQS that can process events concurrently and handle backpressure', 'Implement an event processor that aggregates data by various dimensions (time, product category, user segment, etc.)', 'Build a data storage layer using AWS RDS (PostgreSQL) with optimized schema and query patterns for high-throughput writes and reads', 'Develop a simple REST API that exposes real-time metrics and aggregated data', 'Implement comprehensive error handling, retry mechanisms, and dead-letter queues for failed events', 'Create a monitoring system that tracks key performance metrics (throughput, latency, error rates, queue depth)', "Write a load testing script that demonstrates the system's ability to scale under increasing load", 'Document the architecture, design decisions, and potential bottlenecks with recommendations for further scaling']

                    ## Constraints
                    ['Must use Python 3.8+ for all components', 'Must leverage AWS services (SQS, RDS at minimum) for the core infrastructure', 'The system must handle at least 1,000 events per second in sustained throughput', 'Database operations must be optimized for high-volume writes (bulk operations, connection pooling, etc.)', 'The solution must include proper connection handling and resource cleanup to prevent leaks', 'All components must be designed to scale horizontally', 'The system must be resilient to failures in any component (graceful degradation)', 'Comprehensive logging must be implemented for troubleshooting and monitoring', 'Code must follow PEP 8 style guidelines and include appropriate documentation', 'The solution must include unit tests for critical components']
                    