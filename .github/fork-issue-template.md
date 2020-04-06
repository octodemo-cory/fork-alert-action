---
title: Alert! Fork Created out of organization scope 
label: bug 
---

## Someone just created an invalid fork, oh no!  

#### Here's who did it: @{{ payload.sender.login }} -- the new repository is located at {{ payload.forkee.html_url }}. 

#### @{{ payload.sender.login }}, please delete this personal fork and fork into a known organization instead, or transition to a [branch-based Git Flow](https://guides.github.com/introduction/flow/) in this repository.
