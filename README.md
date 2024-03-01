# Summary
UD_English-CTeTex is a technical text corpus annotated in Universal Dependency syntax containing 196 software requirements.   

# Introduction
https://universaldependencies.org/release_checklist.html#the-readme-file

The original sentences of the corpus are taken from the [PURE corpus](https://ieeexplore.ieee.org/document/8049173) of software requirement specifications.


## Splitting
The whole corpus contains 9,273 tokens in 276 sentences for 196 software requirements.

As it is below the threshold of 20k tokens, it was not split for train/dev/test. 


The document id used in the files are related to the original file name in the PURE corpus suffixed with the document section, followed optionally with the requirement ID when the section lists multiple requirements.
For example "001_npac_6.4.3_R6-30.1" if taken from document 001_npac.pdf in the orginal corpus, and the requirement is in section 6.4.3. In this section, the requirement is identified as 6-30.1 in a table.


# Acknowledgments
We would like to thank the Natural Sciences and Engineering Research Council of Canada for the grant on the IVVES project that made this dataset possible.

## References

**(Hassert & al. 2021)** Naïma Hassert, Pierre André Ménard, Edith Galy. (2021) [UD on Software Requirements: Application and Challenges](https://aclanthology.org/2021.udw-1.5/). Proc. of Fifth Workshop on Universal Dependencies, Sofia, Bulgaria.

```
@inproceedings{hassert-etal-2021-ud,
    title = "{UD} on Software Requirements: Application and Challenges",
    author = {Hassert, Na{\"\i}ma  and
      M{\'e}nard, Pierre Andr{\'e}  and
      Galy, Edith},
    editor = "de Lhoneux, Miryam  and
      Tsarfaty, Reut",
    booktitle = "Proceedings of the Fifth Workshop on Universal Dependencies (UDW, SyntaxFest 2021)",
    month = dec,
    year = "2021",
    address = "Sofia, Bulgaria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.udw-1.5",
    pages = "62--74",
}
```


# Changelog

* 2022-05-15 v2.10
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.14
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction
Lemmas: not available
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Ménard, Pierre André
Contributing: here
Contact: pamenard@gmail.com
===============================================================================
</pre>
