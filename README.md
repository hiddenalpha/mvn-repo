
Maven Artifacts
===============

Mainly intended to have fixes available early of forks which did not yet
release the urgently required artifact.

Several times already, I had the problem of clients in timely pressure
needing a patch ASAP, with no time to wait for an official release.

WARNING: DO NOT RELY ON THOSE ARTIFACTS TO EXIST FOREVER! IF YOU REALLY
NEED THEM FOR A LONGER TIME, MAKE SURE YOU STORE YOUR OWN COPY SOMEWHERE
ELSE.



## Usage

Browse through here and download the JARs you need. Then add them to
your project manually (make sure you backup the downloaded JARs, just in
case you need them later).



## Usage (example via maven)

```
<project>
	<repositories>
		<repository>
			<id>hiddenalpha-mvn-repo</id>
			<url>https://github.com/hiddenalpha/mvn-repo/raw/refs/heads/main/</url>
			<releases><enabled>true</enabled></releases>
			<snapshots><enabled>true</enabled></snapshots>
		</repository>
	</repositories>
	<dependencies>
		<dependency>
			<groupId>io.github.java-native</groupId>
			<artifactId>jssc</artifactId>
			<version>2.10.3-hiddenalpha.1</version>
			<classifier>enbloated</classifier>
		</dependency>
	</dependencies>
</project>
```

