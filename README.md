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
