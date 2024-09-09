<p align="center">
  <h1 align="center">
    <strong>
      [EMNLP 2023 Main Conference] Towards a Unified Conversational Recommendation System: Multi-task Learning via Contextualized Knowledge Distillation
    </strong>
  </h1>

  <p align="center">
    Yeongseo Jung,
    Eunseo Jung,
    Lei Chen
    <br>
    Department of CSE, HKUST
  </p>

  <div align="center">
    <a href=https://arxiv.org/abs/2310.18119><img src='https://img.shields.io/badge/arXiv-2407.11962-b31b1b.svg'></a>  
  </div>
  
  <h2>Details</h2>
  <p>Coming Soon!</p>
</p>



## Citation
If you are working on the same or similar tasks and find our work interesting, please consider citing our work :)
```BibTeX
@inproceedings{jung-etal-2023-towards,
    title = "Towards a Unified Conversational Recommendation System: Multi-task Learning via Contextualized Knowledge Distillation",
    author = "Jung, Yeongseo  and
      Jung, Eunseo  and
      Chen, Lei",
    editor = "Bouamor, Houda  and
      Pino, Juan  and
      Bali, Kalika",
    booktitle = "Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.emnlp-main.840",
    doi = "10.18653/v1/2023.emnlp-main.840",
    pages = "13625--13637",
    abstract = "In Conversational Recommendation System (CRS), an agent is asked to recommend a set of items to users within natural language conversations. To address the need for both conversational capability and personalized recommendations, prior works have utilized separate recommendation and dialogue modules. However, such approach inevitably results in a discrepancy between recommendation results and generated responses. To bridge the gap, we propose a multi-task learning for a unified CRS, where a single model jointly learns both tasks via Contextualized Knowledge Distillation (ConKD). We introduce two versions of ConKD: hard gate and soft gate. The former selectively gates between two task-specific teachers, while the latter integrates knowledge from both teachers. Our gates are computed on-the-fly in a context-specific manner, facilitating flexible integration of relevant knowledge. Extensive experiments demonstrate that our single model significantly improves recommendation performance while enhancing fluency, and achieves comparable results in terms of diversity.",
}
```