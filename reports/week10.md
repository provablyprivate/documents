### Weekly reports

### 2019-03-25 -> 2019-03-31
* #### Joel

Booked rooms, updated calenders, checked deadlines, documented, reformated my computer to have a newer version of gcc and ssl in order to keep working on the crypto part and coded.

* #### Robert
Since we were about to start merging what we had been working on, I started the week by looking at big picture design issues regarding our simulation. I tried to rework our JSON objects in an attempt to make them more consistent with the terms in the paper. Then I realized that we had no public key encryption scheme in place, so I started to work on that. I also had an idea about an implementation of the paper's proof type based on the Fiat-Shamir identification protocol and wanted something small and manageable to try the idea with, so I started to work on a simple implementation of the RSA encryption scheme using GNU MP. I abandoned my implementation when Johan shared his, which uses POCO's RSA implementation, and enhanced it with private key signing and public key verification.

* #### Adi
Implemented a demo for message passing to analyze code structure and quality. Put together a potential hardware order that will be used for the final presentation.

* #### Fredrik

* #### Johan

### What we have done
This week we kept working on our seperate branches to try to get as many features to work as possible.
We worked on JSON handlers, public key encryption and a way to demo the whole thing.

### Preperations before next week
On tuesday, we plan on merging a lot of the features together in order to make a working product.

