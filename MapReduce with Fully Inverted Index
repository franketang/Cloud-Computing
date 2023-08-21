README: https://docs.google.com/presentation/d/1jhv7ArriMIsu2nh6iFLSy5umvUZypNUq/edit#slide=id.p12

This repository has a Java program that creates a detailed list (known as an inverted index) using the MapReduce method. The program looks at a group of text files and produces a list. This list shows each distinct word from the text files and tells us which files mention that word.

The inverted index is a commonly used list in systems that search for information. It quickly finds documents based on the words inside them. Our program uses MapReduce to make this list for a group of text files.

The program uses the MapReduce method, which has two steps: "Map" and "Reduce".

For example, with 3 files:

file0: it is what it is

file1: what is it

file2: it is a banana




![Image](https://user-images.githubusercontent.com/29631514/261885641-1020ad7d-9111-4b41-9079-8a9b9b76dcff.png)


Setting Up

Go to the project folder: cd repository-name.
Set up the necessary files:
Make folders: index > input.
Add texts to files:
file0: "it is what it is"
file1: "what is it"
file2: "it is a banana"
Running the Program

Go back to the Hadoop directory: cd hadoop-3.3.5.
Prepare and start Hadoop.
Create required directories in HDFS and upload the input files.
Compile the program and create a JAR file.
Run the MapReduce job.


Testing

You can test with your own files or change the existing ones. Just keep them in index/input.
Post run, view the part-r-00000 file in /user/username/index/output to see the inverted index created.
The result looks like: "output".
Review and ensure the inverted index works as expected.
