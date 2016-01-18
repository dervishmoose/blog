---
layout: post
title:  "Serverless SlakBot, like PB & J"
date:   2016-01-07 14:36:23
tags: [serverless, slack]
categories: [Web]
image: lambda-slack.png
---

<span class="image featured"><img src="/images/lambda-slack.png" alt=""></span>
It’s like peanut butter and jelly. Good all by themselves, but way better together. Yum! Serverless (formerly JAWS) and Slack, BFF.

 I have thought about wring a slack bot to do this or to do that, but I realized that I would need to spin up a server OR host the backend on an existing server. Since I have been preaching about technology debt a lot lately, I ate my own dog food and decided not to spin up my own server.  (… and also to not write a slackbot.)

A few days ago serverless-slackbot was released. Serverless (formerly JAWS) leverages AWS Lambda and gives me a “spot” to store nodejs code that can respond to an API call.  There is no standing server to keep patched and updated. Thus greatly reducing the technology debt in deploying projects.

So now, the only real problem left to me is, what was the really really cool thing I was going to build a slack bot for? I don’t remember. Oh, well I’ll be ready next time.

From the Serverless Slack bot project page:

> ## Serverless Slackbot #
>A Serverless Module for the Serverless Framework featuring a SlackBot you can easily add skills to and package as a Slack Application, ready for distribution. All without servers!
> [Check out the project](https://github.com/serverless/serverless-slackbot)
