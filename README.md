# CarFusion: Combining Point Tracking and Part Detection for Dynamic 3D Reconstruction of Vehicle

[N Dinesh Reddy](http://cs.cmu.edu/~dnarapur), [Minh Vo](http://www.cs.cmu.edu/~mvo), [Srinivasa G. Narasimhan](http://www.cs.cmu.edu/~srinivas/)

IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2018. 

[[Project](http://www.cs.cmu.edu/~ILIM/projects/IM/CarFusion/)] [[Paper](http://www.cs.cmu.edu/~ILIM/publications/PDFs/RVN-CVPR18.pdf)] [[Supp](http://www.cs.cmu.edu/~ILIM/projects/IM/CarFusion/pdf/occlusion_net_supp.pdf)]

## Requirements
- Python 3.6
- OpenCV > 3.0
- Numpy
- Glob
- googledrivedownloader
- shapely


## Dataset((14 Keypoints annotations for 100,000 cars(53,000 Images)))

We provide mannual annotations of 14 semantic keypoints for 100,000 car instances (sedan, suv, bus, and truck) from 53,000 images captured from 18 moving cameras at Multiple intersections in Pittsburgh, PA. To view the labels, please run the following command:

To visualize the data:
'''
wget http://www.cs.cmu.edu/~ILIM/projects/IM/CarFusion/Script/Visualize.py
python Visualize.py PathToData CamID_FrameID
'''
