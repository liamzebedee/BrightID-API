# BrightID Service <img width="330px" src="images/logo.svg"/>
<sup>[💬 Join our active community on decstack](https://hub.decstack.com/signup_user_complete/?id=wutow3kb6bda5bhptir6aapyfh) channel: BrightID</sup>

BrightID Service is an API that works with [BrightID](https://github.com/BrightID/BrightID) to provide a way for applications to verify that their users are unique.

This is important to universal basic income, voting, rating systems, referrals, and giveaways.

## Components
### [BrightID Mobile](https://github.com/BrightID/BrightID)
BrightID mobile registers real-world interactions. These form the basis for establishing someone's uniqueness.

BrightID mobile users grant third-party applications the right to verify their uniqueness.

[More details on BrightID Mobile](https://github.com/BrightID/BrightID/wiki/BrightID-Mobile)

### Included With BrightID Service
#### Mobile API
Applications interface with BrightID Mobile on the same device to retrieve a public key associated with the user.
#### Uniqueness API
An application pushes a public key obtained through the interaction API to one or more [BrightID nodes](https://github.com/BrightID/BrightID-Node), which then perform a verification check and publish the result.

## How it Works
[BrightID nodes](https://github.com/BrightID/BrightID-Node) store interactions, forming a social graph. By analyzing this graph, a node is able to determine whether or not a person can be verified as unique. When another application wants to know whether a user is a unique individual in their system, they make a request to a BrightID node.

BrightID nodes protect systems against fake or duplicate accounts, known as _sybils_.

Node operators may earn money for their services.

---
## Contribute

Check out our [open projects](https://github.com/orgs/BrightID/projects).  Or [start a new Issue](https://github.com/BrightID/BrightID-Service/issues) and we'll add you to the conversation.

This repo is for our unique user verification service.

Other repos
* [BrightID](https://github.com/BrightID/BrightID): Mobile app for connecting to other BrightID users
* [BrightID Node](https://github.com/BrightID/BrightID-Node): A node hosting the BrightID social graph
* [Github Pages repo for our site](https://github.com/BrightID/BrightID.github.io)

## Discuss

We have an active community on [Decstack](http://decstack.com/)--Join the conversation at [the Decstack projects team](https://hub.decstack.com/signup_user_complete/?id=wutow3kb6bda5bhptir6aapyfh), channel: https://hub.decstack.com/projects/channels/brightid.
