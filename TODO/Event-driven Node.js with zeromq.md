description: See how well zeromq fits into the event-driven nature of Node.js applications.

In the past four months I've been developing a webapp with fairly complex backend processes. My team and I tried out an event-driven approach, since we were able to break down the processes to some discrete events. Today we have about 15 services, which isn't much compared to big apps
In the past 4 months I've been developing a webapp with zeromq, Java and Node.js. It includes fairly complex backend processes which we were able to break down to events. So my team and I decided to try out an event-driven architecture. Implementing processes event-driven isn't harder in Java than in Node.js but for me it feels more natural in the evented Javascript environment.