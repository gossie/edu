Event Driven Updates
====================

[![Build Status](https://travis-ci.org/encoway/edu.svg?branch=master)](https://travis-ci.org/encoway/edu)

Event Driven Updates (EDU) helps decoupling components of AJAX heavy JSF UIs.

EDU does so by allowing components to request being re-rendered/updated based on an **event**.
An event in terms of EDU is just a name through which it can be referenced by a triggering component e.g., *configuration-changed*.

## Usage

For usage instructions see module `edu`.

## Integration

In order to use EDU in a web application the `edu.jar` must be present on the classpath.

### Maven

Add the folowing dependency to the `<dependencies>` section in a POM:

```xhtml
<dependency>
    <groupId>com.encoway</groupId>
    <artifactId>edu</artifactId>
    <version>X.Y.Z</version>
</dependency>
```

## License

EDU is licensed under Apache 2.0.
