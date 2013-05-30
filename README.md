# Unidecode #

ASCII transliterations of Unicode string for Java.

Transliterate Unicode string to a upper case initials.

## How to Use ##

Edit pom.xml.

```xml
<dependency>
	<groupId>me.xuender</groupId>
	<artifactId>unidecode</artifactId>
	<version>0.0.3</version>
</dependency>
```

### decode
    System.out.print(Unidecode.decode("南无阿弥陀佛"));
    Nan Wu A Mi Tuo Fo

    System.out.print(Unidecode.decode("あみだにょらい"));
    amidaniyorai

### initials
    System.out.print(Unidecode.initials("南无阿弥陀佛"));
    NWAMTF

    System.out.print(Unidecode.initials("Κνωσός"));
    K

## Links ##

* [![Build Status](https://travis-ci.org/xuender/unidecode.png)](https://travis-ci.org/xuender/unidecode)

## Reference ##

[Unidecode for Python](https://pypi.python.org/pypi/Unidecode)
