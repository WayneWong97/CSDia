The "split.json"  records the dataset split of the experiment in the paper "RL-CSDia: Representation Learning of Computer Science Diagrams".  Because the diagrams in the paper need to be processed by OCR, some diagrams with insufficient text are filtered in the split method.

If you need to try on QA task, the recommended data split  is:

* Using the diagrams starting with the numbers 3, 4, and 7 as the val set.
* Using the diagrams starting with the numbers 6, and 9 as the test set.
* Using the remaining diagrams as the training set.