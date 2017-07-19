---
title: "Add Container.json"
description: "In this section, you'll learn how to deploy an application using WeDeploy Ruby."
buttonTitle: "I created the container.json"
tutorialTitle: "Getting started with WeDeploy Ruby"
parentId: "ruby"
layout: "tutorial"
time: 40
weight: 4
---

#### Add Container.json

Every service folder must have a `container.json` file that configures the service. Let's add one to the repo we just cloned.

1. Open the `tutorial-ruby` folder in a code editor
2. Create a new file named `container.json` inside the `ruby` folder.
3. In that file, paste this code:

```application/json
{
	"id": "ruby",
	"type": "wedeploy/ruby",
	"hooks": {
		"build": "bundle install"
	}
}
```

<aside>

###### <span class="icon-16-star"></span> Pro Tip

As you can see above, we added a `hook` in our `container.json` file. Whatever task you put as a `hook` will be completed during the build cycle prior to each deployment.

</aside>
