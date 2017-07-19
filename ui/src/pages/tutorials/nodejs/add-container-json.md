---
title: "Add Container.json"
description: "In this section, you'll learn how to deploy an application using WeDeploy Node.js."
buttonTitle: "I created the container.json"
tutorialTitle: "Getting started with WeDeploy Node.js"
parentId: "nodejs"
layout: "tutorial"
time: 40
weight: 4
---

#### Add Container.json

Every service folder must have a `container.json` file that configures the service. Let's add one to the repo we just cloned.

1. Open the `tutorial-nodejs` folder in a code editor
2. Create a new file named `container.json` inside the `nodejs` folder.
3. In that file, paste this code:

```application/json
{
	"id": "nodejs",
	"type": "wedeploy/nodejs",
	"hooks": {
		"build": "npm install"
	}
}

```

<aside>

###### <span class="icon-16-star"></span> Pro Tip

As you can see above, we added a `hook` in our `container.json` file. Whatever task you put as a `hook` will be completed during the build cycle prior to each deployment.

</aside>
