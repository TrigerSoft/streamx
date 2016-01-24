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
* **Power**: declarative Drools business rules language
 * Specially designed javascript-like declarative <a href="http://docs.jboss.org/drools/release/6.3.0.Final/drools-docs/html/ch08.html" target="_blank">language</a>
 * Advanced <a href="http://docs.jboss.org/drools/release/6.3.0.Final/drools-docs/html/ch09.html#d0e12237" target="_blank">temporal reasoning</a>
 * Different types of <a href="http://docs.jboss.org/drools/release/6.3.0.Final/drools-docs/html/ch09.html#d0e12032" target="_blank">sliding windows</a>
 * Support for state *enter* and *exit* notifications. I.e. the system can track both cases, when conditions are met and *not* met anymore.
* **Ordering**: results sent to the same output can be <a href="https://azure.microsoft.com/en-us/documentation/articles/service-bus-partitioning/" target="_blank">ordered</a>
* **Scalability**: tight integration with Azure Event Hubs allows the solution to scale up to the number of partitions configured for the Event Hubs. Scaling can be dynamially and uninterruptible applied from the management console
* **Reliability and quick recovery**: 
 * Managed service in the cloud
 * Built-in recovery capabilities via internal state maintainance guaranties At-Least-Once delivery
* **Low cost**: the service is built for you to pay as you go based on Processing Unit usage that can be dynamically adjusted
