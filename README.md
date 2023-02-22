# my_references


### chatGPT commands
#### fastDDS recorder
I need design a FastDDS data recorder implementation in c++, with the following requirements:
1. An XML configuration file should specify important parameters such as the file name, chunk size, maximum number of chunks, etc..
2. The data recorder should discover all existing messages types currently available in the FastDDS domain using the FastDDS discovery mechanism, and then capture them into a binary file format.
3. There should be no limit on the number of samples that can be recorded.
4. The binary file format should allow for easy serialization and deserialization of data.
5. Use chunking mechanism to optimize disk I/O and memory usage. 
6. The code should base on fastDDS version 2.9.1.

Can you show me the overall design approach, the list of source files, and the member functions that each source file will implement? Please keep your answer consistent.

please show me the full content of the above source files; ignore the word count limit while displaying.

#### fastDDS replayer:
The data replay should read the recorded data from the binary file and publish it on a FastDDS topic.
The replay should be able to handle multiple types of data.
The replay should use a configurable time interval to publish data at a specific rate.
The replay should be able to handle replaying large amounts of data at high speeds.

### classic Deep Learning e-book, with slides and codes
https://www.deeplearningbook.org/lecture_slides.html

### online course, Stanford CS231n
http://cs231n.stanford.edu/

### Machine learning website, including good material on LSTM 
https://machinelearningmastery.com/start-here/
