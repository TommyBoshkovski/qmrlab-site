---
layout: post
title:  "Quick Start Guide"
author: sal
categories: [ Jekyll, tutorial ]
image: assets/images/12.jpg
featured: true
hidden: true
---

You want to run interactive jupyter notebooks in a blog post? It's never been easier. 
 
Here is an example:

<pre data-executable="true" data-language="python">print("Hello!")</pre>
<pre data-executable="true" data-language="python">1+1</pre>
<pre data-executable="true" data-language="python">
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt
x = np.linspace(0,10)
plt.plot(x, np.sin(x))
plt.plot(x, np.cos(x))
</pre>