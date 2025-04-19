# CS300-Pseudocode
To get this solution, whatsapp: +254794689731

# CS 300 Pseudocode Document

## Example Function Signatures

Below is an example of a function signature that you can use as a guide to help address the program requirements using each data structure for the milestones. The pseudocode for finding and printing course information is also given below and depicted in bold to help you get started. The provided pseudocode is for a vector data structure, so you may use this pseudocode in your first milestone as is. The hash table and tree structures are also shown below. But these structures are left for you to do in future milestones.

//Vector - Milestone 1

void searchCourse(Vector&lt;Course&gt; courses, String courseNumber) {

**for all courses**

**if the course is the same as courseNumber**

**print out the course information**

**for each prerequisite of the course**

**print the prerequisite course information**

}

//Hash Table - Milestone 2

void searchCourse(HashTable&lt;Course&gt; courses, String courseNumber) {

}

//Binary Search Tree – Milestone 3

void searchCourse(Tree&lt;Course&gt; courses, String courseNumber) {

## Example Runtime Analysis

When you are ready to analyze the runtime for the Project One data structures for which you created the pseudocode, use the example chart below to support your work. This particular example is for printing course information when using the vector data structure. As a reminder, this is the same pairing that was bolded in the pseudocode from the first part of this document. The example only covers the search function for the vector structure. You do not have to complete your runtime analysis until Project One. However, working on your analysis now may help you understand the changes as you complete the milestones. Don’t forget to include your charts in Project One. You will submit Project One in Module Six.

| **Code** | **Line Cost** | **\# Times Executes** | **Total Cost** |
| --- | --- | --- | --- |
| **for all courses** | 1   | n   | n   |
| --- | --- | --- | --- |
| **if the course is the same as courseNumber** | 1   | n   | n   |
| --- | --- | --- | --- |
| **for each prerequisite of the course** | 1   | 1   | 1   |
| --- | --- | --- | --- |
| **for each prerequisite of the course** | 1   | n   | n   |
| --- | --- | --- | --- |
| **print the prerequisite course information** | 1   | n   | n   |
| --- | --- | --- | --- |
| **Total Cost** |     |     | 4n + 1 |
| --- |     |     | --- | --- | --- |
| **Runtime** |     |     | O(n) |
| --- |     |     | --- | --- | --- |
To get this solution, whatsapp: +254794689731
