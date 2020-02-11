# Fancy-python
This repo is based on my articles [How to be fancy with Python](https://towardsdatascience.com/how-to-be-fancy-with-python-8e4c53f47789) and [How to be fancy with OOP in Python](https://towardsdatascience.com/how-to-be-fancy-with-python-part-2-70fab0a3e492). It includes small Python tricks that will make your life much much easier. I hope they also help you become a better Python programmer. It is available as a jupyter notebook so you can clone and run it yourself. Also, if you know some tricks of your own, submit a pull request and I'll be more than happy to include it.

### -1. Keyboard shortcuts

`TAB` to indent code

`SHIFT + TAB` to unindent code

To comment a bunch of code, select it and press `CONTROL + /`

To surround something with quotation marks or brackets around something, press `SHIFT + "` or `SHIFT + (`

### 0. Zip, enumerate

Usually in Python, we loop over things like this:

![Comprehensions 1](https://github.com/dipam7/Fancy-python/blob/master/images/comprehensions_1.png)

To do the same with multiple lists, use zip

![Comprehensions 2](https://github.com/dipam7/Fancy-python/blob/master/images/comprehensions_2.png)

And if you need indexes by any chance you can just do

![Comprehensions 3](https://github.com/dipam7/Fancy-python/blob/master/images/comprehensions_3.png)

### 1. Comprehensions

The best part about Python is that you can accomplish so much in so less code. Take list comprehensions for example. If you want to create a list of numbers in a certain range you can easily do it as follows:

![Comprehensions 4](https://github.com/dipam7/Fancy-python/blob/master/images/comprehensions_4.png)


You can also apply conditions on it very easily.


![Comprehensions 5](https://github.com/dipam7/Fancy-python/blob/master/images/comprehensions_5.png)

One practical example of this is to convert a number to its digits.

![Comprehensions_6](https://github.com/dipam7/Fancy-python/blob/master/images/comprehensions_6.png)

This concept of applying a function to every element of the list reminds me of map

![Comprehensions_7](https://github.com/dipam7/Fancy-python/blob/master/images/comprehensions_7.png)

Just like lists, there are comprehensions for dictionaries and generators as well. We'll talk about generators later.

Let's start with dictionaries. First let's learn about something called `operator.itemgetter`

Say you have a list of lists like this

![Dict_comp_1](https://github.com/dipam7/Fancy-python/blob/master/images/dict_comp_1.png)

and you want to get the first element of every list from the inner lists. You can do so as follows

![Dict_comp_2](https://github.com/dipam7/Fancy-python/blob/master/images/dict_comp_2.png)

Cool right?

Let me give you one more example. You can use it with the `key` argument in the sorted function.

![Dict_comp_3](https://github.com/dipam7/Fancy-python/blob/master/images/dict_comp_3.png)

See how it works?

