# SplatXtRact

**Tractable Gaussian Splatting via Open World Region-of-Interest Extraction and Refinement**

## Authors

* [Hannah Schieber](https://hannahhaensen.github.io)
* Constantin Kleinbeck
* Angela Schoellig
* Stefan Leutenegger
* [Daniel Roth](https://hex-lab.io/author/daniel-roth/)

## Affiliations

* Human-Centered Computing and Extended Reality Lab, TUM University Hospital, Clinic for Orthopedics and Sports Orthopedics
* Technical University of Munich
* Munich Institute of Robotics and Machine Intelligence (MIRMI)
* Mobile Robotics Lab, ETH Zurich

## Abstract

We present a task-conditioned refinement for 3D Gaussian Splatting (GS) that enables robots or human operators to selectively extract task-relevant regions of a learned scene.

Given a pre-trained GS map, our approach supports local region-of-interest (ROI) refinement, preserving global map consistency while meeting close to real-time constraints required for interactive robotic perception.

The framework decouples semantic ROI selection from initial GS optimization, allowing flexible integration with external and novel perception models.

We evaluate our approach on indoor and outdoor datasets, including **TUM RGB-D** and **MipNeRF360**, demonstrating:

* Higher novel view synthesis quality compared to the state of the art
* Reduced artifacts
* Bounded latency suitable for human-in-the-loop operation

## Paper

The paper is available as open access in **IEEE Robotics and Automation Letters**:

[IEEE RA-L Paper](https://ieeexplore.ieee.org/document/11543331)

## Demo Video

A demo video is embedded on the project page:

[Watch on YouTube](https://youtu.be/WxQG413UnDA)

Embed URL:

```html
<iframe
  src="https://www.youtube.com/embed/WxQG413UnDA"
  title="YouTube video player"
  allowfullscreen>
</iframe>
```

## Code

Code: **TBA**

## Contact

For questions or interest in comparing object removal and extraction methods, contact:

**hannah dot schieber [at] tum dot de**

## Citation

```bibtex
@ARTICLE{schieber_splatxtract_2026,
  author={Schieber, Hannah and Kleinbeck, Constantin and Schoellig, Angela P. and Leutenegger, Stefan and Roth, Daniel},
  journal={IEEE Robotics and Automation Letters},
  title={SplatXtRact: Tractable Gaussian Splatting via Open World Region-of-Interest Extraction and Refinement},
  year={2026},
  volume={11},
  number={7},
  pages={8664-8671},
  doi={10.1109/LRA.2026.3699257}
}
```

## Keywords

* Gaussian Splatting
* Semantic Gaussian Splatting
* Region-of-Interest Extraction
* ROI Refinement
* Robotic Perception
* Novel View Synthesis
* Human-in-the-Loop Interaction
