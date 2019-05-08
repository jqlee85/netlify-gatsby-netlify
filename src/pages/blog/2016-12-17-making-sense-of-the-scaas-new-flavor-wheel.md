---
templateKey: blog-post
title: Automate with webhooks
date: 2016-12-17T15:04:10.000Z
description: >-
  Webhooks notify you, another person or system when resources have changed by
  calling a given HTTP endpoint. This is a new sentence!!!
featuredpost: false
featuredimage: /img/felix-russell-saw-112140.jpg
tags:
  - javascript
---
## What are webhooks?

The webhooks are used to notify you when content has been changed. Specify a URL, configure your webhook, and we will send an HTTP POST request whenever something happens to your content.

## How do I configure a webhook?

Go to Settings → Webhooks from the navigation bar at the top. From there, hit Add webhook, and you will be directed to your new webhook. Then choose a name, put in the information of your HTTP endpoint (URL and authentication), specify any custom headers and select the types of events that should trigger the webhook.

## Why do I get an old version in the CDA?

As the delivery API is powered by a CDN network consisting of hundreds of servers distributed across continents, it takes some time (up to a few minutes) to reflect the changes to the published content. This must be taken into consideration when reacting to webhooks. In normal conditions, there could be a reasonable delay of 2 to 5 minutes.

Extracted from the [Webhooks FAQ](https://www.contentful.com/faq/webhooks/ "Webhooks FAQ").
