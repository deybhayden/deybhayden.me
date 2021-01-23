---
title: "Coffee and Bagel(bot)?s"
date: 2017-12-12T21:01:11-06:00
Description: ""
Tags: ["remote work", "management"]
Categories: []
---

## Connecting with people in a Remote Workplace

Remote workforces are fairly common these days, especially in tech startups, but connecting on a personal level with these remote workers is still a challenge. At [StatMuse](https://www.statmuse.com/), we use a small chat bot, [bagelbot](https://github.com/statmuse/bagelbot), to set up randomized meetings with 3–4 different people in the company on a scheduled basis. The structure of these calls varies depending on the people paired, but the common theme of deepening bonds is universal. Bagelbot plays a small, but pivotal role in this event, so I’ll go over a couple details in this post.

Every other week (for our company), Bagelbot takes attendance at a given time, asking people if they will be attending this weeks meeting:

![Bagelbot so wishes you’d join in](/images/bagelbot1.png)*Bagelbot so wishes you’d join in*

Then, after a specified amount of time passes, he quits listening for attendance responses and generates random pairs of at least 3 people. He then spits out the pairs in a channel, accompanied by a Google Hangout link for the different parties to use.

![n.ame format is used to avoid spamming unavailable people](/images/bagelbot2.png)*n.ame format is used to avoid spamming unavailable people*

That’s pretty much it! The bot itself is a handful of scripts posting/receiving messages. The scheduling piece is just managed by a simple recurring cronjob on a AWS t2.micro Linux instance. Check it out on [GitHub](https://github.com/statmuse/bagelbot) for more technical details/questions.

--

*I originally wrote this post while working at [StatMuse](https://www.statmuse.com) - reposted here for personal archive.*
