---
layout: default
title: ""
published: true
data:
  x: 50
  y: 2250
  z: -1000
  rotate: -20
---

# Functors #

The *map* operation

{% highlight scala %}
trait Functor[F[_]] {
  def map[A,B](a: F[A])(f: A => B): F[B]
}
{% endhighlight %}