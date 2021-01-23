---
title: "Introducing Godzillops"
date: 2018-01-23T21:01:16-06:00
Description: ""
Tags: ["remote work", "strategy", "trends"]
Categories: []
---

## ゴジラ — King of Business Operations

Slack bots are a known commodity at this point. Whether you realize it or not, most workspaces you are in are using bots, slash commands, *etc.* to boost job productivity. At [StatMuse](https://www.statmuse.com), we decided to build a bot capable of helping us onboard new employees using natural language processing (NLP), the same computer science concept we employ in bringing answers to your sports questions every day. We’re a completely remote team and ChatOps is a critical path to scaling BizOps for our organization. This bot is known as [Godzillops](https://github.com/statmuse/godzillops) (also lovingly referred to as GZ), and we’re announcing that we’ve open sourced this tool and it’s runtime platform, [Tokyo](https://github.com/statmuse/tokyo).

![King of Business Operations](/images/godzillops1.gif)*King of Business Operations*

## What can GZ do?

We use Godzillops to add new employees to our Google Business organization as well as send out invites to GitHub (if they are a developer), Trello, and/or Abacus. Below are some action shots of GZ putting in the work. To start out, let’s add a Google account — to do that, you go and DM Godzillops, and tell it you want to create an account.

![GZ Convo](/images/godzillops2.png)

Next, you can invite these accounts to any of the other services currently offered by GZ.

![easy peasy](/images/godzillops3.png)

![lemon squeezy](/images/godzillops4.png)

![github success](/images/godzillops5.png)

## What is GZ built with?

Godzillops is built with [Python](https://www.python.org/) 3.4 and [nltk](http://www.nltk.org/). Tokyo also uses Python & the “official” [slack client](https://github.com/slackapi/python-slackclient) library. We have our version running on a EC2 t2.micro and in a supervisor process. CI scripts are available in the repo for AWS CodePipeline.

## Help out!

We’re excited to see what the community contributes back to GZ and hear about how it’s used at other companies.

![GZ out](/images/godzillops6.gif)

## StatMuse is on Slack!

If you made it this far in the post, then slackbots are probably your thing! You can talk to your favorite players directly from Slack with StatMuse. Ask sports questions about players and teams from the NBA, MLB & NFL. Get it [here](https://slack.com/apps/A7U7ZN46Q-statmuse)!

![Thanks SVP](/images/godzillops7.png)*Thanks SVP*

--

*I originally wrote this post while working at [StatMuse](https://www.statmuse.com) - reposted here for personal archive.*
