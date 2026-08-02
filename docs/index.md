### About Me

[Linkedin](https://www.linkedin.com/in/richardnaik/)

[GitHub](https://github.com/richardnaik)

I'm a SysAdmin by day and I tinker on my homelab for fun and skill improvement. I use a lot of automations and abstractions at work so at home I try to keep things realtively simple at home, emphasis on relative since I'm still a weirdo who enjoys this sort of thing.

My goal with this project is to help my family make sense of all the stuff in my office in case I get hit by a bus, and to help ME make sense of it all in case I forget.

I've grouped things into three categories, hardware, storage, and services. Services are deployed using a standard Docker daemon and compose files. Beyond compose itself I don't use many automations for this since I use them at work enough to keep me up to snuff, and I want to keep my manual CLI skills sharp. 

In the past I've tried various flavors of high avavilability clustering with my Pis such as Nomad, k3s, and Docker Swarm. While these "worked", it was a massive pain to keep them up to date and they didn't even have the resiliency I wanted during power outages and such. This setup also left the Pis to do almost all of the work while Evo sat mostly idle, a massive waste of resources.

TLDR it's a Linux server running Docker behind a Ubiquiti networking stack. Not much more too it than that.