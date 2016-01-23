---
layout: md
---
## CEP Concepts
Understanding the true nature of CEP applications

#### Data analytics is divided to two major domains:
1. Analyzing large amounts of *historical* data to make better decisions in the *future*. The data and decisions are usually not related directly.
2. Analyzing events in *current* time frame to take a *compensating* action. There is a direct relation between the event and the action.

#### The second domain is CEP. In summary, CEP applications must meet the following requirements:
- Events are happening in *real time*
<pre>planes reporting their coordinates</pre>
- Under certain conditions a *compensating* action needs to be taken
<pre>if distance between two planes is under some threshold, the pilots should be notified</pre>
- There is a temporal distance between events
<pre>distance between the planes is calculated based on their locations within some
(potentially short) time frame</pre>
- The action might be taken when the conditions are met and/or when these conditions are *not* met anymore
<pre>when distance between the planes is back above threshold, the pilots should be notified
again</pre>


> **Q: What if my application does not meet these requirements?**<br/>
**A: Probably there is a simpler and better solution to the problem!**
