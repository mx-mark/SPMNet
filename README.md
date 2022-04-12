# Visually aligned sound generation via sound-producing motion parsing [[paper](https://authors.elsevier.com/c/1etTF3INukKfYX)]
<img src="https://user-images.githubusercontent.com/94091472/162933955-5206dd2b-49b9-47be-878f-fc4bb35c3b20.jpg" alt="SPMNet" width="950">

# Overview
We propose to tame the visually aligned sound generation by projecting the sound-producing motion to a discriminative temporal visual embedding.
This visual embedding can, then, distinguish the transient visual motion from complex background information. which leads to produce high temporal-wise alignment sounds.
We refer to it as **SPMNet**.

# News
Code, pre-trained models and all demos will be released here. Welcome to watch this repository for the latest updates.

# Demo
## Dog
<video src="https://user-images.githubusercontent.com/94091472/162940077-5773285a-c967-4da4-bfc8-223faf2a6ed2.mp4"></video>
<video src="https://user-images.githubusercontent.com/94091472/162942202-0f3a392f-88be-4a5e-8bba-a1bb50023887.mp4"></video>

## Drum
<video src="https://user-images.githubusercontent.com/94091472/162942648-829712bb-ae63-4eec-a894-e4afcea067fe.mp4"></video>
<video src="https://user-images.githubusercontent.com/94091472/162942655-277c17c3-907b-4d55-a78a-725289cc334d.mp4"></video>

## Firework
<video src="https://user-images.githubusercontent.com/94091472/162942780-d247796b-03f4-4509-8fc6-f62716d78fa6.mp4"></video>
<video src="https://user-images.githubusercontent.com/94091472/162942788-ca10c467-d56f-4cde-92c5-549780a006db.mp4"></video>

Listen for the audio samples on our [materials](https://ars.els-cdn.com/content/image/1-s2.0-S0925231222003873-mmc1.pptx).

# Citation
Our paper was accepted by Neurocomputing 2022.
Please, use this bibtex if you would like to cite our work
```
@article{Ma2022VisuallyAS,
  title={Visually Aligned Sound Generation via Sound-Producing Motion Parsing},
  author={Xin Ma and Wei Zhong and Long Ye and Qin Zhang},
  journal={Neurocomputing},
  year={2022}
}
```

# Acknowledgments
We acknowledge the following work:
- The code base is built upon [RegNet](https://github.com/PeihaoChen/regnet) repo.
- Thanks to [SpecVQGAN](https://github.com/v-iashin/SpecVQGAN) open source efforts.
