# Complete-Blood-Count-CBC-
Complete Blood  Cells Detection and Counting
A complete blood count (CBC) is a blood test used to evaluate your overall health and detect a wide range of disorders, including anemia, infection and leukemia. A complete blood count test measures several components and features of your blood, including: Red blood cells, which carry oxygen.
Some of the most common diseases a CBC detects include anemia, autoimmune disorders, bone marrow disorders, dehydration, infections, inflammation, leukemia, lymphoma, myeloproliferative neoplasms, myelodysplastic syndrome, sickle cell disease, thalassemia, nutritional deficiencies (e.g., Iron, B12 or folate) etc.


## Transfer Learning and Custom Training for CBC on Official YOLOv7

## Results
``` shell
  Class      Images      Labels           P           R      mAP@.5  mAP@.5:.95: 100% 2/2 [00:02<00:00,  1.30s/it]
     all          73         967       0.852       0.876       0.906        0.61
     Platelets    73          76       0.802       0.855       0.876       0.436
     RBC          73         819       0.789       0.772       0.859         0.6
     WBC          73          72       0.966           1       0.983       0.792
50 epochs completed in 0.377 hours.
```

## Download file for weights "best.pt"

From Google Drive:
``` shell
https://drive.google.com/file/d/1WAGlkLQ4j24-CXqAo9fYP7nTqXpZOlom/view?usp=sharing
```

## Upload File directly or use the following code

From Google Drive:
``` shell
from google.colab import files
uploaded = files.upload()
```
## Inference

On image:
``` shell
!python custom_detect.py --weights best.pt --conf 0.06 --img-size 416 --source  /inference/images
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
