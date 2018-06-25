---
name: Resize image
language: java
version: 8+
read_more:
- "https://github.com/Animosity/CraftIRC/wiki/Complete-idiot's-introduction-to-yaml"
- "https://getbootstrap.com/docs/4.0/layout/grid/#vertical-alignment"
libraries:
- name: Imgscalr A Java Image Scaling Library
  description: imgscalr is an simple and efficient best-practices image-scaling and manipulation library implemented in pure Java.
  license: Apache 2.0
  language: java
  website: http://www.thebuzzmedia.com/software/imgscalr-java-image-scaling-library/
  dependency_group: org.imgscalr
  dependency_id: imgscalr-lib
  dependency_version: 4.2
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
