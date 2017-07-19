---
title: "Deploying Ruby apps"
description: "Launch a Ruby application in few steps."
headerTitle: "Deploy"
layout: "guide"
weight: 4
---

### Ruby

###### {$page.description}

<article id="1">

## Introduction

Our email service enables you to send customized emails to your users and check on their status with just a few lines of code.

</article>

<article id="2">

## Try it yourself

Want to see the whole process of deploying an app on WeDeploy with Ruby?

<div class="guide-btn-cta">
	<a class="btn btn-accent btn-sm" href="/tutorials/ruby" target="_blank" data-senna-off>
		<span class="icon-16-external"></span>Try the tutorial
	</a>
</div>

<div class="guide-aux-cta">
	or see a <a href="http://boilerplate-ruby.wedeploy.io" target="_blank" data-senna-off>live demo</a>.
</div>

</article>

<article id="3">

## Configuring

<aside>

All WeDeploy projects use a consistant file structure and configuration files to deploy apps with Git or GitHub. Learn more on our <strong><a href="/docs/intro/how-it-works.html">How It Works Page</a></strong>.

</aside>

Below is an example of a `container.json` for a Ruby container.

```application/json
{
	"id": "ruby",
	"type": "wedeploy/ruby:latest",
	"hooks": {
		"build": "bundle install"
	}
}
```

The `id` for your services are uniquely determined by you.

</article>

## What's next?

Now you can start building your ruby based application.
