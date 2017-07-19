---
title: "Deploying Liferay apps"
description: "Launch a Liferay application in few steps."
headerTitle: "Deploy"
layout: "guide"
weight: 6
---

### Liferay

###### {$page.description}

<article id="1">

## Introduction

Our Liferay service enables you to deploy a Liferay Portal with all its capabilities with just a few lines of code.

</article>

<article id="2">

## Try it yourself

Want to see the whole process of deploying an app on WeDeploy with Liferay?

<div class="guide-btn-cta">
	<a class="btn btn-accent btn-sm" href="/tutorials/liferay" target="_blank" data-senna-off>
		<span class="icon-16-external"></span>Try the tutorial
	</a>
</div>

<div class="guide-aux-cta">
	or see a <a href="http://boilerplate-liferay.wedeploy.io" target="_blank" data-senna-off>live demo</a>.
</div>

</article>

<article id="3">

## Configuring

<aside>

All WeDeploy projects use a consistant file structure and configuration files to deploy apps with Git or GitHub. Learn more on our <strong><a href="/docs/intro/how-it-works.html">How It Works Page</a></strong>.

</aside>

Below is an example of a `container.json` for a Liferay container.

```application/json
{
	"id": "liferay",
	"type": "wedeploy/liferay:latest"
}
```

The `id` for your services are uniquely determined by you.

</article>

## What's next?

Now you can start building your liferay based application.
