# pallet-all

An all-in-one dependency for [pallet](https://github.com/hugoduncan/pallet) and
[pallet-crates](https://github.com/hugoduncan/pallet-crates).

See [palletops](http://palletops.com) for an overview.

[API documentation](https://hugoduncan.github.com/pallet) is available.

## Support

[On the group](http://groups.google.com/group/pallet-clj), or #pallet on freenode irc.

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

### Quickstart

If you just want to try out pallet, then you can follow these instructions:

- git clone https://github.com/hugoduncan/pallet-all

- Install [Leiningen](http://github.com/technomancy/leiningen).

- In a shell, go to the directory containing the pallet source code and enter

        $ lein deps
        $ lein compile-java
        $ lein repl

You should now have a working repl, which you can use to explore pallet.  You
might want to make the basic pallet commands available without namespace prefix
by typing the following at the repl.

        user> (use 'pallet.repl)
	user> (use-pallet)

## Todo

Make password handling shell character safe.
Add progress reporting.

## See also
[chef](http://wiki.opscode.com/display/chef/Home),
[crane](http://github.com/bradford/crane),
[jclouds](http://github.com/jclouds/jclouds)

## License

Licensed under [EPL](http://www.eclipse.org/legal/epl-v10.html)
