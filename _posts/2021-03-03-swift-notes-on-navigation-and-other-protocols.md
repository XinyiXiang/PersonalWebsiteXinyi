---
title: Swift Notes on Navigation and Other Protocols
commentable: true
Edit: 2021-03-03
mathjax: true
mermaid: true
tags: Swift SwiftUI protocols
categories: technical
description: This is my final draft for an Appreciation of Architecture course, for which I focused my comparative studies between iconic Renaissance architectures and buildings established during industrial revolution.
---

You cannot put two alerts with isPresented in the same View.

@StateObject conforms to @ObservableObject protocol automatically. You could either pass the state object into a property with ObservedObject attribute or alternatively add using the .environmentObject(:_) modifier.

When separating the leading and trailing items in the NavigationBarItems, use commas.

The place of the .environment matters because you need to include whatever you send it to, otherwise it wouldn’t know what to modify.


<img src="https://raw.githubusercontent.com/xinyixiang/xinyixiang.github.io/master/_posts/2021-03-03-swift-notes-on-navigation-and-other-protocols/code.png" width="80%">