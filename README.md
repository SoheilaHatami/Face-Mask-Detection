# Wearing face mask detection using deep learning during COVID-19 pandemic
The official code for ["Wearing face mask detection using deep learning through COVID-19 pandemic"](https://arxiv.org/abs/2305.00068).

### Model Weights
["Yolov4-tiny-weights"](https://drive.google.com/file/d/1Aj-zghtgLFFIkx2XTPK_GjrzLnDjIZlL/view?usp=share_link)
["SSD-weights"](https://drive.google.com/file/d/1rEOU81fACnlhbeIHHT23lK439hwkbTFK/view?usp=share_link)

### Training and Testing
1) Download the face mask detection dataset from [here](https://drive.google.com/file/d/1eybS8bQj5kMC73-ibIZJ_3O2IV507iJI/view?usp=share_link).
2) Run the following code to install the Requirements.

    `pip install -r requirements.txt`

3) Run the following notebooks to train the models on the face mask detection dataset.
    SSD.ipynb
    YOLOv4.ipynb
4) Test the trained model with this dataset in in IPYNB too.

## Results
Performance comparision on the dataset is as the following:

## YOLOv4-tiny Result
![yv4](https://github.com/SoheilaHatami/Face-Mask-Detection/assets/74190994/0da43764-9dd0-4150-a4df-033bdbec9148)

## SSD Result
![mobilnet](https://github.com/SoheilaHatami/Face-Mask-Detection/assets/74190994/dafe1d5a-30ff-4470-b0d9-b584b031e813)

## Final Result
<p align="center">
![mAP](https://github.com/SoheilaHatami/Face-Mask-Detection/assets/74190994/93107ee7-acaf-4ea3-be21-bfd5ba807409)
</p>

## Citation
```
@article{Faculty of Mechanical Engineering, Tarbiat Modares University, Tehran, Iran,
  title={Wearing face mask detection using deep learning through COVID-19 pandemic},
  author={Javad Khoramdel
, Soheila Hatami
, and Majid Sadedel},
  journal={https://arxiv.org/abs/2305.00068},
  year={2023}
}
```
