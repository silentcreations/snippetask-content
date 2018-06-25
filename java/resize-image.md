---
name: Resize image
language: java
version: 8+
read_more:
    - "https://github.com/Animosity/CraftIRC/wiki/Complete-idiot's-introduction-to-yaml"
    - "https://getbootstrap.com/docs/4.0/layout/grid/#vertical-alignment"
---
In Java, to resize (or scale) an image read from an image file and save the scaled image into another image file, we can follow these steps:

```java
public static void resize(String inputImagePath, String outputImagePath, double percent) {
        File inputFile = new File(inputImagePath);
        BufferedImage inputImage = ImageIO.read(inputFile);
        int scaledWidth = (int) (inputImage.getWidth() * percent);
        int scaledHeight = (int) (inputImage.getHeight() * percent);
        resize(inputImagePath, outputImagePath, scaledWidth, scaledHeight);
    }
}
```
