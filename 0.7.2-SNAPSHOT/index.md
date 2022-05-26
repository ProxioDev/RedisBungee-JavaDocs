# Java docs:

## API [Click here](./RedisBungee-API)
## Bungeecord Events  [Click here](./RedisBungee-BungeeEvents)

## Implementing RedisBungee in your plugin: [![RedisBungee Build](https://github.com/proxiodev/RedisBungee/actions/workflows/maven.yml/badge.svg)](https://github.com/Limework/RedisBungee/actions/workflows/maven.yml) [![](https://jitpack.io/v/limework/redisbungee.svg)](https://jitpack.io/#limework/redisbungee)

RedisBungee is distributed as a [maven](https://maven.apache.org) project.

first, install it to your maven local repo as we don't have public maven repo.
```
git clone https://github.com/ProxioDev/RedisBungee.git
cd RedisBungee
mvn clean install
```
then to import for bungeecord use:
```
<dependency>
        <groupId>com.imaginarycode.minecraft</groupId>
        <artifactId>RedisBungee-Bungee</artifactId>
        <version>0.7.2-SNAPSHOT</version>
        <scope>provided</scope>
</dependency>
```
Second method by using jitpack [![](https://jitpack.io/v/limework/redisbungee.svg)](https://jitpack.io/#limework/redisbungee)

first, add this repository
```
	<repositories>
		<repository>
		    <id>jitpack.io</id>
		    <url>https://jitpack.io</url>
		</repository>
	</repositories>
```
then add this in your dependencies
```
	<dependency>
	    <groupId>com.github.limework.redisbungee</groupId>
	    <artifactId>RedisBungee</artifactId>
	    <version>0.7.2</version>
	</dependency>
	
```


