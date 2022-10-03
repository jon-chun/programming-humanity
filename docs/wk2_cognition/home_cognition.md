![Algorithmic Gears](./images/malcolm-lightbody-401OD83Ke6o-unsplash_algorithms_gears.jpg)

# Cognition

![Algorithmic Flowchart](./images/cognition_good_code.png)


Last week we explored the many facets of data. This week, we look at algorithms and how we can process that data. We begin by exploring the long history of attempts to describe, systematize and automate cognition. The origins of computer science can be said to date back to Aristotle, and the field has been heavily influenced by math, logic and linguistics. You may also be surprised to learn how influential philosophers have been to the field.

Once again we'll compare human information processing with computers. Can algorithms and AI help us understand how we think and even, perhaps, the nature of consciousness? As the best example of self-aware and intelligent matter in the Universe, the human mind is the natural yardstick for all other computational, cognitive and conscious systems.

In terms of code, we'll learn how Computer Science represents and implements one familiar aspect of cognition: explicit algorithmic thinking. One of the best ways to learn how to code is to begin with "pseudo-code"--crafting an algorithm using informal language before we express it in a programming language like Python. We'll also study specific popular algorithms for common tasks (e.g. sort and search) as well as general patterns of computation (e.g. iteration and recursion). 

We close the week by focusing on the one aspect of human cognition that is still a mystery: consciousness. Can consciousness be explained mathematically, materially, or spiritually? While theories of consciousness used to be the domain of religion and philosophy, we now have physicists, computer scientists, and neuroscientists joining the debate. Is consciousness a fundamental property of the universe like information, matter and energy? A material process of our biology? A mathematical formula? A way of integrating information? Our conclusion has implications for whether we will be able to replicate consciousness in our machines. Of course, the larger question is undoubtedly: should we even try?

In DataCamp, we finish the course (units 2, 3, and 4) Introduction to Data Science with Python. While this course would fit better with next week's focus on output and visualization, we have found it a gentle introduction to programming. Don't worry, in later weeks, we will do a deeper dive into Python programming, as well as hone these skills in data visualization!


## **Monday: Intellectual History**

- [How Aristotle Invented the Computer](https://www.theatlantic.com/technology/archive/2017/03/aristotle-computer/518697/), Chris Dixon, The Atlantic, Mar 2017 (History of IDEAS approach)
- [The History of Computing](https://www.youtube.com/watch?v=-M6lANfzFsM), (13:41) Futurology - An Optimistic Future, Sept 2017 (History of Material Advances)
- [Why Your Brain is Not a Computer](https://www.theguardian.com/science/2020/feb/27/why-your-brain-is-not-a-computer-neuroscience-neural-networks-consciousness) Matthew Cobb, TheGuardian.com, Feb 2020
- [Theory of Mind Through the Lens of Algorithms](https://www.youtube.com/watch?v=a19lSbFPRqY), (12:18) Andrea Diaconescu, TEDxZurich, Nov 2014
- [The Halting Problem](https://www.youtube.com/watch?v=t37GQgUPa6k) (up to 6:00) Up and Atom, Jul 2018 (We will go over in class, do your best to understand)
- DataCamp, [Introduction to Data Science with Python](https://campus.datacamp.com/courses/introduction-to-data-science-in-python)
    * Chapter 2, Loading Data in Pandas
    * (If you're having trouble, go back and watch the videos again--they usually give you the exact code you'll need for the exercise.)
- Test Your Understanding
    * There are a few key concepts from the history of computing we'll go over in class: decidability and completeness (this can be hard to grasp), Moore's Law, high-level and low-level programming languages, and the differences between the hardware (i.e. electrical relay, vacuum tube, transistor). Focus on the surprising extent to which language and logic are key and how it is implemented using Boolean logic. In DataCamp, you'll use Boolean logical expressions!
    * Today you have readings/videos about the brain that make somewhat opposing arguments. What is the debate? 
    * DataCamp terms--creating DataFrames with pandas. Useful grammar/vocab we will use in class today:
      * syntax: pd.read_csv('filename.csv')
      * csv--comma separated values (a type of stored data)
      * methods follow a dot and are different form a function because they are "attached" to an object. For example df.head() and df.info() are ways to inspect a DataFrame. Head and info are methods "attached" with a dot to df--the dataframe!
      * rows versus columns. There are 2 ways to select columns (When do you HAVE to use brackets **versus** dot notation?). We select rows differently, with logical statements (note the introduction of a Boolean as a data type); also notice that the logical statement references columns, since you will be selecting ROWs based on which rows have certain column values--this can be confusing!) We'll practice all of this in class.

## **Wednesday: Algorithms & Recursion**

- [What is an Algorithm and Why Should You Care?](https://www.khanacademy.org/computing/computer-science/algorithms/intro-to-algorithms/v/what-are-algorithms) (5:27) Khan Academy
- [Binary Search (A Guessing Game)](https://www.khanacademy.org/computing/computer-science/algorithms/intro-to-algorithms/a/a-guessing-game) Khan Academy
- [Introduction to Algorithms](https://www.youtube.com/watch?v=gcQMBK53UjI) (25:00) Joseph Dugan, Mar 2017
- [Comparing Recursion: Thought, Code, Language](http://assets.press.princeton.edu/chapters/s9424.pdf) 
- [Python: Recursion Explained](https://www.youtube.com/watch?v=wMNrSM5RFMc) (8:44) Joe James, Nov 2017
- DataCamp, [Introduction to Data Science with Python](https://campus.datacamp.com/courses/introduction-to-data-science-in-python)
    * Chapter 3: Plotting Data with Matplotlib
- Test Your Understanding
    * What is an algorithm, and what are some examples (binary, linear)
    * What is the difference between iteration and recursion? How does recursion offer a way of explaining human thought?
    * DataCamp: functions: plt.plot(x, y, label = "label") plt.show() plt.xlabel("label") plt.ylabel("label") plt.title("title") plt.legend() plt.text(xcoord, ycoord, "text")
    * keywords fontsize =25  and color = "green"

## **Friday: Consciousness**

- [Consciousness is a Mathematical Pattern](https://www.youtube.com/watch?v=GzCvlFRISIM), (16:30) Max Tegmark (Physicist), Jun 2016 (good)
- [What is Consciousness?](https://www.youtube.com/watch?v=pnsgI4qllkY) (7:00) David Chalmers (Philosopher) Nov 2020
- [The Hard Problem of Consciousness](https://www.youtube.com/watch?v=ZKoowV2i--U) (6:00) Donald Hoffman (Cognitive Psychologist), Sep 2019
- [We exist inside the story that the brain tells itself](https://www.youtube.com/watch?v=tyrPMVMb-Uw&list=RDLVTvoIpLlwf8k&start_radio=1&rv=TvoIpLlwf8k), (25:05) Joscha Bach (AI Engineer) Jun 2020 (CHALLENGING concepts)
- DataCamp, [Introduction to Data Science with Python](https://campus.datacamp.com/courses/introduction-to-data-science-in-python)
    * Chapter 4: Different Types of Plots
- Test Your Understanding
    * What are traditional ways of understanding consciousness, esp. materialism, idealism, and dualism? Why is consciousness a "hard problem"?
    * What are panpsychism and integrated information theory? How are they similar? How might they be different? 
    * Why does Joscha Bach suggest consciousness is a simulation?
    * DataCamp vocab/grammar: plt.scatter(x, y, color=, marker =, alpha=) plt.bar (only need to label y), yerr plt.barh, stacked bar chart (bottom=) plt.hist(df, bins = or range=(x,y) or density=True

## **In-Class Demos:**

- Pandas: [FBI Police Shootings](https://colab.research.google.com/drive/1WjVj8oceV48LCJHEneGhrCQDxDUsHB4F?usp=sharing)
- Kaggle: [Global Human Traffic EDA](https://www.kaggle.com/viktorpolevoi/global-human-trafficking-eda) and [World Slavery and Nepal Trafficking Analysis](https://www.kaggle.com/milan400/world-slavery-and-nepal-trafficking-analysis)
- VisuAlgo: [Bubble Sort](https://visualgo.net/en/sorting)

![](https://programminghumanity.files.wordpress.com/2020/01/cartoon_robot_love_algo.png?w=552)