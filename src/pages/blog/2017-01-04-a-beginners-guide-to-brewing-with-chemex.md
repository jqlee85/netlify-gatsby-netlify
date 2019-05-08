---
templateKey: blog-post
title: Hello world
date: 2017-01-04T15:04:10.000Z
description: >-
  Your very first content with Contentful, pulled in JSON format using the
  Content Delivery API.
featuredpost: false
featuredimage: /img/cameron-kirby-88711.jpg
tags:
  - general
---
These is your very first content with Contentful, pulled in JSON format using the [Content Delivery API](https://www.contentful.com/developers/docs/references/content-delivery-api/ "Content Delivery API"). Content and presentation are now decoupled, allowing you to focus your efforts in building the perfect app.

## Your first steps

Building with Contentful is easy. First take a moment to get [the basics of content modelling](https://www.contentful.com/r/knowledgebase/content-modelling-basics/ "the basics of content modelling"), which you can set up in the [Contentful Web app](https://app.contentful.com/ "Contentful Web app"). Once you get that, feel free to drop by the [Documentation](https://www.contentful.com/developers/docs/ "Documentation") to learn a bit more about how to build your app with Contentful, in particular the [API basics](https://www.contentful.com/developers/docs/concepts/apis/ "API basics") and each one of our four APIs, as shown below.

### Content Delivery API

The [Content Delivery API](https://www.contentful.com/developers/docs/references/content-delivery-api/ "Content Delivery API") (CDA), available at `cdn.contentful.com`, is a read-only API for delivering content from Contentful to apps, websites and other media. Content is delivered as JSON data, and images, videos and other media as files.
The API is available via a globally distributed content delivery network. The server closest to the user serves all content, both JSON and binary. This minimizes latency, which especially benefits mobile apps. Hosting content in multiple global data centers also greatly improves the availability of content.

### Content Management API

The [Content Management API](https://www.contentful.com/developers/docs/references/content-management-api/ "Content Management API") (CMA), available at `api.contentful.com`, is a read-write API for managing content. Unlike the Content Delivery API, the management API requires you to authenticate as a Contentful user. You could use the CMA for several use cases, such as:
* Automatic imports from different CMSes like WordPress or Drupal.
* Integration with other backend systems, such as an e-commerce shop.
* Building custom editing experiences. We built the [Contentful Web app](https://app.contentful.com/ "Contentful Web app") on top of this API.

### Preview API

The [Content Preview API](https://www.contentful.com/developers/docs/concepts/apis/#content-preview-api "Content Preview API"), available at `preview.contentful.com`, is a variant of the CDA for previewing your content before delivering it to your customers. You use the Content Preview API in combination with a "preview" deployment of your website (or a "preview" build of your mobile app) that allows content managers and authors to view their work in-context, as if it were published, using a "preview" access token as though it were delivered by the CDA.

### Images API

The [Images API](https://www.contentful.com/developers/docs/concepts/apis/#images-api "Images API"), available at `images.contentful.com`, allows you to resize and crop images, change their background color and convert them to different formats. Using our API for these transformations lets you upload high-quality assets, deliver exactly what your app needs, and still get all the benefits of our caching CDN.
