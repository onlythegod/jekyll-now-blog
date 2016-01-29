---
layout: post
title: first note
---

### UML diagrams
{% highlight c %}
void main(){
	int a = 3;
}
{% endhighlight %}
You can also render sequence diagrams like this:


{% plantuml %}
Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response
Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
{% endplantuml %}


