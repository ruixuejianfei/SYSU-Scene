SYSU-Scene Dataset
=================================
![SYSU-Scene example](https://github.com/ruixuejianfei/SYSU-Scene/blob/master/sample.png)

SYSU-Scene dataset is a new parsing database including elaborately annotated objects.

  - 5,046 high-resolution photos with totally 37 tags
  - Wide range of categories, relationship, and scenes
  - All images are with pixel-level annotations

Feel free to contact `r.m.zhang1989@gmail.com` should you have any suggestions or questions.

Please visit the [project page](http://hcp.sysu.edu.cn/sysu-scenes/) for more information.

Files
-----
Root directory contains following files and folders:
  - ground truth/               - directory of annotations (5046 files.mat)
  - gtvis/                      - directory of visual result of annotations (5046 files.png)
  - images/                     - directory of original photos (5046 files.jpg)
  - seg/                        - directory of segmentations (5046 files.png)
  - label_list.mat              - [1*59] cell array which maps label numbers to label names
  - README.md                   - this file
  - sample.png                  - sample annotations

Notes on Image-Level Annotations
--------------------------------
Each annotation is saved in `ground truth/` as a matlab `.mat` file, which is a variable
- groundtruth: [h*w] matrix denotes the annotated labels of pixels

```
