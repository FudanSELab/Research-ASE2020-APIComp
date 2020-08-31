# Examples of Answer Points

1. From the Stack Overflow answer [Difference between CopyOnWriteArrayList and synchronizedList](https://stackoverflow.com/questions/28979488/difference-between-copyonwritearraylist-and-synchronizedlist), We extract 3 answer points: "CopyOnWriteArrayList uses ReentrantLock.","CopyOnWriteArrayList creates a backup copy of the data.", "CopyOnWriteArrayList updates underlying volatile array reference only  via setArray.", from the sentence "CopyOnWriteArrayList uses ReentrantLock and creates a backup copy of the data and the underlying volatile array reference is only updated via setArray".

2. From the Stack Overflow answer [Difference between Java's Vector.add() and Vector.addElement()?](https://stackoverflow.com/questions/3089969/difference-between-javas-vector-add-and-vector-addelement), We extract 2 answer points: "The addElement() method is synchronized.","The add() method is not synchronized.", from the sentence "addElement() is synchronized. add() isn't.".

3. From the Stack Overflow answer [What is the difference between a JFrame and a JDialog?](https://stackoverflow.com/questions/5552833/what-is-the-difference-between-a-jframe-and-a-jdialog), We extract 2 answer points: "JFrame inherit from Window","JDialog inherit from Window", from the sentence "But both inherit from Window, so they share much functionality.".

For all answer point results, you can view the [file](https://github.com/FudanSELab/Research-ASE2020-APIComp/blob/master/question_select/answer_point.xlsx)
