# Parallel_SVMs
The quantity of electronic data available for analysis has grown exponentially with the rapid development of the World Wide Web, the Internet of Things, and other digital technologies. As a result, data mining and machine learning algorithms face computational complexity issues when applied to real world datasets. Support Vector Machines (SVM) are powerful classifcation and regression tools but their computational requirements increase rapidly as the number of training examples increases. To address this problem, several parallel MapReduce based implementations of SVMs have been proposed. These implementation have in common that they decompose a large-scale multi-class problem to a number of relatively smaller subproblems by dividing the data into multiple partitions which can be processed in parallel; however, these approaches use different aggregation and combination strategies to form the final model.In this project, we implement three parallel SVM algorithms on the Hadoop implementation of MapReduce, using the LibSVM library for core SVM computations. We conduct a comprehensive investigation of the three algorithms in order to compare their generalization performance, accuracy, and training times.