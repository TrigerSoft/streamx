---
layout: md
---
## Streamx - CEP as a service for Azure
we take the leading CEP engine and tightly integrate it with Azure to create a simple and powerfull developer experience

#### Key capabilities and benefits
* **Ease of use**: user friendly development environment
 * Syntax highlighting
 * Static ongoing compilation and error reporting
 * Multiple files for better code organization
 * In-browser query testing
* **Power**: declarative Drools business rules language
 * Specially designed javascript-like declarative <a href="http://docs.jboss.org/drools/release/6.3.0.Final/drools-docs/html/ch08.html" target="_blank">language</a>
 * Ability to combine multiple Event Hubs and other inputs in the same rule
 * Advanced <a href="http://docs.jboss.org/drools/release/6.3.0.Final/drools-docs/html/ch09.html#d0e12237" target="_blank">temporal reasoning</a>
 * Different types of <a href="http://docs.jboss.org/drools/release/6.3.0.Final/drools-docs/html/ch09.html#d0e12032" target="_blank">sliding windows</a>
 * Support for state *enter* and *exit* notifications. I.e. the system can track both cases, when conditions are met and/or *not* met anymore.
* **Ordering**: events from same partition will produce outputs sent to the same partition
* **Scalability**: tight integration with Azure Event Hubs allows the solution to scale up to the number of partitions configured for the Event Hubs. Scaling can be dynamically and uninterruptible applied from the management console
* **Reliability and quick recovery**: 
 * Managed service in the cloud
 * Built-in recovery capabilities via internal state maintainance guaranties At-Least-Once delivery
* **Low cost**: the service is built for you to pay as you go based on Processing Unit usage that can be dynamically adjusted
* **Reference data**: static or slow changing data can be combined with streaming data in the same rule
 * Azure tables with dynamic updates and deletes
 * Azure Blobs
* **Inputs**: 
 * Azure Event Hubs for data streams
 * Azure Blobs or Tables service (reference data)
* **Outputs**:
 * Azure Storage Blobs or Tables
 * Azure Event Hubs
 * Azure Service Bus Topics or Queues
