### Weekly reports
### 2019-04-08 -> 2019-04-14

* #### Joel
Wrote on the report. Wrote about nested signatures, security issues, interface, c++, cryptography. Booked rooms and documented important points. 
* #### Robert
I worked on the simulation with the agents sending their messages. At first, I planned some practical details regarding the network hosts and the networked applications running on them, and asked the group if the resulting simulation structure was good. I wrote skeleton code for the agents' input and output interfaces, with the goal of connecting everything properly. At the same time, I worked on the Mininet API code for the network emulation. In doing this, I noticed some unintended behaviour in our TCP connection handling code, so I rewrote parts of it, and also did some refactoring to make it easier to work with. I also spent time merging our type handling code (i.e. the sequential communication test) with our network code.
* #### Adi
Spent my week mostly coding the core components for message passing. Several changes and new ideas were implemented, but it seems like we've settled on total hex-based message sending now. Devoted a lot of time trying to generalize methods into a seperate class. Added a lot of comments for improved readability. Changed the structure of old code to be consistent with newer one.

* #### Fredrik

* #### Johan

### What we have done
This week we continued to work on our individual parts. Joel and Johan worked on the report meanwhile Adi and Robert continued working on the code. The code will soon be done, only a few interfaces is now missing and a few bugs are left. We decided to encode our messages hex.hex instead of our old version. The report is coming along nicely, we have written a lot in the results and method parts now and are up to ~9 pages of text. 

We also had a meeting with Robin where we discussed what we have done and he was very happy with the results. 
### Preperations before next week
