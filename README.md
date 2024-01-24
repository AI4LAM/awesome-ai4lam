# Awesome AI for LAM [![Awesome](.graphics/awesome-list-badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of resources, projects, and tools for using Artificial Intelligence in Libraries, Archives, and Museums.

[![License](https://img.shields.io/badge/License-CC0-blue.svg?style=flat-square)](https://github.com/AI4LAM/awesome-ai4lam/blob/master/LICENSE)
![Maintained?](https://img.shields.io/badge/Maintained%3F%2dyes-forestgreen.svg?style=flat-square)
[![Last commit](https://img.shields.io/github/last-commit/AI4LAM/awesome-ai4lam.svg?style=flat-square&color=orange&label=Last%20commit)](https://github.com/AI4LAM/awesome-ai4lam/commits/main/)
![GitHub contributors](https://img.shields.io/github/contributors/AI4LAM/awesome-ai4lam?label=Contributors&style=flat-square&color=a44e88)
[![Mastodon](https://img.shields.io/badge/Mastodon-7334cF?style=flat-square&logo=Mastodon&logoColor=white)](https://glammr.us/@AI4LAM)
[![Slack](https://img.shields.io/badge/Slack-5A255B?style=flat-square&logo=slack&logoColor=white)](https://ai4lam.slack.com/join/shared_invite/zt-1omthldn8-9vrGySjIRdija1nKQm0ltA#/)


## Contents

- [Introduction](#introduction)
- [Learning Resources](#learning-resources)
  - [Introductions to AI](#introductions-to-ai)
  - [Computer vision](#computer-vision)
  - [Natural language processing](#natural-language-processing)
  - [Generative AI](#generative-ai)
  - [AI in galleries, libraries, archives and museums](#ai-in-galleries-libraries-archives-and-museums)
  - [Other "awesome" lists in AI and ML](#other-awesome-lists-in-ai-and-ml)
- [Tools and Frameworks](#tools-and-frameworks)
  - [Document analysis, transcription, and labeling](#document-analysis-transcription-and-labeling)
  - [Audio and video analysis, transcription, and labeling](#audio-and-video-analysis-transcription-and-labeling)
  - [Indexing and classification](#indexing-and-classification)
  - [Search and retrieval](#search-and-retrieval)
  - [Applications of Transformers, LLMs, and GPT](#applications-of-transformers-llms-and-gpt)
- [Datasets](#datasets)
- [Projects, Initiatives, and Case Studies](#projects-initiatives-and-case-studies)
  - [Project lists & directories](#project-lists--directories)
  - [Projects by AI4LAM community members](#projects-by-ai4lam-community-members)
- [Policies and recommendations](#policies-and-recommendations)
  - [Statements by organizations and government bodies](#statements-by-organizations-and-government-bodies)
  - [Surveys of policies and recommendations](#surveys-of-policies-and-recommendations)
  - [Frameworks](#frameworks)
- [Conferences and Workshops](#conferences-and-workshops)
  - [Upcoming Conferences and Workshops](#upcoming-conferences-and-workshops)
  - [Past Conferences and Workshops](#past-conferences-and-workshops)
- [Journals and Magazines](#journals-and-magazines)
- [Community](#community)
- [Contributions](#contributions)
- [License](#license)


## Introduction

This list is a collection of resources, tools, projects, and other materials for professionals and enthusiasts in the Libraries, Archives, and Museums (LAM) sector. You might also know this as the GLAM (galleries, libraries, archives and museums) or CHI (cultural heritage institutions) sector, or be more familiar with the term 'memory institutions'. However you describe the field, if you know of an AI, machine learning, big data or data science project, event or resource related to collections, please share it here!

This list is maintained by the [AI4LAM](https://www.ai4lam.org/) community. Its aim is to support knowledge sharing, innovation, and collaboration in applying AI to LAM.

## Learning Resources

Please note: the appearance of a resource on this list does not constitute an official endorsement by AI4LAM.

### Introductions to AI

- [Elements of AI](https://www.elementsofai.com/) – free course by MinnaLearn & University of Helsinki
- [AI Guide by the AI Pedagogy Project](https://aipedagogy.org) – collection of materials by [metaLAB](https://mlml.io/about/)
- [Slides from FF23 workshop on _Intro to AI for GLAM_](https://docs.google.com/presentation/d/1dVdS3u-XS2RDexNm3RlwICCsh5gBmdi1pBARgIGnPN8) and [shared notes](https://pad.carpentries.org/intro-ai-ff2023)
- [Machine Learning 101](https://docs.google.com/presentation/d/1kSuQyW5DTnkVaZEjGYCkfOxvzCqGEFzWBy4e9Uedd9k/edit#slide=id.g168a3288f7_0_58) – by Jason Mayes from Google
- [Introduction to Deep Learning](https://sebastianraschka.com/blog/2021/dl-course.html), by Sebastian Raschka
- [Dive into Deep Learning](https://d2l.ai/index.html), by Zhang et al.
- [A Collection of AI Demos to Discover and Explore](https://exploreai.jisc.ac.uk/)
- [DeepLearning.AI Short Courses](https://www.deeplearning.ai/short-courses/), a free courses from a platform created by Andrew Ng
- [Introduction to Hugging Face](https://www.codecademy.com/learn/intro-to-hugging-face), a free course by Codecademy

### Computer vision

- [A Gentle Introduction to Computer Vision](https://machinelearningmastery.com/what-is-computer-vision/) – from Machine Learning Mastery
- [Computer Vision for the Humanities: An Introduction to Deep Learning for Image Classification](https://programminghistorian.org/en/lessons/computer-vision-deep-learning-pt1) – two-part intro by the Programming Historian

### Natural language processing

- [A Code-First Introduction to NLP](https://www.fast.ai/posts/2019-07-08-fastai-nlp.html) – by Rachel Thomas of fast.ai
- [NLP course](https://lena-voita.github.io/nlp_course.html) and associated [GitHub repo](https://github.com/yandexdataschool/nlp_course#readme) – by Elena Voita
- [NLP accelerated class](https://www.youtube.com/playlist?list=PL8P_Z6C4GcuWfAq8Pt6PBYlck4OprHXsw) – by Machine Learning University
- [Overview of deep learning techniques applied to NLP (2018)](https://nlpoverview.com/index.html)
- [Deep Learning for NLP](https://machinelearningmastery.com/category/natural-language-processing/) – from Machine Learning Mastery
- [Hands-on NLTK Tutorial](https://github.com/hb20007/hands-on-nltk-tutorial#readme)
- [NLP in Python - Quickstart Guide](https://github.com/NirantK/NLP_Quickbook#readme)
- [Deep Learning for NLP With Pytorch](https://pytorch.org/tutorials/beginner/deep_learning_nlp_tutorial.html)

### Generative AI

- [What are large language models (LLMs)?](https://www.youtube.com/watch?v=iR2O2GPbB0E) – (YouTube) by Google for Developers
- [A Very Gentle Introduction to LLMs without the Hype](https://mark-riedl.medium.com/a-very-gentle-introduction-to-large-language-models-without-the-hype-5f67941fa59e) – by Mark Riedl
- [What Is ChatGPT Doing … and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/) – by Stephen Wolfram
- [A brief introduction to GenAI](https://docs.google.com/presentation/d/1X3VpadTOsUe2neFts24pURy3nNQ2k64k4d3MEqHlEgk/edit#slide=id.g25b6aed46c6_0_492) – by U. Michigan MIDAS
- [The Map Of Transformers](https://towardsdatascience.com/the-map-of-transformers-e14952226398)
- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/), a visual introduction to transformers
- [Introduction to Generative AI](https://www.cloudskillsboost.google/paths/118), by Google
- [Generative AI for Beginners - A Course](https://microsoft.github.io/generative-ai-for-beginners/#/), by Microsoft
- [Understanding LLMs – A Transformative Reading List](https://sebastianraschka.com/blog/2023/llm-reading-list.html)
- [Large Language Model Course](https://github.com/mlabonne/llm-course#readme)
- [A Generative AI Primer](https://nationalcentreforai.jiscinvolve.org/wp/2023/10/16/generative-ai-primer/), by the UK's National Centre for AI
- [What Is ChatGPT Doing … and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/) by Stephen Wolfram

### AI in galleries, libraries, archives and museums

- The [AI4LAM YouTube channel](https://www.youtube.com/@ai4lam120/videos) has introductory presentations on many topics
- The [CENL "AI in Libraries" network group](https://www.cenl.org/networkgroups/ai-in-libraries-network-group/) is also organizing webinars on AI implementation in GLAM.

### Other "awesome" lists in AI and ML

- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning#readme)
- [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision#readme)
- [Awesome Image Classification](https://github.com/weiaicunzai/awesome-image-classification#readme)
- [Awesome Document Understanding](https://github.com/tstanislawek/awesome-document-understanding#readme)
- [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning#readme)
- [Awesome Deep Learning for Natural Language Processing (NLP)](https://github.com/brianspiering/awesome-dl4nlp#readme)
- [Awesome NLP](https://github.com/keon/awesome-nlp#readme)
- [Awesome Natural Language Generation](https://github.com/accelerated-text/awesome-nlg#readme)
- [Awesome Visual Transformer](https://github.com/dk-liang/Awesome-Visual-Transformer#readme)
- [Awesome Generative AI](https://github.com/steven2358/awesome-generative-ai#readme)
- [Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning#readme)
- [Awesome Jupyter GLAM](https://github.com/LibraryCarpentry/awesome-jupyter-glam#readme)
- [The NLP Index](https://index.quantumstat.com)


## Tools and Frameworks

Note: datasets for training and testing are listed in a [separate section](#datasets) of this document.

### Document analysis, transcription, and labeling

- [Callico](https://teklia.com/blog/open-sourcing-callico/) – open-source web platform for document annotation
- [Distributed Annotation 'n' Enrichment (DANE)](https://github.com/CLARIAH/DANE#readme) – compute task assignment & file storage for automatic annotation of content ([CLARIAH](https://www.clariah.nl/about-clariah), Norway)
- [HTRFLOW demo](https://huggingface.co/spaces/Riksarkivet/htr_demo) and associated [GitHub repo](https://github.com/Swedish-National-Archives-AI-lab/htrflow_app) – explore AI models for Handwritten Text Recogntion (Swedish National Archives)
- [Label Studio](https://labelstud.io) – data labeling platform to fine-tune LLMs, prepare training data, or validate AI models
- [OCR correction](https://bnl.public.lu/en.html) – OCR correction tools (Bibliothèque nationale, Luxembourg)
- [Surya](https://github.com/VikParuchuri/surya#readme) – multilingual document OCR toolkit with line-level text detection
- [Text models from the National Library of Sweden](https://huggingface.co/KBLab) – available on Hugging Face
- [Transkribus](https://readcoop.eu/transkribus/) – transcription, recognition, & searching of historical documents


### Audio and video analysis, transcription, and labeling

- [Acoustic models from the National Library of Sweden](https://huggingface.co/KBLab) – available on Hugging Face
- [Annotorious](https://annotorious.github.io) – JavaScript image annotation library
- [Audiovisual Metadata Platform (AMP)](https://uisapp2.iu.edu/confluence-prd/display/AMP/AMP%3A+Audiovisual+Metadata+Platform) – generation of metadata for discovery & use of digital audio & video collections (Indiana U., USA)
- [CAMPI](https://kilthub.cmu.edu/articles/preprint/CAMPI_Computer-Aided_Metadata_Generation_for_Photo_archives_Initiative/12791807) – Computer-Aided Metadata Generation for Photo archives Initiative (Carnegie Mellonw U., USA)
- [inaFaceAnalyzer](https://github.com/ina-foss/inaFaceAnalyzer#readme) – Python toolbox for face-based description of gender representation in media (Institut National de l'Audiovisuel, France)
- [Newspaper Navigator](https://labs.loc.gov/work/experiments/newspaper-navigator/) – explore visual & textual content in the _Chronicling America_ digitized newspaper collection (Library of Congress, USA)
- [Oodi](https://medium.com/headai-customer-stories/customer-story-oodi-1d1ef2554bb6) – virtual information assistant (Helsinki Central Library)
- [ReTV](https://retv-project.eu) – video analysis & summarization (Modul Univesrity, Austria)
- [VGG Image Annotator](https://www.robots.ox.ac.uk/~vgg/software/via/) – manual annotation software for image, audio and video

### Indexing and classification

- [Annif](https://annif.org) and [associated tutorial](https://github.com/NatLibFi/Annif-tutorial) – tool for automated subject indexing and classification (National Library of Finland)

### Search and retrieval

- [GallicaPix](https://gallicapix.bnf.fr/rest?run=findIllustrations-form.xq) – retrieval of heritage images (Bibliothèque nationale de France)
- [GallicaSNOOP](https://www.bnf.fr/sites/default/files/2022-05/Poster_Gallica_Snoop.pdf) – framework for large-scale content-based image retrieval (Bibliothèque nationale de France)
- [Maken Similarity Service](https://www.nb.no/maken/) – tools for alternative reading & finding similar photographs (National Library of Norway)
- [Semantic search for Nasjonalmuseet’s online collection](https://beta.nasjonalmuseet.no/2023/08/add-semantic-search-to-a-online-collection/) – open beta test (National Museum of Norway)
- [VGG Text Search (VTS) Engine](https://www.robots.ox.ac.uk/~vgg/software/vts/) – search for text strings over a user-defined image set

### Applications of Transformers, LLMs, and GPT

- [BERTopic](https://maartengr.github.io/BERTopic/index.html) – topic modeling technique that leverages Transformers and c-TF-IDF
- [Chatbot for Luxembourgish newspapers](https://chat.eluxemburgensia.lu/login?next=/) – uses ChatGPT and understands French, German and English (Bibliothèque nationale de Luxembourg)
- [Norwegian Transformer Model (NoTraM)](https://github.com/NBAiLab/notram#readme) – transformer model for Norwegian and Nordic languages (National Library of Norway)
- [Swedish BERT](https://github.com/Kungbib/swedish-bert-models#readme) – BERT model for the Swedish language (Royal Library of Sweden)
- [Visual AI](https://www.robots.ox.ac.uk/~vgg/projects/visualai/index.html) – open-world interpretable visual transformer (UK)


## Datasets

- [Datasets from the National Library of Sweden](https://huggingface.co/KBLab) – available on Hugging Face
- [Gensim datasets](https://github.com/piskvorky/gensim-data#readme) – repository of datasets for unstructured text processing
- [HTR-United](https://htr-united.github.io) – datasets for training transcription or segmentation models
- [Kaggle datasets](https://www.kaggle.com/datasets)
- [nlp-datasets](https://github.com/niderhoff/nlp-datasets#readme) – free/public domain datasets with text data for use in NLP
- [Open Library data dumps](https://openlibrary.org/developers/dumps) – from the Internet Archive
- [Registry of Open Data on AWS](https://registry.opendata.aws) – datasets tagged by topic

## Projects, Initiatives, and Case Studies

### Project lists & directories

- [Inventory of NARA Artificial Intelligence (AI) Use Cases](https://www.archives.gov/data/ai-inventory) - the US National Archives and Records Administration (NARA)'s inventory of AI use cases
- [List of Artificial Intelligence (AI) initiatives in museums](https://docs.google.com/spreadsheets/d/1A7IVnucQZ0ICxYSOCjqQ1oV3xGgNzDKtIYGrk6smV7w/edit#gid=0) – compiled in 2021 by Elena Villaespesa, Oonagh Murphy and Kate Nadel for the [Museums+AI Network](https://themuseumsai.network) project.
- [Projects in AI Registry (PAIR)](https://libraries.ou.edu/content/project-highlight-projects-ai-registry-pair) – registry of AI projects in higher education (U. Oklahoma Libraries, USA)

### Projects by AI4LAM community members

- [Living with Machines](https://livingwithmachines.ac.uk) – Turing Institute & British Library
- [Machine Learning with Archive Collections](https://blog.archiveshub.jisc.ac.uk/2022/02/28/machine-learning-with-archive-collections/)
- [Vatican Manuscripts](https://www.youtube.com/watch?v=8khPUtwaVaw) – machine transcription in the Vatican Secret Archive


## Policies and recommendations

### Statements by organizations and government bodies

- [ACM TechBrief on Generative AI, by the ACM Technology Policy Council](https://dl.acm.org/doi/pdf/10.1145/3626110)
- [Canadian Government _Principles for responsible, trustworthy and privacy-protective generative AI technologies_](https://www.priv.gc.ca/en/privacy-topics/technology/artificial-intelligence/gd_principles_ai/)
- [IFLA Statement on Libraries and Artificial Intelligence](https://repository.ifla.org/bitstream/123456789/1646/1/ifla_statement_on_libraries_and_artificial_intelligence-full-text.pdf)
- [US Government _Executive Order on the Safe, Secure, and Trustworthy Development and Use of Artificial Intelligence_](https://www.whitehouse.gov/briefing-room/presidential-actions/2023/10/30/executive-order-on-the-safe-secure-and-trustworthy-development-and-use-of-artificial-intelligence/)


### Surveys of policies and recommendations

- [A cluster analysis of national AI strategies](https://www.brookings.edu/articles/a-cluster-analysis-of-national-ai-strategies/) – Brookings Institute analysis of different countries’ national AI strategies, Dec. 2023
- [A principled governance for emerging AI regimes: lessons from China, the European Union, and the United States](https://link.springer.com/article/10.1007/s43681-022-00205-0) by R. B. L. Dixon in _AI and Ethics_, 3, 793–810, 2023
- [AI Governance Alliance: Briefing Paper Series](https://www.weforum.org/publications/ai-governance-alliance-briefing-paper-series/) – by the World Economic Forum, Jan. 2024
- [AI policies across the globe: Implications and recommendations for libraries](https://doi.org/10.1177/0340035223119617) by L.&nbsp;S. Lo in _IFLA Journal_, 49(4), 645–649, 2023
- [Principled Artificial Intelligence: Mapping Consensus in Ethical and Rights-Based Approaches to Principles for AI](http://dx.doi.org/10.2139/ssrn.3518482) by Fjeld et al, Berkman Klein Center Research Publication No. 2020-1, 2020
- [What ethics do I need to consider when using AI?](https://www.muchaduabout.com/post/what-ethics-do-i-need-to-consider-when-using-ai) – blog posting by Livi Adu, Nov. 2023


### Frameworks

- [A Comprehensive AI Policy Education Framework for University Teaching and Learning](https://educationaltechnologyjournal.springeropen.com/articles/10.1186/s41239-023-00408-3) by C. K. Y. Chan in _International Journal of Educational Technology in Higher Education_, 20(38), 2023.
- [A Framework for U.S. AI Governance: Creating a Safe and Thriving AI Sector](https://computing.mit.edu/wp-content/uploads/2023/11/AIPolicyBrief.pdf) white paper by the MIT Schwarzman College of Computing, Dec. 11, 2023. (See also [related article in MIT News](https://news.mit.edu/2023/mit-group-releases-white-papers-governance-ai-1211).)


## Conferences and Workshops

The annual _Fantastic Futures_ conference is the main conference series for the AI4LAM community. Various other conferences and workshops are relevant to the community and may be included in the list below.

### Upcoming Conferences and Workshops

👋🏻 **Note**: AI4LAM's [conferences tracker Google sheet](https://docs.google.com/spreadsheets/d/1jO8dKt0CuhZKq382OZRdMSGOU3OpJhgK2nJ-FAynbeo/edit#gid=1287495458) has a more complete list of events. The following is a list of larger and/or especially relevant events for AI4LAM.

- [IIPC General Assembly &amp; Web Archiving Conference](https://netpreserve.org/ga2024/) – Apr. 24–26 at the Bibliothèque nationale de France, Paris, France.
- [International Conference on Document Analysis and Recognition (ICDAR) 2024](https://icdar2024.net) – Aug. 30–Sep. 4 in Athens, Greece
- [International Conference on Digital Preservation (iPRES) 2024](https://ipres2024.pubpub.org) – Sep. 16–20 in Ghent & Flanders, Belgium.
- [Fantastic Futures 2024](https://www.nfsa.gov.au/fantastic-futures-canberra-2024-artificial-intelligence-libraries-archives-and-museums) – Oct. 16–18 at the National Film and Sound Archive of Australia (NFSA), Canberra, Australia.
- [ai4Libraries Conference](https://www.ai4libraries.org) – Oct. 23 and/or 24 virtual event hosted by Georgia Tech Library, Atlanta, Georgia, USA.
- [CIDOC 2024 &amp; Frontiers of knowledge, museums, documentation, and linked data](https://cidoc.mini.icom.museum/events/next-conference/) – Nov. 11–15 in Amsterdam, the Netherlands.

### Past Conferences and Workshops

- [Fantastic Futures 2018](https://www.nb.no/hva-skjer/ai-conference/) – Dec. 5 at the National Library of Norway, Oslo, Norway.
- [Fantastic Futures 2019](https://wayback.stanford.edu/was/20230508165810/http://library.stanford.edu/projects/fantastic-futures) – Dec. 4–6 at Stanford University, Stanford, California, USA.
- [Fantastic Futures 2021](https://www.bnf.fr/fr/captations-et-supports-de-la-conference-2021) – Dec. 8–10 at the Bibliothèque nationale de France, Paris, France.
- [Fantastic Futures 2022](https://sites.google.com/view/ai4lam/ai4lam-2022-virtual-event) – Nov. 30–Dec. 2 virtual event hosted by the British Library, London, England.
- [ai4Libraries Conference](https://www.ai4libraries.org) – Oct. 19 virtual event hosted by Georgia Tech Library, Atlanta, Georgia, USA.
- [Fantastic Futures 2023](https://ff2023.archive.org) – Nov. 15–17 at Internet Archive Canada Headquarters, Vancouver, British Columbia, Canada.


## Journals and Magazines

- [AI & Society](https://link.springer.com/journal/146/articles)
- [AI Magazine](https://onlinelibrary.wiley.com/loi/23719621)
- [Archival Science](https://link.springer.com/journal/10502)
- [Big Data & Society](https://journals.sagepub.com/home/bds)
- [Critical AI](https://criticalai.org)
- [Digital Humanities Quarterly](https://digitalhumanities.org/dhq/)
- [Digital Scholarship in the Humanities](https://academic.oup.com/dsh)
- [International Journal on Digital Libraries](https://link.springer.com/journal/799)
- [Journal of Academic Librarianship](https://www.sciencedirect.com/journal/the-journal-of-academic-librarianship/special-issue/10WVZWS842J)
- [Journal of Cultural Analytics](https://culturalanalytics.org)
- [Journal of Documentation](https://www.emerald.com/insight/publication/issn/0022-0418)
- [Journal of Librarianship and Information Science](https://journals.sagepub.com/home/LIS)
- [Journal of Open Humanities Data](https://openhumanitiesdata.metajnl.com)
- [Journal of the Association for Information Science and Technology](https://asistdl.onlinelibrary.wiley.com/journal/23301643)
- [Journal on Computing and Cultural Heritage](https://dl.acm.org/journal/jocch)
- [Library Hi Tech](https://www.emerald.com/insight/publication/issn/0737-8831)
- [Library Resources & Technical Services](https://journals.ala.org/index.php/lrts)
- [Literary and Linguistic Computing](https://dl.acm.org/journal/lilc)
- [Social Science Computer Review](https://journals.sagepub.com/description/SSC)
- [World Digital Libraries – An International Journal](https://content.iospress.com/journals/world-digital-libraries-an-international-journal)


## Community

The AI4LAM community's home page is [https://ai4lam.org](https://ai4lam.org/). The secretariat and other contact addresses can be found at the [_About_](https://sites.google.com/view/ai4lam/about) page.


## Contributions

Your help and participation in enhancing this awesome list are very much welcome! Please use the [issue ticket system](https://github.com/AI4LAM/awesome-ai4lam/issues) to request additions or changes, or to make other contributions to this repository. For more information, please visit the [guidelines for contributing](CONTRIBUTING.md).


## License

<img align="right" title="CC0 Logo" alt="CC0 Logo" src=".graphics/cc0.jpg" width="100rem"/>

The contents of this page are licensed under the [Creative Commons CC0 1.0 Universal license](https://creativecommons.org/public-domain/cc0/). CC0 is a &ldquo;no rights reserved&rdquo; license; the authors relinquish copyright and similar rights to the contents of the Awesome AI for LAM list.
