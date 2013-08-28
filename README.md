TracingDoc
==========

A one stop shop to get into tracing

What is tracing?
================

Tracing is the action of writing the flow of a program during normal and abnormal behavior. It is used to troubleshoot problems without affecting teh flow of the program.

Tracing differs from logging in that the data is generally not human readible but is able to be written quickly. Also, every event should have a timestamp allowing overlap with profiling. 


Why Trace?
==========

Tracing is useful to debug problems in production machines. It also allows peolpe to figure out why their program may be running slower than expected. It will give the full view of a system.

Because of this , the three main reasons to trace are: 

* understanding: to get a better idea of what's going on under the hood
* performance profiling: to figure out why your system is consuming the resources it is. (CPU/RAM/IO/NET...)
* non-disruptive testing: (minimally disruptive) testing protocols or real-time systems where a late answer is a bad answer

How to Trace?
=============

Using Printf?


Using LTTng?


How To View Traces?
===================

Picking the tool

Using Babeltrace? 

Using Battrace

Using Eclipse/LTTng

Using LTTv

Digging deeper
==============

Now that you've opeened and viewed a trace, here's some more analysis that can be done. 

Babeltrace

Battrace

Eclipse/LTTng

LTTv

References
==========

http://multivax.blogspot.ca/

http://dtrace.org/blogs/brendan/2013/08/16/memory-leak-growth-flame-graphs/
