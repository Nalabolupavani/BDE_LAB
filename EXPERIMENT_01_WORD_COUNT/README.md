Experiment 1 – Word Count using MapReduce
Aim

To implement a Word Count program using Hadoop MapReduce.

Objective

To understand the working of the MapReduce programming model by counting the frequency of words in a given input file.

Technologies Used
Java
Hadoop
MapReduce
HDFS
Files
File	Description
src/WordCount.java	Java source code for the Word Count MapReduce program
input/file.txt	Input text file used for the experiment
Working

The Word Count program uses Hadoop MapReduce to calculate the frequency of each word in the input file.

Mapper

The Mapper reads the input text and generates intermediate key-value pairs in the following form:

(word, 1)

Reducer

The Reducer receives all values associated with each word and calculates their total frequency.

For example:

hello → 2
world → 3

Execution

The Java program can be compiled and executed using the Hadoop MapReduce framework.

The input file is provided to the Hadoop environment, and the MapReduce job processes the data to generate the word frequencies.

Result

The Word Count program was successfully implemented using Hadoop MapReduce.