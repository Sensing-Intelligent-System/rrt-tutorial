## Tutorial for RRT

### Environment Setup:
This tutorial needs pygame and other python lib; most of them have installed in our vbi image but not pygame, let's install it



### Installation:
```
$ sudo pip install pygame
```

If you encounter error "Cannot import scipy.misc.imread", try: 
```
$ pip uninstall pillow
$ pip install pillow==6.1
$ pip install scipy==1.2.1
```
But make sure this won't affect your other project.

#### Task 1:
```
$ python rrt-pygame.py
```

#### Task 2:
```
$ python rrt-map.py
```
click a starting and end points on the map


### Reference:

The rrt-pygame code is written by Steve LaValle
http://msl.cs.illinois.edu/~lavalle/sub/rrt.py

The rrt-map code:
https://github.com/ArianJM/rapidly-exploring-random-trees
