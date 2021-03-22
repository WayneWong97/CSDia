# CSDia

CSDia(Computer Science Diagrams) dataset is a diagram dataset from Computer Science courses. It contains a total of 1,294 diagrams in 12 categories from five undergraduate courses: *Data structure*, *Principles of Computer Networks*, *Computer Architecture*, *Digital Logic Circuit*, and *Computer Operating System*. 

## Simple Statistic

On the whole, CSDia contains annotations of more than 11,000 objects and 5,600 relations. As shown in the Table, each category of the dataset is unbalanced, ranging from 71 to 150 per class. We split diagrams into 951 for training sets and 343 for test sets.

|     Category     | Diagrams | Objects | Relations |
| :--------------: | :------: | :-----: | :-------: |
|    Array list    |   100    |   583   |    468    |
|   Linked list    |    74    |   626   |    375    |
|   Binary tree    |   150    |  1323   |    590    |
| Non-Binary tree  |   150    |  1489   |    651    |
|      Queue       |   150    |  1261   |    444    |
|      Stack       |   150    |   540   |    403    |
|  Directed graph  |    71    |   695   |    377    |
| Undirected graph |    79    |   828   |    437    |
|     Deadlock     |   100    |   840   |    423    |
|    Flow chart    |   100    |   985   |    458    |
|  Logic circuit   |    70    |   913   |    432    |
| Network topology |   100    |  1593   |    517    |
|      Total       |   1294   |  11776  |   5675    |

## Annotation

We put the annotation files of each category independently in a file with the same name as the category. The following uses *binary tree* as the example to illustrate the content of the annnotation:

Each diagram has global labeling information, including: filename, size, file_attributres(source, class, caption). Further information about objects and relations in the diagram, each object has: shape_attrbutes(x, y, width, height)、region_attrbites(id, obj_label, description). Each relation has: shape_attrbutes(x, y, width, height)、region_attrbites(id, logic_label, relationship). 

It should be noted that the relation in the diagram is to mark logical symbols such as arrows and lines. To distinguish between relations and objects, you need to specify in "Type: object" or "Type: logical symbol".

## QA

We selected the diagrams in *Queue* category to annotate the relevant question and answer as a preliminary attempt. Each diagram corresponds to a ".txt" file with the same name. Each file contains six questions, questions 1-4 are one-step reasoning questions, and 5-6 are two-step reasoning questions. The six questions include one out of four questions and true or false questions in half. The correct answer is in the last line of the file.

## Version

1.0 (March, 2021)

## Contact

Shaowei Wang(wang97@stu.xjtu.edu.cn)



License for Non-Commercial Use





 

