# imagenette / imagewoofの実験用コード置き場

https://github.com/fastai/imagenette

## 実験結果メモ

AutoAugmentをImageNet用にせずCIFAR用のままにしてるくらいには雑な結果。

### trainとvalを逆にした版

```txt
[INFO ] Arguments: --data=imagenette --model=resnet
[INFO ] Validation Accuracy:      0.785
[INFO ] Validation Cross Entropy: 0.777

[INFO ] Arguments: --data=imagewoof --model=resnet
[INFO ] Validation Accuracy:      0.567
[INFO ] Validation Cross Entropy: 1.383
```

### trainとvalを逆にしない版

```txt
[INFO ] Arguments: --data=imagenette --model=resnet
[INFO ] Validation Accuracy:      0.988
[INFO ] Validation Cross Entropy: 0.097

[INFO ] Arguments: --data=imagewoof --model=resnet
[INFO ] Validation Accuracy:      0.894
[INFO ] Validation Cross Entropy: 0.500
```

