bubble
======

create dynamic maps using hyperlinks

scrape with beautiful soup to get link text, get pages for each link with [requests](http://docs.python-requests.org/en/latest/), use d3 to generate the node diagram

# possible d3 vizualizations:
* [Cluster Dendogram](http://bl.ocks.org/mbostock/4063570)
* [Radial Reingold–Tilford Tree](http://bl.ocks.org/mbostock/4063550)
* [d3.layout.tree](http://mbostock.github.io/d3/talk/20111018/tree.html)

# [pseudo]code

````
import sys
depth = sys.argv[1]

def makeNode():
    #uhhhhh    

for link in allLinks:
    print link.get_text()
    makeNode(link)
````
