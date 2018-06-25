---
name: Get file extension
language: java
version: 7+
libraries:
- id: commons-io/commons-io/2.6
read_more:
- http://commons.apache.org/proper/commons-io/javadocs/api-2.5/org/apache/commons/io/FilenameUtils.html#getExtension%28java.lang.String%29
---
Use the `FilenameUtils` class with a full path, or just a file name to get the extension.

```java
String ext = FilenameUtils.getExtension("/path/to/file/foo.txt");
// returns "txt"

String ext2 = FilenameUtils.getExtension("bar.exe");
// returns "exe"
```
