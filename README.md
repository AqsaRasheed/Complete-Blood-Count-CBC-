# Complete-Blood-Count-CBC-
Complete Blood  Cells Detection and Counting
#Transfer Learning and Custom Training for CBC on Official YOLOv7


## Inference

On image:
``` shell
!python detectandcount.py --weights best.pt --conf 0.06 --img-size 416 --source  /inference/images

```

<div align="center">
    <a href="./">
        <img src="./figure/1.jpg" width="59%"/>
    </a>
</div>

<div align="center">
    <a href="./">
        <img src="./figure/2.jpg" width="59%"/>
    </a>
</div>
<div align="center">
    <a href="./">
        <img src="./figure/3.jpg" width="59%"/>
    </a>
</div>
<div align="center">
    <a href="./">
        <img src="./figure/4.jpg" width="59%"/>
    </a>
</div>
<div align="center">
    <a href="./">
        <img src="./figure/5.jpg" width="59%"/>
    </a>
</div>

## Reference/Citation

```
@article{wang2022yolov7,
  title={{YOLOv7}: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors},
  author={Wang, Chien-Yao and Bochkovskiy, Alexey and Liao, Hong-Yuan Mark},
  journal={arXiv preprint arXiv:2207.02696},
  year={2022}
}
```





## Acknowledgements

<details><summary> <b>Expand</b> </summary>

* [https://github.com/WongKinYiu/yolov7](https://github.com/WongKinYiu/yolov7)
</details>
