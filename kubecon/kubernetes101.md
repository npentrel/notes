Kubernetes 101 - @bridgetkromhout
- was supposed to be 3h but they said 30 min
- they'll talk us through how to do it

### Intro (what even is this)

Typical scenario:
- you: learning a lot in a k8s workshop at a conference
- your coworkers: sad with all the FOMO

open-source k8s training
democratize k8s learning! - you can do this training
-> github.com/jpetazzo/container.training/

1. start with familiar things
2. limit unnecessary options
3. build understanding incrementally

#### The delivery of the workshop:
- container.training coming soon to you

This is open source - so you can fork it and use it for your trainings

Chapter 1 and 2 in the first hour or two
after a break chapter 3 and 4

```
@honest_update
We replaced our monolith with micro services so that every outage could be more like a murder mystery
```

- it's not very useful to do kubernetes trianings without an app people can see the parts of
- `dockercoins` app is in the repo to play around with

##### Setup
- requirements are in the git repo
- default is aws but you can set it up with aws
- look at how the clusters are configured after - this training wants to hand you all of this
- `open ips.html`
- these cards can be printed so that participants of the workshop can just get strated and don't have to find their credentials and remember them
- `prepare-vms` preconfigures instances with an ssh key and some other things

##### Caveats
- there can be timeouts
- the cluster is already configured, some people will like that others won't

### Content overview:
##### What's next
To be added:
- Helm
- Brigade
- virtual kubelet

Opinionated choices:
- `kubeadm` has a couple of characteristics that are different from other tools
  - it's not perfect and more complicated than swarm
  - but it let's people interact with the master node
- `weave` is being used but that's just a random choice


Meandering and details

What's next
