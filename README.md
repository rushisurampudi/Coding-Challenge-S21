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

## Solution
The solution that I tried to go about is to use the CGView library. This tool is already developed as a server to be used on the web and it is also an application for local use but the CGView API can be used to implement map visualization on other java applications. This would work perfectly to create a circular genome map of the Tomato Curly Stunt Virus because this tool takes the genbank format and can convert it into a map and into .png format. I attempted to do this on my machine but unfortunately faced issues with my IDE that I could not solve and couldn’t implement the solution. However, I don’t see why this solution wouldn’t work had I gotten the chance to do it. Since I couldn’t do that, I looked into other solutions for this and found that tools like Circos, GenomeVx and Circleator would do the job as well. I have attached the result from GenomeVx here. 


![GenomeVx-1](https://user-images.githubusercontent.com/71059181/105647366-02161000-5e5a-11eb-97ff-7174126acce0.png)
