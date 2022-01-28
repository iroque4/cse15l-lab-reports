# Lab Report 2

## Fix #1

![image](CodeDiff1.png)

[1st failure-inducing input](https://github.com/iroque4/markdown-parse/blob/main/test-file2.md)

![image](InfiniteLoop.png)

The failure-inducing file, test-file2.md did not contain an open parentheses after the second link. My code had a bug where conditional statement is continuously satisfied. As a symptom, our code enters an infinite loop.

## Fix #2

![image](CodeDiff2.png)

[2nd failure-inducing input](https://github.com/iroque4/markdown-parse/blob/main/test-file4.md)

![image](WrongOutput.png)

The failure inducing file, test-file4.md, contained an image instead of a link. However, our code had a bug where it would interpret the image as a link, and a our symptom was an incorrect printed link.

## Fix #3

![image](CodeDiff3.png)

[3rd failure-inducing input](https://github.com/iroque4/markdown-parse/blob/main/test-file3.md)

![image](WrongOutput2.png)

The failure-inducing file, test-file3.md did not contain a link since the brackets were separated from the parentheses. However, my code had a bug where it would interpret it as a link. As a symptom, my code printed the wrong output.

