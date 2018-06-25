---
name: Get base filename
language: java
version: 7+
libraries:
- id: commons-io/commons-io/2.6
read_more:
- http://commons.apache.org/proper/commons-io/javadocs/api-2.5/org/apache/commons/io/FilenameUtils.html#getBaseName(java.lang.String)
---
Use the `FilenameUtils` class with a full path, or just a file name to get the base name without the extension.

```java
String ext = FilenameUtils.getBaseName("/path/to/file/foo.txt");
// returns "foo"

String ext2 = FilenameUtils.getBaseName("bar.exe");
// returns "bar"
```
