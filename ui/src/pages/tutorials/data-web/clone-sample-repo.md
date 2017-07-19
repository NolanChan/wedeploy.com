---
title: "Clone Sample Repo"
description: "In this section, you'll learn how to save and get data on the web using the WeDeploy API Client."
buttonTitle: "I cloned the repo"
tutorialTitle: "Getting started with WeDeploy Data on the web"
parentId: "data-web"
layout: "tutorial"
time: 30
weight: 3
---

#### Clone Sample Repo

First, you'll clone a sample repo that contains the necessary files and directories for deploying a site with Data.

Run this command in your terminal:

```
git clone https://github.com/wedeploy/tutorial-data-web.git
```

<aside>

###### <span class="icon-16-star"></span> Pro Tip

Every WeDeploy project follows a similar file structure by using JSON files to managing your project, service, and data path configurations.

```xml
your-project
├── data
│   ├── api.json
│   └── container.json
├── hosting
│   ├── container.json
│   └── index.html
└── project.json
```

You can see a similar file structure in the repo you just cloned. Want to know more about <a href="/docs/intro/configuration-files.html" target="_blank">configuration files</a>?

</aside>
