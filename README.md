# Hyperium is no longer available.

Hyperium is no longer available, and we will no longer provide support for it. [Click here](https://https://github.com/asbyth/Hyperium-Replacements) to find a list of replacement Forge mods.

## Development Setup

You will first need to set up a development workspace with the Hyperium source code. You can do this by downloading the repository, opening the `build.gradle` as a project in IntelliJ IDEA and running the following commands from terminal or gradle window.

```bash
./gradlew setupDecompWorkspace
./gradlew genIntellijRuns
```

![Image of project](https://media.discordapp.net/attachments/747901986770518047/750929662795972740/Screen_Shot_2020-09-02_at_11.06.15_PM.png)

This will download the dependencies and setup the run configuration for the project allowing you to run the client from your IDE. If the game will still not run after you have completed these steps make sure the `Minecraft Client` run configuration is set to the module `Hyperium.main`.
