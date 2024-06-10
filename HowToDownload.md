# How To Download Tcases Using Maven #

## Tcases Command Line Tools

To get the command line version of Tcases, download the Tcases shell distribution file from the Maven Central Repository, using the following procedure.

  1. Visit the [Central Repository page](https://central.sonatype.com/artifact/org.cornutum.tcases/tcases-shell/4.0.1/versions) for `tcases-shell`.
  1. Find the entry for the latest version and click on "Browse".
  1. To download the shell distribution ZIP file, click on "tcases-shell-_${version}_.zip". If you prefer a compressed TAR file, click on "tcases-shell-_${version}_.tar.gz".

After downloading, see *The Complete Guide* for [tips on installation](./Tcases-Guide.md#installing-the-tcases-distribution).


## Tcases Libraries

You can download the following Tcases libraries as JARs from the Maven Central Repository. Depending on how you want to use Tcases, list one
of the following dependencies in your project POM.

#### tcases-maven-plugin
A Maven plugin to run Tcases. For details, see the [plugin documentation site](http://www.cornutum.org/tcases/docs/tcases-maven-plugin/).

#### [tcases-lib](https://search.maven.org/search?q=g:org.cornutum.tcases%20AND%20a:tcases-lib)
The core models for Tcases objects. For the current version, see the [release notes](ReleaseNotes.md). Prior to 3.0.0, this JAR also contained all other Tcases APIs.

```xml
<dependency>
  <groupId>org.cornutum.tcases</groupId>
  <artifactId>tcases-lib</artifactId>
  <version>...</version>
</dependency>
```

#### [tcases-io](https://search.maven.org/search?q=g:org.cornutum.tcases%20AND%20a:tcases-io)
(Since 3.0.0) Supports reading and writing Tcases objects from external documents. For the current version, see the [release notes](ReleaseNotes.md).

```xml
<dependency>
  <groupId>org.cornutum.tcases</groupId>
  <artifactId>tcases-io</artifactId>
  <version>...</version>
</dependency>
```

#### [tcases-cli](https://search.maven.org/search?q=g:org.cornutum.tcases%20AND%20a:tcases-cli)
(Since 3.0.0) Command line tools for running Tcases. For the current version, see the [release notes](ReleaseNotes.md).

```xml
<dependency>
  <groupId>org.cornutum.tcases</groupId>
  <artifactId>tcases-cli</artifactId>
  <version>...</version>
</dependency>
```

#### [tcases-openapi](https://search.maven.org/search?q=g:org.cornutum.tcases%20AND%20a:tcases-openapi)
(Since 3.1.0) Converts an OpenAPI v3 definition into test cases for a REST-ful API. For the current version, see the [release notes](ReleaseNotes.md).

```xml
<dependency>
  <groupId>org.cornutum.tcases</groupId>
  <artifactId>tcases-openapi</artifactId>
  <version>...</version>
</dependency>
```

#### [tcases-openapi-test](https://search.maven.org/search?q=g:org.cornutum.tcases%20AND%20a:tcases-openapi-test)
(Since 3.8.0) Provides runtime support for tests generated by Tcases for OpenAPI. For the current version, see the [release notes](ReleaseNotes.md).

```xml
<dependency>
  <groupId>org.cornutum.tcases</groupId>
  <artifactId>tcases-openapi-test</artifactId>
  <version>...</version>
</dependency>
```

#### [tcases-rest-assured](https://search.maven.org/search?q=g:org.cornutum.tcases%20AND%20a:tcases-rest-assured)
(Since 3.4.0) Provides a [`TestCaseWriter`](http://www.cornutum.org/tcases/docs/api/org/cornutum/tcases/openapi/restassured/RestAssuredTestCaseWriter.html)
implementation for [REST Assured](https://github.com/rest-assured/rest-assured).
For the current version, see the [release notes](ReleaseNotes.md).

```xml
<dependency>
  <groupId>org.cornutum.tcases</groupId>
  <artifactId>tcases-rest-assured</artifactId>
  <version>...</version>
</dependency>
```

#### [tcases-moco](https://search.maven.org/search?q=g:org.cornutum.tcases%20AND%20a:tcases-moco)
(Since 3.4.0) Provides a [`TestWriter`](http://www.cornutum.org/tcases/docs/api/org/cornutum/tcases/openapi/moco/MocoServerTestWriter.html)
implementation for JUnit API tests using a [Moco](https://github.com/dreamhead/moco) stub server.
For the current version, see the [release notes](ReleaseNotes.md).

```xml
<dependency>
  <groupId>org.cornutum.tcases</groupId>
  <artifactId>tcases-moco</artifactId>
  <version>...</version>
</dependency>
```

#### [tcases-ant](https://search.maven.org/search?q=g:org.cornutum.tcases%20AND%20a:tcases-ant)
(Since 2.0.0) Provides an Ant task for running Tcases. For the current version, see the [release notes](ReleaseNotes.md).

```xml
<dependency>
  <groupId>org.cornutum.tcases</groupId>
  <artifactId>tcases-ant</artifactId>
  <version>...</version>
</dependency>
```