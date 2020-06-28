# Knowledge-Centric Software Engineering

This repo contains an exploration of the idea to have knowledge management at the center of software development, and tools that result from the exploration.

The fundamentals are discussed in the [wiki](https://github.com/SoftDevGang/knowledge-centric-software-engineering/wiki), so that's a good place to get started.

If you're more interested in the practical aspects, the source code repository contains tools related to the topic.

## Knowledge harvesting from code

Since a lot of knowledge is stored in existing code, we are looking at ways to harvest that knowledge. The avenues for investigation are: names and relationships (aka a multi-dimensional ontology).

Names can be extracted, cleaned up, and analysed as follows:

* classify based on the knowledge content, for example into useless (eg. `a`), technical details (eg. `Exception`), domain names, and misleading
* identify synonyms or words with very similar meaning 
* difference between the list of words used and the domain names. Perhaps we should aim for a high percentage of domain names in our code

### First step: A list of words used

The tool "word_list" is a script that extracts words used in C++ code. It removes comments, #includes, and string constants and outputs all the other names found in code. You can find more details by looking at the code.

### Next steps: who knows?

If you're interested in the topic, please contribute on the wiki, submit a pull request, or contact @alexboly on twitter.
