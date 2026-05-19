---
title: "Morph & Slerp: Shape description for 3D printing of concrete"
authors: Bhooshan, S., Van Mele, T. and Block, P.
year: 2020
keywords: 3D printing, Robotic concrete printing, Optimal Transport, Displacement Interpolation, Function Representation, shape-design, pitched-brick vaulting
link: "https://doi.org/10.1145/3424630.3425413"
image: /assets/images/publications/Morph & Slerp Shape description for 3D printing of concrete.jpg
order: 9
abstract: >-
  Synthesis of shapes that are guaranteed to be physically produced by Robotic 3D printing of concrete, needs research attention. This is necessitated by the rapid development of the hardware, commercial availability of and interest in concrete printing. Further the need is amplified by the lack of easy-to-implement-and-use shape-design tools. Together, they provide the context of the proposed work. 
  A necessary feature for geometries to be ‘printable’ is that each consecutive layer onto which material is deposited should change gradually such that it has sufficient overlap with the preceding layer (spatial coherence of print paths). The computational handling of these aspects have been introduced by Bhooshan et al. 2018 including the use of a time evolving scalar-field to represent the shape to be designed – the so-called Function Representation (FRep). This paper significantly extends the previous work by (a) fully parametrising the shape description for 3D printing of concrete by decomposing the shape as a combination of shape interpolation (Morph) and affine interpolation (Slerp), and (b) replacing the linear, cross-fading interpolation scheme resulting in physically problematic artefacts with a scheme that produces smooth, spatially coherent outcomes. 
  An easy-to-implement software application has been prototyped. It couples the shape description with a guiding heuristic to design topologically complex, physically plausible shapes with relative ease. The coupling significantly reduces the effort and expertise needed to produce shapes that are printable whilst also providing intuitive, visual feedback to designers. This is particularly useful in the current context where computer simulation of the stability of the layers during printing is actively being developed, experimental in nature and still computationally expensive. The presented approach does not, however, automatically guarantee printable outputs. The shape description and outputs may, nonetheless, be readily used as good candidates for further optimisation to guarantee print readiness.
citation: >-
  Bhooshan, S., Van Mele, T. and Block, P., 2020, November. Morph & Slerp: Shape description for 3D printing of concrete. In Proceedings of the 5th Annual ACM Symposium on Computational Fabrication (pp. 1-10).
---