---
title: "Deploying Node.js apps"
description: "Launch a Node.js application in few steps."
headerTitle: "Deploy"
layout: "guide"
weight: 3
---

### Node.js

###### {$page.description}

<article id="1">

## Introduction

Our email service enables you to send customized emails to your users and check on their status with just a few lines of code.

</article>

<article id="2">

## Try it yourself

Want to see the whole process of deploying an app on WeDeploy with Node.js?

<div class="guide-btn-cta">
	<a class="btn btn-accent btn-sm" href="/tutorials/nodejs" target="_blank" data-senna-off>
		<span class="icon-16-external"></span>Try the tutorial
	</a>
</div>

<div class="guide-aux-cta">
	or see a <a href="http://boilerplate-nodejs.wedeploy.io" target="_blank" data-senna-off>live demo</a>.
</div>

</article>

<article id="3">

## Configuring

<aside>

All WeDeploy projects use a consistant file structure and configuration files to deploy apps with Git or GitHub. Learn more on our <strong><a href="/docs/intro/how-it-works.html">How It Works Page</a></strong>.

</aside>

Below is an example of a `container.json` for a Node.js container.

```application/json
{
	"id": "nodejs",
	"type": "wedeploy/nodejs:latest",
	"hooks": {
		"build": "npm install"
	}
}
```

The `id` for your services are uniquely determined by you.

</article>

## What's next?

Now you can start building your Node.js based application.
