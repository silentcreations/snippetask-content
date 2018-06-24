---
name: Resize image in Java
language: Java
version: 8+
---
In Java, to resize (or scale) an image read from an image file and save the scaled image into another image file, we can follow these steps:

```
public static void resize(String inputImagePath, String outputImagePath, double percent) {
        File inputFile = new File(inputImagePath);
        BufferedImage inputImage = ImageIO.read(inputFile);
        int scaledWidth = (int) (inputImage.getWidth() * percent);
        int scaledHeight = (int) (inputImage.getHeight() * percent);
        resize(inputImagePath, outputImagePath, scaledWidth, scaledHeight);
    }
}
```
