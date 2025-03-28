# onePaperMultipleTypesettingStyles

This is the official one-paper-multiple-typesetting-styles implementation. 

LaTeX is initially designed to make typesetting easier by separating the content and the typesetting. However, when a draft is ready for submission or a paper is rejected without being sent for review and is determined to be submitted to another journal or conference, it usually takes authors plenty of time to make the draft or the paper adapted to the template of the target journal or conference while maintaining the latest content, which is quite inconvenient. Thus, we want to further separate the content and the typesetting. 

To track your LaTeX, please refer to [LaTeXChecker](https://github.com/BatchClayderman/LaTeXChecker). 

## Content

Please write your paper title, abstract, keywords, content, and references here. 

## Figure

Please include your figures (with their corresponding sources like ``.pptx`` if you wish to) here. It is highly recommended to use figures in the PDF format and vector graphics recognized by ``\includegraphics``. 

## Building

Currently, seven well-acknowledged templates are deployed. Users should only change the packages and authors' information to adapt to the specified templates. 

- ACMConference
- Elsevier
- IEEEConference
- IEEEJournal
- Springer
- TSP
- Wiley

## Caution

Please note that it is required to **specifically change the title in the Springer and the Wiley templates** while modifying the ``./Content/title.tex`` file. 

Please note that it is required to **specifically change the abstract and keywords** while modifying the ``./Content/title.tex`` and ``./Content/keyword.tex`` files. 

## Citation

If you wish to cite this work, please use the following BibTeX. 

```
@inproceedings{liu2024efficient,
  title={An efficient information retrieval and tracking algorithm for multiple typesetting styles of the same paper},
  author={Liu, Yingying and Li, Yuan and Tang, Jiyue and Ji, Tong and Xu, Xiaoyu and Luo, Yuxin and Lin, Yifeng and Yang, Yuer and Wu, Yubing},
  booktitle={2024 7th International Conference on Data Science and Information Technology (DSIT)},
  pages={1--6},
  year={2024},
  organization={IEEE}
}
```

## Forgetness

The paper mentioned above is the official academic paper that corresponds to this repository. It has already passed peer review, been published by the IEEE publisher, and been indexed by the EI database. 

People who typeset their papers based on this repository may forget to rewrite their Data Availability statements, which results in guiding reviewers to this repository. 

In these situations, we would appreciate it if reviewers could ask the authors for correct Data Availability statements instead of rejecting papers directly. 
