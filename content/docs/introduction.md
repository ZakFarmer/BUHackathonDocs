+++
title = "Introduction"
description = "This section covers how to use the API generally."
date = 2021-05-01T19:30:00+00:00
updated = 2021-05-01T19:30:00+00:00
draft = false
weight = 0
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "This section covers how to use the API generally."
toc = true
top = false
+++


## How do I make a request to the API?

It all depends on your use case. If you're using the API to get statistics as part of a presentation, for example, the most simple way is to use the browser. <br /><br />To get started, you can copy the link example on one of the endpoints to see how it works in your browser.<br /><br />Here is an example of a request to the Travel Impact endpoint: <br />[https://bu-hackathon-api.herokuapp.com/api/v1/impact/travel?busDistance=259&carDistance=2323&planeDistance=430&trainDistance=230](https://bu-hackathon-api.herokuapp.com/api/v1/impact/travel?busDistance=259&carDistance=2323&planeDistance=430&trainDistance=230)
<br /><br />
There are programs you can use to send requests to the API as well, such as [Postman](https://www.postman.com/) and [HTTPie](https://httpie.io/). API responses will come back as JSON objects, so it would help to read up on JSON if you're unfamiliar. More info [here](https://www.w3schools.com/js/js_json_intro.asp) from W3Schools.

## How do I integrate the API with my application?

If you want to build something to accompany your prototype/app idea, that's great! Depending on which programming language and platform you're targeting, there will be different libraries for making HTTP requests. Some HTTP client libraries for popular languages are:
- [Axios](https://github.com/axios/axios) for NodeJS
- [Requests](https://github.com/psf/requests) for Python
- [Retrofit](https://github.com/square/retrofit) for Java
- [Guzzle](https://github.com/guzzle/guzzle) for PHP
- [Hyper](https://github.com/hyperium/hyper) for Rust  
- [Alamofire](https://github.com/Alamofire/Alamofire) for Swift

For the most part these are heavily documented in a way that should make it relatively easy to get going with sending requests to an external API (whether you're building a simple console program or a frontend web app.)

## Can I contribute to the API / make my own version?

Of course you can! Feel free to fork the [repository](https://github.com/3sidedcube/BUHackathonAPI) and make your improvements - if you feel like everyone would benefit from them, you can make a pull request to the main repository.

If you're not familiar with Git, read more information about it [here](https://w3schools.com/git/git_intro.asp?remote=github). It's used a lot in the industry, so definitely something to learn if you're pursuing a Computer Science career.

## What endpoints are there to use?

You can view the OpenAPI documentation for the API [here](https://bu-hackathon-api.herokuapp.com/api/v1/docs) - this tells you exactly what to send (and what you will receive) to/from the API. Example requests are there for you to test (the simplest way is to copy the link into your browser.)

## How was this website built?

This website was created to give a resource of background information around the API to make it easier to use. It was created using [Zola](https://github.com/getzola/zola) - a Rust based static site generator - with the [Adidoks](https://github.com/aaranxu/adidoks) theme.