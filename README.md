# Maven-repo for sophea

Two repos are available:
* releases - [https://raw.github.com/sophea/mvn-repo/master/releases](https://raw.github.com/sophea/mvn-repo/master/releases)
* snapshots - [https://raw.github.com/sophea/mvn-repo/master/snapshots](https://raw.github.com/sophea/mvn-repo/master/snapshots)

## Repositories

You can include sophea's repositories in your project's pom.xml:
~~~
    <pluginRepositories>
        <pluginRepository>
            <id>sophea-github-releases</id>
            <name>sophea Maven releases repo at GitHub</name>
            <releases>
                <enabled>true</enabled>
            </releases>
            <snapshots>
                <enabled>false</enabled>
            </snapshots>
            <url>https://raw.github.com/sophea/mvn-repo/master/releases</url>
        </pluginRepository>
    </pluginRepositories>
    <repositories>
        <repository>
            <id>sophea-github-releases</id>
            <name>sophea Maven releases repo at GitHub</name>
            <releases>
                <enabled>true</enabled>
            </releases>
            <snapshots>
                <enabled>false</enabled>
            </snapshots>
            <url>https://raw.github.com/sophea/mvn-repo/master/releases</url>
        </repository>
    </repositories>
~~~


