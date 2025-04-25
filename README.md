## Designing Secure AI-based Systems: a Multi-Vocal Literature Review
This repository contains the replication package for the above paper, published at IEEE SecDev 2024


### Cite
If you use the presented results in a scientific context, please cite as:

```bibtex
@inproceedings{schneider_2024_AI-systems_security_rules,
    author      = {Schneider, Simon and Saha, Ananya and Mezzi, Emanuele and Tuma, Katja and Scandariato, Riccardo},
    booktitle   = {2024 IEEE Secure Development Conference (SecDev)}, 
    title       = {Designing Secure AI-based Systems: a Multi-Vocal Literature Review}, 
    year        = {2024},
    pages       = {13-19},
    keywords    = {Bibliographies;Computer architecture;Software systems;Security;Artificial intelligence;Guidelines;AI;software architecture;security;guidelines},
    doi         = {10.1109/SecDev61143.2024.00007}}
}
```


### Abstract 
AI-based systems leverage recent advances in the field of AI/ML by combining traditional software systems with AI components. Applications are increasingly being developed in this way. Software engineers can usually rely on a plethora of supporting information on how to use and implement any given technology. For AI-based systems, however, such information is scarce. Specifically, guidance on how to securely design the architecture is not available to the extent as for other systems.

We present 16 architectural security guidelines for the design of AI-based systems that were curated via a multi-vocal literature review. The guidelines could support practitioners with actionable advice on the secure development of AI-based systems. Further, we mapped the guidelines to typical components of AI-based systems and observed a high coverage where 6 out of 8 generic components have at least one guideline associated to them.

### Content

1. ```systematic_literature_review.xlsx```: contains the intermediate and final results of a systematic literature review we have conducted to identify actionable guidance for designing AI-based systems securely.

2. ```grey_literature_study.xlsx```: contains the intermediate and final results of a grey literature study we conducted and which did not produce any usable results for the intended goal.

3. ```search_queries.txt```: contains the search queries we used to enable reproducability. 

4. ```raw_results/```: contains the results of applying he search queries to the used scnientific databases.

5. ```merged_search_results.csv```: contains the raw results of all databases merged into one list.

6. ```selected_sources/```: contains the three papers that were retained after the selection process and which form the basis of the presented list of architectural security guidelimes for AI-based systems.


