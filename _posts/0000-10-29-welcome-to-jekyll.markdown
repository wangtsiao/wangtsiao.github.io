---
layout: post
title:  "Jeykll使用方法"
date:   0000-10-29 20:16:31 +0800
categories: jekyll update
---
<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

Jeykll默认支持代码块，如下：
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

{% highlight python %}
def print_hello(name):
  print(f"Hello {name}")

print_hello("python")

{% endhighlight %}


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

是否支持数学公式：
```
$$
i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1
$$
```
显示：
$$
i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1
$$

那么
```
$ i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1 $
```

显示：
$ i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1 $
看来并不支持。

如何让它显示单行公式呢：
试试这个
```
\\
$$
i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1
$$
```

\\
$$
i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1
$$

# 标题1

## 标题2

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
