# Text Classification Survey

Companion website to a long-running survey on text classification. We have been working on text classification since over ten years. 

Access to the latest version of the [text classification survey compiled as PDF](https://github.com/ascherp/text-classification-survey/blob/main/paper/main-textclassification.pdf).
Larger updates are also released on the text classification [survey's arXiv](https://arxiv.org/abs/2204.03954) landing page.

Versions:
 
- [Version 2025-01-19 on arXiv](https://arxiv.org/abs/2204.03954v6): extending into results from methods using large language models; added methods up to and including January 2025

- [Version 2023-03-03 on arXiv](https://arxiv.org/abs/2204.03954v2): added hierarchical text classification; removed appendix

- [Version 2022-04-08 on arXiv](https://arxiv.org/abs/2204.03954v1): added multi-label text classification; included measurements of running time and plots of the datasets' class distributions (in appendix)

- [Version 2022-05](https://doi.org/10.18653/v1/2022.acl-long.279) (ACL) and [update of the survey on arxiv](https://arxiv.org/abs/2109.03777v3): ACL 2022 paper on single-label text classification and introduction of WideMLP with TF-IDF as baseline

- [Version 2021-09-01](https://arxiv.org/abs/2109.03777v1): first release of the survey on single-label text classification and introduction of the TF-IDF + WideMLP baseline (dubbed the ``simple'' baseline)
 
## Citation

Please cite this work as follows:

For **single-label text classificatiomn, multi-label classification, and hierarchical classification, including the use of large language models**:

```
@misc{galke2025reallymakingprogresstext,
      title={Are We Really Making Much Progress in Text Classification? A Comparative Review}, 
      author={Lukas Galke and Ansgar Scherp and Andor Diera and Fabian Karl and Bao Xin Lin and Bhakti Khera and Tim Meuser and Tushar Singhal},
      year={2025},
      eprint={2204.03954},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2204.03954}, 
}
```

Please cite this work as follows **for single-label text classificatiomn and TF-IDF + WideMLP baseline**:

```
@inproceedings{DBLP:conf/acl/GalkeS22,
  author       = {Lukas Galke and
                  Ansgar Scherp},
  editor       = {Smaranda Muresan and
                  Preslav Nakov and
                  Aline Villavicencio},
  title        = {Bag-of-Words vs. Graph vs. Sequence in Text Classification: Questioning
                  the Necessity of Text-Graphs and the Surprising Strength of a Wide
                  {MLP}},
  booktitle    = {Proceedings of the 60th Annual Meeting of the Association for Computational
                  Linguistics (Volume 1: Long Papers), {ACL} 2022, Dublin, Ireland,
                  May 22-27, 2022},
  pages        = {4038--4051},
  publisher    = {Association for Computational Linguistics},
  year         = {2022},
  url          = {https://doi.org/10.18653/v1/2022.acl-long.279},
  doi          = {10.18653/V1/2022.ACL-LONG.279},
  timestamp    = {Wed, 07 Dec 2022 23:10:02 +0100},
  biburl       = {https://dblp.org/rec/conf/acl/GalkeS22.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```


