---
title: "Checking Status"
description: "Sending an email is an asynchronous task. Use this API to know if an email was sent or not."
headerTitle: "Email"
layout: "guide"
weight: 3
---

### {$page.title}

###### {$page.description}

<article id="1">

## Checking Status

In order to check if an email was sent or not, we can use the email ID, e.g. `123`, and request the status in the same way we sent the email.

```javascript
WeDeploy
	.email('<serviceID>-<projectID>.wedeploy.io')
	.auth('<your-project-master-token>')
	.status('<email-id>')
	.then(function(response) {
		console.log('Email status:', response);
	})
	.catch(function(error) {
		// Some error has happened
	});
```
```swift
WeDeploy.email('<serviceID>-<projectID>.wedeploy.io')
	.checkEmailStatus(id: "202605176596079530")
	.then { status in
		print("Email status: \(status)")
	}
	.catch { error in
		// Some error has happened
	}
```
```text/x-java
WeDeploy
	.email('<serviceID>-<projectID>.wedeploy.io')
	.checkEmailStatus("<emailID>")
	.execute();
```

</article>
