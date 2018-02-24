# BrightID API <img width="330px" src="images/logo.svg"/>
<sup>[💬 Join our active community on decstack](https://hub.decstack.com/signup_user_complete/?id=wutow3kb6bda5bhptir6aapyfh) channel: BrightID</sup>

APIs allow applications to connect to [BrightID](https://github.com/BrightID/BrightID) to verify that their users are unique.

## Mobile API
Applications interface with BrightID Mobile on the same device through the Mobile API to retrieve the public key associated with a user.

## Node API
[BrightID nodes](https://github.com/BrightID/BrightID-Node) return the _trust score_ associated with a public key obtained through the mobile API.  The trust score represents a user's likelihood of being unique.  The API connects automatically to several nodes to retrieve an accurate score by consensus.

## How it Works
[BrightID nodes](https://github.com/BrightID/BrightID-Node) store connections between users, forming a social graph. Nodes analyze the graph and assign users _trust scores_. When an application wants to know whether a user is a unique individual in their system, they make a request to a BrightID node.

BrightID nodes protect systems against fake or duplicate accounts, known as _sybils_.

---
## Contribute

Check out our [open projects](https://github.com/BrightID/BrightID-Service/projects).  Or [start a new Issue](https://github.com/BrightID/BrightID-Service/issues) and we'll add you to the conversation.

This repo is for our unique user verification service APIs.

Other repos
* [BrightID](https://github.com/BrightID/BrightID): Mobile app for connecting to other BrightID users
* [BrightID Node](https://github.com/BrightID/BrightID-Node): A node hosting the BrightID social graph
* [Github Pages repo for our site](https://github.com/BrightID/BrightID.github.io)

## Discuss

We have an active community on [Decstack](http://decstack.com/)--Join the conversation at [the Decstack projects team](https://hub.decstack.com/signup_user_complete/?id=wutow3kb6bda5bhptir6aapyfh), channel: https://hub.decstack.com/projects/channels/brightid.
