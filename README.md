
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

Add a repository in your project:

```
<project>
	<repositories>
		<repository>
			<id>hiddenalpha-mvn-repo</id>
			<url>https://github.com/hiddenalpha/mvn-repo/raw/refs/heads/main/</url>
		</repository>
	</repositories>
</project>
```

