# Pencil
PencilKit 扩展、图片编辑组件

```
pod 'CaamDauPencil'
```

<p>
  <img src="https://github.com/liucaide/Images/blob/master/CaamDau/pencil1.png" width="15%" />
  <img src="https://github.com/liucaide/Images/blob/master/CaamDau/pencil2.png" width="25%" />
</p>

```
if #available(iOS 13.0, *) {
    PencilDraw.show(imageView.image ?? Assets().logo_0, drawing: drawing as? PKDrawing ?? PKDrawing()) { [weak self](draw, image) in
        self?.drawing = draw
        self?.imageView.image = image
    }
} else {
    
}
```
