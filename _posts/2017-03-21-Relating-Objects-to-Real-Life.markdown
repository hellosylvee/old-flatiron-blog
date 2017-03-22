---
layout: post
title:  "Relating Objects to Real Life"
date:   2017-03-21 23:05:55 -0400
categories: jekyll update
---
![](https://68.media.tumblr.com/6a466313b27bb7c6cb30a3e39c6ebc99/tumblr_o28zvvhCgh1r0klrdo1_500.gif)
<br>
## Day 2

## What is Ruby?
Ruby is an Object Oriented Programming Language and has features that include data encapsulation, data abstraction, polymorphism, and inheritance. Besides those fancy words, the program is fundamentally composed of classes and objects. Now what are those - what is a class and what is an object? And why is Ruby a language of classes and objects?

Just a quick background story, the Ruby language was designed and developed in the mid-1990s by a developer named Yukihiro Matsumoto or  "Matz". He created this language to be easy and friendly for people to learn programming by designing it to imitate real life. There are many objects in real life - objects made, objects destroyed, objects that you're holding in your hand like your smartphone. Like there are objects in this world, there are also objects in the world of Ruby.

Along with objects, there are classes in Ruby. What are they and what is the relation to objects? Classes are like blueprints from which individual objects are created. Most often, you'll here Rubyists say the word "instance" of a class. What is that? Let's take a look at a file on your desktop, and think of that as a class. Then press `Command V` + `Command C`, and...voila! You just created a copy of the original file - you created an instance of the class. And you can also do that in Ruby!

<br>
## World of Objects
We have a Cat class with a class method that returns a string "purrrrrrrrr".

{% highlight ruby %}
class Cat
  def purr
    "purrrrrrrrr"
  end
end
pusheen = Cat.new
#=> #<Cat:0x007fdf8e082c38>
{% endhighlight %}

Pretty neat, eh? Now let's create some objects in Ruby by using the method new of the class.

{% highlight ruby %}
class Cat
  def purr
    "purrrrrrrrr"
  end
end
pusheen = Cat.new
#=> #<Cat:0x007fdf8e082c38>
pusheen
#=> #<Cat:0x007fdf8e082c38>
pusheen.purr
#=> "purrrrrrr"
{% endhighlight %}

What in the (ruby) world? Okay, let's take a look here. We created a new instance

![alt text][Instances of Cats]

{% highlight ruby %}
class Cat
  def purr
    "purrrrrrrrr"
  end
end
pusheen = Cat.new
#=> #<Cat:0x007fdf8e082c38>
pusheen
#=> #<Cat:0x007fdf8e082c38>
pusheen.purr
#=> "purrrrrrr"
{% endhighlight %}

# BLOG IN PROGRESS


[Instances of Cats]: https://s-media-cache-ak0.pinimg.com/736x/84/a5/44/84a5445465b4a963a9e0a4466b892765.jpg "Instances of Cats"

<!-- Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->
