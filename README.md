# ACM Research Coding Challenge (Spring 2021)

## No Collaboration Policy

**You may not collaborate with anyone on this challenge.** You _are_ allowed to use Internet documentation. If you _do_ use existing code (either from Github, Stack Overflow, or other sources), **please cite your sources in the README**.

## Submission Procedure

Please follow the below instructions on how to submit your answers.

1. Create a **public** fork of this repo and name it `ACM-Research-Coding-Challenge-S21`. To fork this repo, click the button on the top right and click the "Fork" button.
2. Clone the fork of the repo to your computer using `git clone [the URL of your clone]`. You may need to install Git for this (Google it).
3. Complete the Challenge based on the instructions below.
4. Submit your solution by filling out this [form](https://acmutd.typeform.com/to/uqAJNXUe).

## Question One

Genome analysis is the identification of genomic features such as gene expression or DNA sequences in an individual's genetic makeup. A genbank file (.gb) format contains information about an individual's DNA sequence. The following dataset in `Genome.gb` contains a complete genome sequence of Tomato Curly Stunt Virus. 

**With this file, create a circular genome map and output it as a JPG/PNG/JPEG format.** We're not looking for any complex maps, just be sure to highlight the features and their labels.

**You may use any programming language you feel most comfortable. We recommend Python because it is the easiest to implement. You're allowed to use any library you want to implement this**, just document which ones you used in this README file. Try to complete this as soon as possible.

Regardless if you can or cannot answer the question, provide a short explanation of how you got your solution or how you think it can be solved in your README.md file. However, we highly recommend giving the challenge a try, you just might learn something new!

I have submitted my research project by including the PNG file of the Circular Genome Diagram and the main.py file for my code that I used to construct the diagram from the Genbank file.
I solved this problem by researching packages of Python that would help in the process for making the circular genome diagram. I eventually came across this tool called BioPython which helps to model genetic graphs and models mainly in the field of biology. Although I am not a biologist, I believe that when dealing with issues such as this, it is recommended to research a little bit about this field before solving the problem. Regardless, I found tools in BioPython that are designed specifically for creating GenomeDiagram and for creating charts. The URL where I received the most help and found existing code for my project would be: https://biopython-cn.readthedocs.io/zh_CN/latest/en/chr17.html 
That website deserves a lot of credit for its ability to explain the process and the structure of the code itself, and I was able to do this project mainly due to that website's guidance and support. 
