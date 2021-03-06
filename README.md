# Package Delivery System / System Control Software project

## Why

Explain..

## Getting Started

This repository stores a template project about `EV3Dev-lang-java`. 
Once you download in your computer the project, 
open your favourite Java IDE ( [Eclipse](https://eclipse.org/home/index.php) or [IntelliJ](https://www.jetbrains.com/idea/))
to import this [Gradle](https://gradle.org/) project. The project includes latest dependencies and
an example ready to be deployed on your Robot using the `core` library from `EV3Dev-lang-java`.

The project includes some tasks to reduce the time to deploy on your robot.

Review the IP of your Brick and update the file `deploy.gradle`:

```
remotes {
    ev3dev {
        host = '192.168.1.180'
        user = 'robot'
        password = 'maker'
    }
}
```

The tasks associated to deploy on your robot are:

- deploy (The project deliver a FatJar to your Brick)
- remoteRun (Ejecute a jar deployed on your Brick)
- deployAndRun (Deploy & Execute from your Computer the program that you configured on the file: MANIFEST.MF)

You can use the Java IDE to launch the task or execute them from the terminal

```
./gradlew deployAndRun
```

# Commands

Following commands are available for use in Bricks: 

# Examples

Exist several examples ready to use here:

https://github.com/ev3dev-lang-java/examples
