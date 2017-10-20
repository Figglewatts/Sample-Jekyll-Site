---
layout: post
title: Code Snippets
tags: [ test, code ]

excerpt: Quick overview on how to post code snippets using Liquid tags and how to escape or not escape markdown and HTML in your blog entries. 

---

Whenever you need to post a code snippet, use the liquid tags `hilight` and `endhilight` like this:

```java
public static void main(string[] args) {
	// test
	System.out.println("Test test test");
}
```

```c++
class TestHighlight
{
private:
	int _testInt;
	float _testFloat;
public:
	TestHighlight(int i_test, float f_test)
		: _testInt(i_test), _testFloat(f_test);
};
```

Note that this only provides color-coding. For that you might need to use a front end colorization engine like Highlight.JS or something similar.
