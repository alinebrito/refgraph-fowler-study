# Understanding Refactoring Tasks over Time: A Study Using Refactoring Graphs

__Summary:__ Refactoring is a fundamental practice in modern software development. Therefore, it is essential that practitioners have a solid understanding of refactoring, both in theory and in practice. In this paper, we
rely on a graph-based abstraction---called refactoring graphs---to understand, visualize and analyze refactorings performed by students in a canonical refactoring application: the Video Store System, proposed by Fowler. We asked 46 students to perform the refactorings included in this example under two scenarios: according to a list of explicit and well-defined guidelines and using flexible and more open guidelines. 
By using a graph distance metric automatically computed over refactoring graphs, we find that, for explicit guidelines, most students performed the refactoring tasks successfully. On the other hand, when following flexible ones, a significant part of the students faced problems to identify the appropriate operations.

__Dataset:__ The
refactoring operations performed by the students (and our analysis) are publicly
available at: [alinebrito.github.io/refgraph-fowler-study](https://alinebrito.github.io/refgraph-fowler-study).

## Class Diagram

Initial class diagram of the  Video Store System:

<img src="img/diagram-initial-version.svg" width="400" style="">

Final version after applying the refactorings:

<img src="img/diagram-final-version.svg" width="500" style="">