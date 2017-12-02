# Brightside Unique <img width="330px" src="images/brightside.svg"/>
<sup>[💬 Join the conversation at decstack](http://tinyurl.com/decstack-projects-invite) channel: brightside</sup>

Brightside Unique works with [Brightside](https://github.com/Brightside-Social/brightside) to provide a way for applications to verify that their users are unique.

This is important to basic income, voting, group decision-making, reputation systems, and charities.

## Components
### [Brightside Mobile](https://github.com/Brightside-Social/brightside)
Brightside registers real-world interactions. These form the basis for establishing someone's uniqueness.

Brightside users grant third-party applications the right to verify their uniqueness.

[More details on Brightside Mobile](https://github.com/Brightside-Social/brightside/wiki/Brightside-Mobile)

### Included With Brightside Unique
#### Mobile API
Applications interface with Brightside Mobile on the same device to retrieve a public key associated with the user.
#### Uniqueness API
An application pushes a public key obtained through the interaction API to one or more [Brightside nodes](https://github.com/Brightside-Social/brightside-node), which then perform a verification check and publish the result.

## How it Works
[Brightside nodes](https://github.com/Brightside-Social/brightside-node) store interactions, forming a social graph. By analyzing this graph, a node is able to determine whether or not a person can be verified as unique. When another application wants to know whether a user is a unique individual in their system, they make a request to a Brightside node.

Brightside nodes protect systems against fake or duplicate accounts, known as _sybils_.

Node operators may earn money for their services.

---
## Contribute

Check out our [open projects](https://github.com/orgs/Brightside-Social/projects).  Or [start a new Issue](https://github.com/Brightside-Social/brightside-unique/issues) and we'll add you to the conversation.

This repo is for our unique user verification service.

Other repos
* [Brightside](https://github.com/Brightside-Social/brightside): Mobile app for connecting to other Brightside users
* [Brightside Node](https://github.com/Brightside-Social/brightside-node): A node hosting the Brightside social graph
* [Github Pages repo for our site](https://github.com/Brightside-Social/Brightside-Social.github.io)

## Discuss

We have an active community on [Decstack](http://decstack.com/)--Join the conversation at http://tinyurl.com/decstack-projects-invite, channel: https://hub.decstack.com/projects/channels/brightside.
