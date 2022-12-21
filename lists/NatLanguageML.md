## Command Line Exploration To High-Performance Computing

Python was not originally *supposed* to be for HPC. Python was, as a vastly improved derivative of the ABC educational programming language, a way for non-programmers, or at least non-C language and non-Assemblylanguage programmers to become more programmatic in their problem-solving, ie early Python was known for being devastatingly effective replacement for a scientific calculator. But after [thirty years of distillation](https://learning.oreilly.com/library/view/python-distilled/9780134173399/ch01.xhtml) it is probably still the basics and using Python interactively with iPython or a Jupyter Notebook interface, often collaboratively or allowing others to *play with the code* that makes Python [as popular as it is](https://www.tiobe.com/tiobe-index/) ... and, it is likely, that since Python is implemented in C, the popularity of C might be explained by low-level optimizations of code for Python libraries.  Most natural language insights must come out of first using a very, very, very high-level exploratory language, becoming fluent in command line Python and adopting a [Pythonic mindset in classes, objects, methods, functions and libraries](https://learning.oreilly.com/library/view/fluent-python-2nd/9781492056348/ch11.html) 

Yes, at some point ... rather quickly perhaps because of how Python can help accelerate a general understanding of the problem's domain space ... many NLP tasks evolve into something far too computationally intensive for pure Python implementations to be feasible ... it's time for low-level tensor optimizations of problem with C language, GPUs and AI accelerators. However, in some cases the expense only arises when training models or tokenizing, not when using NLTK to label inputs ... so it's possible to use things like "fast" tokenizers OR find other ways to specifically attack the constraint which is the current barrier to more rapid execution, ie *draining the pond exposes news rocks under the boat which can be removed with the pond level  lower.* ALL parts of the workflow can be optimized, eg NLTK's package system provides a convenient way to distribute trained models but there ways to add a Git workflow OR container registry to make the transition rapid from the Pythonic command line interfaces to high-performance computing and parallel programming machine learning approaches like MapReduce and things that take us past MapReduce.

**NLTK is still relevant ... even in the world where there are mountains of GPUs and more powerful ML accelerators and new frontiers in BigCompute**

Before we get too carried away with how much more can be accomplished today than a year ago with GPUs and better memory bandwidth architectures, it might be best to actually go back to the FUNDAMENTALS of FUNDAMENTALS approach ... and look at how we initially wrangle the data and perform some of the most basic NLP computational assignments with the Natural Language ToolKit (NLTK) in Python ... we can also look at how the NLTK came into being and then evolved ... and, by the way, things like NumPy or even the standard library in Python have certainly not stopped evolving, eg Python's not all THAT slow any more, like it was way back in 2022 before [the stable release of Python **3.11**](https://www.python.org/downloads/release/python-3110/) started being used.

**In order to efficiently, effectively and rapidly scale, it is imperative to understand the fundamentals better ... or else, we end up automating a complete shitstorm that is impossible to clean up.**

Thus we start off by revisiting [O'Reilly's collection on Natural Language Processing](https://learning.oreilly.com/topics/natural-language-processing/) and [Jon Krohn](https://github.com/jonkrohn)'s [Expert Playlist on Machine Learning](https://learning.oreilly.com/playlists/a40ea8fe-994d-4370-8b29-0d6c0f519a89/) ... this can rapidly take us into the overwhelming task of attempting to stay somewhat current reading and trying out hundreds of different proven Transformer and Diffuser models [and variations on those models] that we can find on Hugging Face Hub and in other corners of the interwebs ... as we understand, we can automate and improve the lower level execution, but it still helps us if we think of a general roadmap for studying semiotics and computational linguistics to better understand cognitive neuroscience of human crowds.  

## Phonology and Morphology
*How does the CROWD process information?* OR *How can we better achieve our objectives in knowledge engineering by using the constantly-learning crowd to more effectively process information?* We start by understanding the fundmentals of very fundamental stuff ... getting to very first principles of what underlies our assumptions when we analyze things from a *ab initio* or first principles approach. Computational approaches to the study of sound patterns and word structures typically use a finite state toolkit. Phenomena such as suppletion and non-concatenative morphology are difficult to address using the string processing methods we have been studying. The technical challenge is not only to link NLTK to a high-performance finite state toolkit, but to avoid duplication of lexical data and to link the morphosyntactic features needed by morph analyzers and syntactic parsers.

## Lexical Semantics
This is a vibrant area of current research, encompassing inheritance models of the lexicon, ontologies, multiword expressions, etc, mostly outside the scope of NLTK as it stands. A conservative goal would be to access lexical information from rich external stores in support of tasks in word sense disambiguation, parsing, and semantic interpretation.

## Natural Language Generation
Producing coherent text from underlying representations of meaning is an important part of NLP; a unification based approach to NLG has been developed in NLTK, and there is scope for more contributions in this area.

## Linguistic Fieldwork
A major challenge faced by linguists is to document thousands of endangered languages, work which generates heterogeneous and rapidly evolving data in large quantities. More fieldwork data formats, including interlinear text formats and lexicon interchange formats, could be supported in NLTK, helping linguists to curate and analyze this data, while liberating them to spend as much time as possible on data elicitation.

## Other Languages
Improved support for NLP in languages other than English could involve work in two areas: obtaining permission to distribute more corpora with NLTK's data collection; writing language-specific HOWTOs for posting at http://nltk.org/howto, illustrating the use of NLTK and discussing language-specific problems for NLP including character encodings, word segmentation, and morphology. NLP researchers with expertise in a particular language could arrange to translate this book and host a copy on the NLTK website; this would go beyond translating the discussions to providing equivalent worked examples using data in the target language, a non-trivial undertaking.

## NLTK-Contrib DevCommunity
Many of NLTK's core components were contributed by members of the NLP community, and were initially housed in NLTK's "Contrib" package, nltk_contrib. The only requirement for software to be added to this package is that it must be written in Python, relevant to NLP, and given the same open source license as the rest of NLTK. Imperfect software is welcome, and will probably be improved over time by other members of the NLP community.

## Teaching Materials
Since the earliest days of NLTK development, teaching materials have accompanied the software, materials that have gradually expanded to fill this book, plus a substantial quantity of online materials as well. We hope that instructors who supplement these materials with presentation slides, problem sets, solution sets, and more detailed treatments of the topics we have covered, will make them available, and will notify the authors so we can link them from http://nltk.org/. Of particular value are materials that help NLP become a mainstream course in the undergraduate programs of computer science and linguistics departments, or that make NLP accessible at the secondary level where there is significant scope for including computational content in the language, literature, computer science, and information technology curricula.


## Open Source Basics and The Python Development Community
1. Language Processing, Document Utilities and Python
2. Accessing Text Corpora, Wrangling Lexical Resources
3. Processing Raw Semiotics, At The Edge
4. Structured Programs, Structures of Structures, Managing MLops Workflow
5. Categorizing and Tagging Words, Semiotics, Images, Sounds, Smells
6. Learning to Classify, Tokenization
7. Vectorization, Extracting Basic Information
8. Analyzing Structure, Context, Meaning
9. Improving Feature-Based Models, Grammars, Idioms
10. Analyzing Context, Double Entendre, Misunderstandings 
11. Managing Linguistic Data and MLops Pipelines
12. The Rapidly Evolving Model Space 