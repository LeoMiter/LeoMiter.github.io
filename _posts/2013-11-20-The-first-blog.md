---
    layout: default
    title: 第一篇
---

{% include head.md %}

## 第一篇
1. 公元2013年11月20日，GitHub开博。
2. 当年的第一段代码，今天的第一篇博客。
{% highlight c %}
    #include <stdio.h>
    #include <stdlib.h>
    #include <string.h>

    int main(int argc, char **argv) {
        printf("hello,world\n");
        return 0;
    }
{% endhighlight %}

{{ page.date | date_to_string }}

{% include tail.md %}
{% include comment.html %}
