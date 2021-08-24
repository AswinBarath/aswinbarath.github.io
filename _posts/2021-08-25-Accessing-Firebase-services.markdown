---
layout: post
title: Accessing Firebase services
date:   2021-08-25 01:00:00 +0530
description: Know more about how to access firebase services
img: Accessing-Firebase-services.png
tags: [Blog, firebase, backend]
author: Aswin Barath
---

Firebase API follows a straightforward approach. 
By invoking these methods will get you access to each Firebase service.

### Syntax to access Firebase Firestore

```
firebase.firestore()
```

### Syntax to access Firebase Authentication

```
firebase.auth()
```

### Syntax to access Firebase Storage

```
firebase.storage()
```

### Firebase hosting commands
Firebase Hosting uses a command-line interface instead of methods on the Firebase object. Run the following commands:

#### Initialize a Firebase project

```
firebase init 
```

#### deploy a Firebase project

```
firebase deploy 
```


Feel free to share if you found this useful 😃.