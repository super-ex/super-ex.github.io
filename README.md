# SuperEx: Enhancing Indoor Mapping and Exploration using Non-Line-of-Sight Perception

This is the repo for the paper

**[SuperEx: Enhancing Indoor Mapping and Exploration using Non-Line-of-Sight Perception](https://super-ex.github.io)**  

[Kush Garg](https://www.linkedin.com/in/kushgarg22/)<sup>\*</sup>, [Akshat Dave](https://akshatdave.github.io/)

[Paper](https://arxiv.org/pdf/2510.10506) | [Video](https://youtu.be/r53JzqJOlBI)

## Abstract

Efficient exploration and mapping in unknown indoor environments is a fundamental challenge, with high stakes in time-critical settings. In current systems, robot perception remains confined to line-of-sight; occluded regions remain unknown until physically traversed, leading to inefficient exploration when layouts deviate from prior assumptions. In this work, we bring non-line-of-sight (NLOS) sensing to robotic exploration. We leverage single-photon LiDARs, which capture time-of-flight histograms that encode the presence of hidden objects -- allowing robots to look around blind corners. Recent single-photon LiDARs have become practical and portable, enabling deployment beyond controlled lab settings. Prior NLOS works target 3D reconstruction in static, lab-based scenarios, and initial efforts toward NLOS-aided navigation consider simplified geometries. We introduce SuperEx, a framework that integrates NLOS sensing directly into the mapping–exploration loop. SuperEx augments global map prediction with beyond-line-of-sight cues by (i) carving empty NLOS regions from timing histograms and (ii) reconstructing occupied structure via a two-step physics-based and data-driven approach that leverages structural regularities. Evaluations on complex simulated maps and the real-world KTH Floorplan dataset show a 12% gain in mapping accuracy under 30% coverage and improved exploration efficiency compared to line-of-sight baselines, opening a path to reliable mapping beyond direct visibility.

## Citation

```bibtex
@misc{garg2025superexenhancingindoormapping,
      title={SuperEx: Enhancing Indoor Mapping and Exploration using Non-Line-of-Sight Perception}, 
      author={Kush Garg and Akshat Dave},
      year={2025},
      eprint={2510.10506},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2510.10506}, 
}
```