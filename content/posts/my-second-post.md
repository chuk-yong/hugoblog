---
title: "Adjusting Profile Sidebar on Hugo Anatole"
date: 2021-05-02T15:01:45+08:00
draft: false
---

When view in Chrome, the profile picture occupies the center of the section and the rows of favicons (contact, linkedin, github...) got lost in the bottom. 

Inside config.toml:

```
[params]
customCss = ["css/custom.css", "css/styles.css"]
```

In your /hugo-blog folder, add a folder 'assets'

In /hugo-blog/assets add a folder 'css'

In /hug-blog/assets/css create two files: custom.css and styles.css

Inside customer.css:

```
.sidebar .logo-title {
    text-align: center;
    padding-top: 240px;
    flex: 1;
}
```

To move the profile picture and the favicons up, give padding-top a value of say, 120px.

That should solve the problem.

