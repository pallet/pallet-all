# pallet-all

An all-in-one dependency for [pallet](https://github.com/hugoduncan/pallet) and
[pallet-crates](https://github.com/hugoduncan/pallet-crates).

See [palletops](http://palletops.com) for an overview.

[API documentation](https://hugoduncan.github.com/pallet) is available.

## Support

You can get support on the [mailing
list](http://groups.google.com/group/pallet-clj), or #pallet on freenode irc.

## Quickstart

See the [basic usage](https://github.com/hugoduncan/pallet-examples/tree/master/basic/)
example in the
[pallet-examples](https://github.com/hugoduncan/pallet-examples) project.

## Installation

Pallet-all is distributed as a jar, and is available in the
[sonatype repository](http://oss.sonatype.org/content/repositories/releases/org/cloudhoist).

Installation is with [Leiningen](http://github.com/technomancy/leiningen),
maven, or your favourite maen repository aware build tool.

### lein/cake project.clj

    :dependencies [[org.cloudhoist/pallet-all "0.4.0-SNAPSHOT"]]
    :repositories {"sonatype"
                   "http://oss.sonatype.org/content/repositories/releases"
                   "sonatype-snapshots"
                   "http://oss.sonatype.org/content/repositories/snapshots"}

### maven pom.xml

    <dependencies>
      <dependency>
        <groupId>org.cloudhoist</groupId>
        <artifactId>pallet-all</artifactId>
        <version>0.4.0-SNAPSHOT</version>
      </dependency>
    <dependencies>

    <repositories>
      <repository>
        <id>sonatype</id>
        <url>http://oss.sonatype.org/content/repositories/releases</url>
      </repository>
      <repository>
        <id>sonatype-snapshots</id>
        <url>http://oss.sonatype.org/content/repositories/snapshots</url>
      </repository>
    </repositories>

## Dependencies

* JDK 1.6
* Maven 2.2.1

## License

Licensed under [EPL](http://www.eclipse.org/legal/epl-v10.html)

Copyright (c) 2010 Hugo Duncan
