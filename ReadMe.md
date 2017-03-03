# Tweet Generator: Data Structures & Probability with Python

## Course Schedule

**Course Dates:** Monday, January 23 – Friday, March 3, 2017 (6 weeks)

**Class Times:** Tuesday & Thursday 1–3pm (12 class sessions)


### Class 1: Tuesday, January 24

**Activity:**
- Discuss course goals and project focus
- Compare Python to other programming languages

**Tutorial:**
- Page 1: Let’s Get Started
- Page 2: Random Dictionary Words

**Objectives:**
- Create Python scripts and modules
- Access command-line arguments
- Read files and extract lines of text
- Strip whitespace from strings


### Class 2: Thursday, January 26

**Activity:**
- Compare code quality for list shuffling function
- Interactive code quiz on Python scripts and modules

**Tutorial:**
- Page 3: Analyze Word Frequency in Text

**Objectives:**
- Split strings into components to find words
- Build a histogram to count word occurrences


### Class 3: Tuesday, January 31

**Activity:**
- Compare code quality for getting random dictionary words

**Tutorial:**
- Page 4: Stochastic Sampling

**Objectives:**
- Sample words according to their observed frequencies
- Compare tradeoffs with different sampling techniques


### Class 4: Thursday, February 2

**Activity:**
- Compare tradeoffs of different histogram implementations
- Probability lecture and discussion

**Tutorial:**
- Page 5: Flask Web App

**Objectives:**
- Build Flask web app on your computer
- Deploy Flask app to Heroku server


### Class 5: Tuesday, February 7

**Activity:**
- Compare implementations for sampling words based on observed frequency

**Tutorial:**
- Page 6: Application Architecture (part 1)

**Objectives:**
- Plan application architecture to prepare for future expansion


### Class 6: Thursday, February 9

**Activity:**
- Compare code quality of functions based on length and responsibility
- Unpack list comprehensions into equivalent code and compare trade offs

**Tutorial:**
- Page 6: Application Architecture (part 2)

**Objectives:**
- Refactor histogram functions as class instance methods


### Class 7: Tuesday, February 14

**Activity:**
- Compare histogram functions and class instance methods
- Markov chains and random walks lecture and discussion

**Tutorial:**
- Page 7: Generating Sentences

**Objectives:**
- Build Markov chain based on observed frequency of adjacent words
- Generate sentence by sampling words using random walk through Markov chain


### Class 8: Thursday, February 16

**Activity:**
- Review Markov chains, how to generate one and sample sentences from it
- Arrays and linked lists lecture and discussion
- Act out how dynamic arrays and linked lists work

**Tutorial:**
- Page 8: Linked List

**Objectives:**
- Implement `LinkedList` class using [starter code](templates/linkedlist.py) and [unit tests](templates/test_linkedlist.py)

**Resources:**
- Watch Make School's [linked list lecture]
- Review Make School's [linked list slides]
- Play with Visualgo's [interactive animations of linked lists][visualgo list]
- Read Wikipedia's [dynamic array article] and [linked list article]

[dynamic array article]: https://en.wikipedia.org/wiki/Dynamic_array
[linked list article]: https://en.wikipedia.org/wiki/Linked_list
[linked list lecture]: https://www.youtube.com/watch?v=3WWuf4H61Nk
[linked list slides]: ArraysLinkedLists.pdf
[visualgo list]: https://visualgo.net/list


### Class 9: Tuesday, February 21

**Activity:**
- Draw diagram of how linked list data structure is stored in memory
- Compare similarities and differences in diagram representations
- Hash tables lecture and discussion

**Tutorial:**
- Page 9: Hash Table

**Objectives:**
- Implement `HashTable` class using [starter code](templates/hashtable.py) and [unit tests](templates/test_hashtable.py)

**Resources:**
- Watch Make School's [hash table lecture]
- Review Make School's [hash table slides]
- Read Wikipedia's [hash table article]

[hash table article]: https://en.wikipedia.org/wiki/Hash_table
[hash table lecture]: https://www.youtube.com/watch?v=nLWXJ6IDKmQ
[hash table slides]: HashTables.pdf


### Class 10: Thursday, February 23

**Activity:**
- Draw diagram of how hash table data structure is stored in memory
- Compare similarities and differences in diagram representations
- Algorithm analysis lecture and discussion

**Tutorial:**
- Page 10: Performance Analysis (stretch challenge)
- Page 12: Creating a Corpus (important to complete)

**Objectives:**
- Analyze your algorithms for best case and worst case time complexity
- Annotate `LinkedList` and `HashTable` methods with time complexity
    - See `LinkedList` [solutions](solutions/linkedlist.py) for examples: `items` and `find` methods
- Benchmark the actual performance of your `LinkedList` and `HashTable` data structures and the built-in `list` and `dict` types (optional stretch challenge)
- Collect a corpus of text from which to learn a Markov chain grammar model

**Resources:**
- Review Make School's [algorithm analysis slides]
- Read InterviewCake's [article on the idea behind big O notation][IC big O]
- Read StackOverflow's [plain English explanations of big O notation][SO big O]

[algorithm analysis slides]: AlgorithmAnalysis.pdf
[IC big O]: https://www.interviewcake.com/article/python/big-o-notation-time-and-space-complexity
[SO big O]: http://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation


### Class 11: Tuesday, February 28

**Activity:**
- Code review `HashTable` methods and analyze algorithm complexity
- Regular expressions lecture and discussion

**Tutorial:**
- Page 13: Parsing Text and Clean Up
- Page 14: Tokenization (stretch challenge)

**Objectives:**
- Use regular expressions to clean up and remove junk from your corpus
- Use regular expressions to create a more intelligent word tokenizer

**Resources:**
- Watch Make School's [regular expressions lecture]
- Review Make School's [regular expressions slides]
- Use Cheatography's [regular expressions cheat sheet] as a reference guide
- Solve interactive challenges in UBC's [regular expressions lab webpage][UBC regex lab]
- Use [RegExr] or [RegEx Pal] to build and test your regular expression patterns
- Use [RegExper] to visualize a diagram of your regular expression patterns
- Read StackOverflow answers to questions about using regular expressions to parse HTML: first [some comedic relief][SO match HTML tags] and then [an explanation of why you shouldn't][SO why not HTML]

[regular expressions lecture]: https://www.youtube.com/watch?v=roUtBDH3Obc
[regular expressions slides]: RegularExpressions.pdf
[regular expressions cheat sheet]: https://www.cheatography.com/davechild/cheat-sheets/regular-expressions/
[UBC regex lab]: http://www.ugrad.cs.ubc.ca/~cs121/2015W1/Labs/Lab8/lab8.html
[RegExr]: http://www.regexr.com/
[RegEx Pal]: http://www.regexpal.com/
[RegExper]: https://regexper.com/
[SO match HTML tags]: http://stackoverflow.com/questions/1732348/regex-match-open-tags-except-xhtml-self-contained-tags
[SO why not HTML]: http://stackoverflow.com/questions/590747/using-regular-expressions-to-parse-html-why-not


### Class 12: Thursday, March 2

**Activity:**
- Practice regular expressions challenges to match words and numbers in text
- Review Markov chains, how to generate one and sample sentences from it
- Discuss *n*-th order Markov chains and how to generate one from a corpus

**Tutorial:**
- Page 11: Markov Chains Revisited
- Page 15: Time to Tweet

**Objectives:**
- Build 2nd order Markov chain based on observed frequency of word triples
- Generate sentences by sampling words from 2nd order Markov chain
- Stretch challenge: Generalize your code to build *n*-th order Markov chain

**Resources:**
- Read Alex Dejeu's [article on how Markov chains work][Dejeu Markov article]
- Watch Make School's [Markov chains lecture]
- Review Make School's [Markov chains slides]
- Read Dataiku's [article on using Markov chains to generate Trump and Clinton quotes][Dataiku Markov article]

[Markov chains lecture]: https://www.youtube.com/watch?v=dNaJg-mLobQ
[Markov chains slides]: MarkovChains.pdf
[Markov chains visualization]: http://setosa.io/blog/2014/07/26/markov-chains/
[Dejeu Markov article]: https://hackernoon.com/from-what-is-a-markov-model-to-here-is-how-markov-models-work-1ac5f4629b71#.folhm2ymk
[Dataiku Markov article]: https://blog.dataiku.com/2016/10/08/machine-learning-markov-chains-generate-clinton-trump-quotes


## Working with this GitHub repository

This repository (located at `https://github.com/MakeSchool-18/Tweet-Generator`) is the course's _origin_ repository which will contain course materials including links, slides, and challenges.
Note that you cannot commit or push to the origin repository.
However, you can _fork_ it to maintain your own version of it and push your code there. Here's an overview of what your repository setup should look like:

![Repository Overview](repository-overview.png "Repository Overview")

Follow these steps to set up your own course repository:

1. Clone this repository on your computer:
`git clone git@github.com:MakeSchool-18/Tweet-Generator.git`

2. Fork this repository on GitHub to create your own version of this repo on your GitHub account, which should also be named `Tweet-Generator`

3. Add your GitHub repository as a _remote_ to the local one on your computer (note: you need to give a name to the remote, e.g. your first name):
`git remote add <first-name> git@github.com:<github-user>/Tweet-Generator.git`

4. Link the local repo to your remote GitHub repo:
`git push -u <first-name> master`

5. When you want to access new course materials, just pull from the origin remote repo:
`git pull origin master`

6. When you've completed a challenge and want to share it for code review, commit your work and push it to your own remote repo with:
`git push`
