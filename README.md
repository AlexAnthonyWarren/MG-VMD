# Effective Video Mirror Detection with Inconsistent Motion Cues (CVPR2024)
Alex Warren, Ke Xu, Jiaying Lin, Gary Tam, Rynson W.H. Lau

[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Warren_Effective_Video_Mirror_Detection_with_Inconsistent_Motion_Cues_CVPR_2024_paper.pdf)

## Abstract 
Image-based mirror detection has recently undergone rapid research due to its significance in applications such as robotic navigation, semantic segmentation and scene reconstruction. Recently, VMD-Net was proposed as the first video mirror detection technique, by modeling dual correspondences between the inside and outside of the mirror both spatially and temporally. However, this approach is not reliable, as correspondences can occur completely inside or outside of the mirrors. In addition, the proposed dataset VMD-D contains many small mirrors, limiting its applicability to real-world scenarios. To address these problems, we developed a more challenging dataset that includes mirrors of various shapes and sizes at different locations of the frames, providing a better reflection of real-world scenarios. Next, we observed that the motions between the inside and outside of the mirror are often inconsistent. For instance, when moving in front of a mirror, the motion inside the mirror is often much smaller than the motion outside due to increased depth perception. With these observations, we propose modeling inconsistent motion cues to detect mirrors, and a new network with two novel modules. The Motion Attention Module (MAM) explicitly models inconsistent motions around mirrors via optical flow, and the Motion-Guided Edge Detection Module (MEDM) uses motions to guide mirror edge feature learning. Experimental results on our proposed dataset show that our method outperforms state-of-the-arts.

## Citation
```bibtex
@InProceedings{Warren_2024_CVPR,
    author    = {Warren, Alex and Xu, Ke and Lin, Jiaying and Tam, Gary K.L. and Lau, Rynson W.H.},
    title     = {Effective Video Mirror Detection with Inconsistent Motion Cues},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2024},
    pages     = {17244-17252}
}
```

Code:
Weights:
Dataset:

