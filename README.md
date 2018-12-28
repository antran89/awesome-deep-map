[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# Deep Mapping Algorithm Resources
A curated list of resources dedicated to deep learning / computer vision algorithms for mapping. The mapping problems include road network inference, building footprint extraction, etc. Any suggestions and pull requests are welcome.

## Papers & Code

### Road network extraction
- [2015-ICCV] Enhancing Road Maps by Parsing Aerial Images Around the World [`paper`](https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Mattyus_Enhancing_Road_Maps_ICCV_2015_paper.pdf)
- [2016-KDD] City-Scale Map Creation and Updating Using GPS Collections [`paper`](https://geometry.stanford.edu/papers/clhygg-csmcugc-16/clhygg-csmcugc-16.pdf)
- [2017-ICCV] DeepRoadMapper: Extracting Road Topology From Aerial Images [`paper`](http://www.cs.toronto.edu/~wenjie/papers/iccv17/mattyus_etal_iccv17.pdf) [code](`https://github.com/mitroadmaps/roadtracer/tree/master/deeproadmapper`)
- [2017-CVPRW] Joint Learning From Earth Observation and OpenStreetMap Data to Get Faster Better Semantic Maps [`paper`](https://arxiv.org/abs/1705.06057)
- [2018-ISPRS International Journal of Geo-Information] Generative Street Addresses from Satellite Imagery [`paper`](https://research.fb.com/publications/generative-street-addresses-from-satellite-imagery/) [`code`](https://github.com/facebookresearch/street-addresses)
- [2018-CVPR, RoadTracer] RoadTracer: Automatic Extraction of Road Networks from Aerial Images [`paper`](http://arxiv.org/abs/1802.03680) [`homepage`](https://roadmaps.csail.mit.edu/) [`code`](https://github.com/mitroadmaps/roadtracer)
- [2018-CVPRW2018] D-LinkNet : LinkNet with Pretrained Encoder and Dilated Convolution for High Resolution Satellite Imagery Road Extraction [`paper`](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Zhou_D-LinkNet_LinkNet_With_CVPR_2018_paper.pdf) [`code`](https://github.com/zlkanata/DeepGlobe-Road-Extraction-Challenge)

### Building footprint extraction
- [2017-TPAMI] Learning Building Extraction in Aerial Scenes with Convolutional Networks [`paper`](http://arxiv.org/abs/1602.06564)
- [2018-CVPRW2018, TernausNetV2] TernausNetV2: Fully Convolutional Network for Instance Segmentation [`paper`](http://arxiv.org/abs/1806.00844) [`code`](https://github.com/ternaus/TernausNetV2)
- [2018-CVPRW2018] Building Detection From Satellite Imagery Using Ensemble of Size-Specific Detectors [`paper`](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Hamaguchi_Building_Detection_From_CVPR_2018_paper.pdf)
- [2018-CVPRW2018] Building Detection from Satellite Imagery Using a Composite Loss Function [`paper`](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Golovanov_Building_Detection_From_CVPR_2018_paper.pdf)

### Others

### Mapping toolkit
- OSM data export tools from HOTOSM, [tool](https://export.hotosm.org/en/v3/exports/new/describe)

## Datasets
- [2017-ICCV] TorontoCity: Seeing the World with a Million Eyes [`homepage`](http://www.cs.toronto.edu/~slwang/) [`paper`](http://arxiv.org/abs/1612.00423)
  - Data source: aerial RGB image, streetview panorama, GoPro, stereo image, street-view LIDAR, airborne LIDAR; Maps: buildings and roads, 3D buildings, property meta-data; Tasks: semantic segmentation, building height estimation, instance segmentation, road topology, zoning segmentation and classification.
  - A non-sharing dataset.
- [2018-arxiv, `SpaceNet`] SpaceNet: A Remote Sensing Dataset and Challenge Series [`paper`](http://arxiv.org/abs/1807.01232)
  - SpaceNet competition hosts several datasets on roads and buildings. For example, `Challenge 3 - Las Vegas, Paris, Shanghai, Khartoum Road Extraction
Challenge` provides road-centerlines annotation of SpaceNet dataset. It uses the imagery from Challenge 2 (24,586 images of 302,701 building footprints), only tiled into 400m chips (resolution of `1300px` x ``1300px``.
- [2018-CVPRW2018, `DeepGlobe`] DeepGlobe 2018: A Challenge to Parse the Earth through Satellite Images [`paper`](http://arxiv.org/abs/1805.06561)
  - Road extraction challenge: DigitalGlobe+Vivid images in Thailand, Indonesia, India with 50cm/pixel. Total of 8570 images (6226 training, 1243 validation, 1101 testing).
  - Building detection: the images are taken from  25,586 images of size `650px` x `650px`
  - Land cover classification: containing 1,146 satellite images of size `2448px` × `2448px` pixels in total.

## Open source implementation

