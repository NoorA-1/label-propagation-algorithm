This repository contains a Python implementation of the Label Propagation Algorithm for detecting community structures, based on the 2007 paper by Raghavan, Albert, and Kumara [1].

For evaluation, the `f_same` measure and Jaccard index were calculated by comparing two solutions obtained from the Zachary's Karate Club network [2].

## References

```bibtex
@article{raghavan2007near,
  title={Near linear time algorithm to detect community structures in large-scale networks},
  author={Raghavan, Usha Nandini and Albert, Réka and Kumara, Soundar},
  journal={arXiv preprint arXiv:0709.2938},
  year={2007}
}

@article{zachary1977information,
  title={An Information Flow Model for Conflict and Fission in Small Groups},
  author={Zachary, Wayne W.},
  journal={Journal of Anthropological Research},
  volume={33},
  number={4},
  pages={452--473},
  year={1977}
}
