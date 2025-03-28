---
layout: post
title: 'Programmatic UIKit with ObjC'
date: 2025-03-28 18:21:33 -0500
categories: uikit objc
---

Hi there! Most probably you will be thinking, why would I need to setup a new iOS project using UIKit when there is SwiftUI, and most of all, configured with Objective-C!

Well, the thing is that UIKit is far from dead, and you will encounter ObjC in the wild. Or you just wanna learn something new. Here, we are gonna setup a pretty basic UIKit project built from scratch with ObjC that will just show a `UIViewController`'s view background set to blue.

This is just a test.

And another test

And yet another

- One list
- Is something interesting

Now, this is something new

1. A
2. B
3. C

```swift
let test: String? = "This is just a test"

if let test = test {
    print(test)
}
```

```objc
UIViewController *viewController = [[UIViewController alloc] init]
```
