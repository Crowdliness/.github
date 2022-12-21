We start off with [O'Reilly's collection on Natural Language Processing](https://learning.oreilly.com/topics/natural-language-processing/) and [Jon Krohn](https://github.com/jonkrohn)'s [Expert Playlist on Machine Learning](https://learning.oreilly.com/playlists/a40ea8fe-994d-4370-8b29-0d6c0f519a89/) ... this can rapidly take us into the overwhelming task of attempting to process hundreds of different proven Transformer and Diffuser models [and variations on those models] that we can find on Hugging Face Hub. 

**NLP is now something for mountains of GPUs and ML accelerators and new frontiers in BigCompute**

Before we get too carried away with how much more can be accomplished today than a year ago with GPUs and better memory bandwidth architectures, it might be best to actually go back to the FUNDAMENTALS of FUNDAMENTALS approach ... and look at how we initially wrangle the data and perform some of the most basic NLP computational assignments with the Natural Language ToolKit (NLTK) in Python ... we can also look at how the NLTK came into being and then evolved.

## NLTK / The NTLK development community
1. Language Processing and Python
2. Accessing Text Corpora and Lexical Resources
3. Processing Raw Text
4. Writing Structured Programs
5. Categorizing and Tagging Words
6. Learning to Classify Text
7. Extracting Information from Text
8. Analyzing Sentence Structure
9. Building Feature Based Grammars
10. Analyzing the Meaning of Sentences 
11. Managing Linguistic Data
12. The Evolving Language Challenge

## Phonology and Morphology
Computational approaches to the study of sound patterns and word structures typically use a finite state toolkit. Phenomena such as suppletion and non-concatenative morphology are difficult to address using the string processing methods we have been studying. The technical challenge is not only to link NLTK to a high-performance finite state toolkit, but to avoid duplication of lexical data and to link the morphosyntactic features needed by morph analyzers and syntactic parsers.

## Command Line Exploration To High-Performance Computing
Most natural language insights must come out of first using a very, very, very high-level exploratory language and a Pythonic mindset ... at first, this is accessible and only require a toolkit and an iPython or Jupyter Notebook interactive interface ... but, at some point, many NLP tasks quickly evolve into something too computationally intensive for pure Python implementations to be feasible. However, in some cases the expense only arises when training models, not when using them to label inputs. NLTK's package system provides a convenient way to distribute trained models, even models trained using corpora that cannot be freely distributed. Alternatives are to develop Python interfaces to high-performance machine learning tools, or to expand the reach of Python by using parallel programming techniques like MapReduce.

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
