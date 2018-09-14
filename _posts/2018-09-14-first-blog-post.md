---
layout: post
title: Python List
---
<body style="background-color:MediumSeaGreen;">
<p style="color:blue;"> What is a list? .</p>

We all know what a list is. We probably make lists everyday -  grocery shopping list, to do list, emails, song playlists, etc. I cannot imagine going into a grocery store without a shopping list.  I would scratch my head standing in front aisles of products without a list. Lists are fundamental on our daily life.

![images]({{ site.baseurl }}/images/shopping list.png)

[source](https://www.flyintotheworld.com/dr-oz-10-day-belly-slimdown-plan-alcohol-salty-food/dr-oz-10-day-belly-slimdown-plan-alcohol-salty-food-1/)

<p style="color:red;"> So what is a list in Python? .</p>

Just like a shopping list, a list in Python is a grouping of comma-separated items between square brackets `[]`. Now let us create a grocery shopping list.

![images]({{ site.baseurl }}/images/created a shopping list.png)

Creating a list just is as simple as putting items in square brackets. Let us create more lists.  

![images]({{ site.baseurl }}/images/created two more lists.png)

The list is a very flexible datatype available in Python. When we print out the list (see number_list), the output looks exactly like the list we created. So lists in Python are ordered. Now let’s give a Python list a better definition: A list is an ordered sequence of items.

<p style="color:purple;"> What lists in Python can do? .</p>

Well, let’s think about our shopping list for a second. In order to make enough time for grocery shopping, I need to know how many items are there in my list. How do we do it? Do we put our figure on the computer screen and count each item in the list? No! We just simply type `len(List Name)`, and we get the answer of 8. 

![images]({{ site.baseurl }}/images/len command.png)

In Python, each item in a list is given an index number, starting 0. In this way, we are able to access items individually.

![images]({{ site.baseurl }}/images/index table.png)

Now we can call any item of the shopping list by referring to its index number. 

![images]({{ site.baseurl }}/images/called index 0 and 7.png)

What if I want to add chocolate to my shopping list? Do I have to make a new list with chocolate added? No. We just need to `append` the new item (chocolate) to our existing shopping list.

![images]({{ site.baseurl }}/images/append chocolate.png)

Now we have 9 items on our list and the last item is chocolate. 

What if I want to combine my grocery shopping list and my beauty shopping list? What should I do? Is there a way of doing it in Python? The answer is yes. We can simply use `+` operator to achieve our goal.

![images]({{ site.baseurl }}/images/combined list.png)

Now my beauty items “lipstick” and “mascara” are added to my shopping list and a new list “combined_shopping_list” is created when we combined these two lists. Actually, there is another way to do it. Instead of creating a new combined list, we can just add the 2nd list to our 1st list and keep the name of the 1st list.

![images]({{ site.baseurl }}/images/new shopping list.png)

Lists also respond to `*` operator. For example, if we need to create a list like [3,3,3,3,3,3,3,3,3,3]. How do we do it? Type “3” 10 times? No. there is a simple way to do it in Python. 

![images]({{ site.baseurl }}/images/repeat.png)

Imagine how much time we would save if we need to repeat some items 100 times, 1000 times, 10,000 times!


If we want to delete a specific list item, then we can use del statement. Say, I don’t need to buy lipstick this time.  Let us delete lipstick from the list.


</body>
