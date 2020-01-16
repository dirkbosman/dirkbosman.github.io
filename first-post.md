

```python
#!pip install nbconvert
!jupyter nbconvert --to MARKDOWN first-post.ipynb
```

    [NbConvertApp] Converting notebook first-post.ipynb to MARKDOWN
    [NbConvertApp] Support files will be in first-post_files/
    [NbConvertApp] Making directory first-post_files
    [NbConvertApp] Writing 3941 bytes to first-post.md


- title: This is the Best Tool so far
- date: 2019-06-21 12:00
- category: tools
- tags: tool, software, best
- slug: best-tool
- authors: Jon Doe
- summary: This is the most important tool out there

# First post!

This will be the first post in our new Pelican blog! You can add any code or markdown cells to this Jupyter notebook, and they will be rendered on your blog.


```python
import random

random.randint(0,100)
```




    4




```python
import matplotlib.pyplot as plt

%matplotlib inline

plt.hist([10,5,7,10,1,1,2,3,5])
```




    (array([ 2.,  1.,  1.,  0.,  2.,  0.,  1.,  0.,  0.,  2.]),
     array([  1. ,   1.9,   2.8,   3.7,   4.6,   5.5,   6.4,   7.3,   8.2,
              9.1,  10. ]),
     <a list of 10 Patch objects>)




![png](first-post_files/first-post_4_1.png)



```python

```
