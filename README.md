# SugarCaneMC [![Build Status](https://img.shields.io/github/actions/workflow/status/YourUsername/SugarCaneMC/build.yml?branch=main)](https://github.com/YourUsername/SugarCaneMC/actions)
[![Discord](https://img.shields.io/discord/YourDiscordID.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/YourDiscordLink)
[![GitHub Sponsors](https://img.shields.io/github/sponsors/YourUsername?label=GitHub%20Sponsors)](https://github.com/sponsors/YourUsername)
[![Open Collective](https://img.shields.io/opencollective/all/sugarcanemc?label=OpenCollective%20Sponsors)](https://opencollective.com/sugarcanemc)

===========

SugarCaneMC is a high-performance Minecraft server forked from PaperMC, designed to enhance gameplay with unique features and optimizations. Our goal is to provide a seamless and enriched Minecraft experience by addressing gameplay inconsistencies and introducing new mechanics.

**Support and Project Discussion:**
- [Our forums](https://forums.sugarcanemc.io/) or [Discord](https://discord.gg/YourDiscordLink)

## How To (Server Admins)
SugarCaneMC is distributed as a jar file that you can download and run just like a normal jar file.

Download SugarCaneMC from our [downloads page](https://sugarcanemc.io/downloads).

Run the SugarCaneMC jar directly from your server. Just like old times.

* For a sneak peek at upcoming features, [see here](https://github.com/AgentH14/SugarCaneMC/projects)

## How To (Plugin Developers)
* See our API [here](sugarcane-api)
* See upcoming, pending, and recently added API [here](https://github.com/AgentH14/SugarCaneMC))

#### Repository (for sugarcane-api)
##### Maven

```xml
<repository>
    <id>sugarcanemc</id>
    <url>https://repo.sugarcanemc.io/repository/maven-public/</url>
</repository>

<dependency>
    <groupId>io.sugarcanemc</groupId>
    <artifactId>sugarcane-api</artifactId>
    <version>1.0.0-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
