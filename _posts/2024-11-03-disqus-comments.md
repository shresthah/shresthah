---
layout: post
title: "My Thoughts on MDPI Journals: The Good, the Bad, and the Ugly"
date: 2024-11-03 11:59:00-0400
description: This blog emphasizes the importance of prioritizing quality over speed in academic publishing to maintain the integrity of research.
tags: comments
categories: external-services
disqus_comments: true
related_posts: true
published: false
---
<div style="text-align: justify">
This post shows how to add custom styles for blockquotes. Based on [jekyll-gitbook](https://github.com/sighingnow/jekyll-gitbook) implementation.

We decided to support the same custom blockquotes as in [jekyll-gitbook](https://sighingnow.github.io/jekyll-gitbook/jekyll/2022-06-30-tips_warnings_dangers.html), which are also found in a lot of other sites' styles. The styles definitions can be found on the [\_base.scss](https://github.com/alshedivat/al-folio/blob/master/_sass/_base.scss) file, more specifically:



A regular blockquote can be used as following:



> This is a regular blockquote
> and it can be used as usual

These custom styles can be used by adding the specific class to the blockquote, as follows:

<!-- prettier-ignore-start -->


> ##### HI
>
> A tip can be used when you want to give advice
> related to a certain content.
{: .block-tip }



> ##### WARNING
>
> This is a warning, and thus should
> be used when you want to warn the user
{: .block-warning }



> ##### DANGER
>
> This is a danger zone, and thus should
> be used carefully
{: .block-danger }

<!-- prettier-ignore-end -->
</div>
