## What is it?
This is test implementation of Netty socket communication. In the documentation https://netty.io/4.1/api/io/netty/channel/ChannelPipeline.html it's written:

 // Tell the pipeline to run MyBusinessLogicHandler's event handler methods<br />
 // in a different thread than an I/O thread so that the I/O thread is not blocked by<br />
 // a time-consuming task.<br />
 // If your business logic is fully asynchronous or finished very quickly, you don't<br />
 // need to specify a group.<br />
 pipeline.addLast(group, "handler", new MyBusinessLogicHandler());<br />
 
But 