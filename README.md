TA-context_metadata
-------------------

This TA is a proof of concept of dynamically inserting contextual data into the index paths. This might be useful in a scenario where you have a content expert have an app defining inputs that you may want to deploy across multiple clients (and you want to keep all the client data separate). 

Given the various hoops one has to go through to accomplish this, it seems like this implementation should likely remain an academic exercise until we can get a ER accepted by Splunk. If we could apply regex to multiple SOURCE_KEYS at the same time... we take each iteration from 5 steps down to 1. But a better solution may be some form of scripted input to look at inputs defined in an app and dynamically override them with contextual data... or another form of orchestration.