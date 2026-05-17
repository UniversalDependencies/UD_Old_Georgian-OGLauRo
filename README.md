# Summary

A treebank for Old Georgian, containing morphosyntactic annotations of the Book of Ezra in the Oshki Bible.


# Introduction

UD_Old_Georgian-OGLauro is a treebank based on the Book of Ezra in the Oshki Bible. The text is retrieved from [TITUS](https://titus.uni-frankfurt.de/texte/etcs/cauc/ageo/at/oskijer/oskij.htm). The sentences are annotated through a semi-automated workflow: [UD_Georgian-GNC](https://github.com/UniversalDependencies/UD_Georgian-GNC) is used as few-shot examples, together with additional guidelines specific for Old Georgian and Ilia Abuladze's [ძველი ქართული ენის ლექსიკონი (მასალები)](http://www.nplg.gov.ge/gwdict/index.php?a=index&d=57) , to prompt Large Language Models (LLMs) to prepare a draft annotation, which is then corrected manually. 

# Acknowledgments

We are grateful to Dr. Paul Meurer for his discussion and guidance and to Prof. Dr. Jost Gippert for generously making the Old Georgian corpus available online on TITUS

## References

For the details of annotation principles, see Lin, Chia-Wei and Diego Luinetti.(forthcoming). 

``` bibtex
@article{LinLuinetti2026,
  author    = {Lin, Chia-Wei and Luinetti, Diego},
  title     = {Building a Treebank for {Ezra} Book of {Old} {Georgian} {Oshki} {Bible}},
  journal = {Journal of Historical Syntax},
  number   = {},
  year      = {forthcoming},
  doi      = {},
}
```


# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-NC-SA 4.0
Includes text: yes
Parallel: bible
Genre: bible
Lemmas: manual native
UPOS: manual native
XPOS: manual native
Features: manual native
Relations: manual native
Contributors: Lin, Chia-Wei; Luinetti, Diego
Contributing: here
Contact: chia-wei.lin@unil.ch; d.luinetti@unimarconi.it
===============================================================================
</pre>
