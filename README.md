# mycss
Think about that one though. Is a minute enough granularity to determine which person goes to which teller? 
At time 0, all tellers would get a customer from the front of the queue 

After every 4 minute,  a new customer are added to back of the queue, and all tellers get a new customer. 
rinse and repeat. 

I would actually start with creating a Teller object with a property indicating either how long it takes to serve a customer, or how many 

per minute they can handle. (I like the time to serve option as it provides a bit more flexibility in some respects, but it doesn't 

exactly match your spec) 
You could then represent this scenario as an array of Tellers, and a Queue of customers. 
