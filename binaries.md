## Exercise 1

Read the magic word (0b110010101111111010111010101) from a Java class file.
Then read the minor version (2 bytes) and the major version (2 bytes).

You will find a class file in the [binaries_example](binaries_example) directory.

Figure out which version of Java is being used based on the following table:

```text
major version number of the class file format being used.
J2SE 8 = 52 (0x34 hex),
J2SE 7 = 51 (0x33 hex),
J2SE 6.0 = 50 (0x32 hex),
J2SE 5.0 = 49 (0x31 hex),
JDK 1.4 = 48 (0x30 hex),
JDK 1.3 = 47 (0x2F hex),
JDK 1.2 = 46 (0x2E hex),
JDK 1.1 = 45 (0x2D hex).
```

[Answer](https://gist.github.com/brweber2/14a3c847650f60fffa9a26784fa0a643)

## Exercise 2 (BONUS)

Read [binaries_example/lib/java.ex](binaries_example/lib/java.ex) and figure out what it does.
