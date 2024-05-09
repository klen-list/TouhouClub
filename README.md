# TouhouClub
![Downloads](https://img.shields.io/github/downloads/Niron3206/TouhouClub/v1.6/total?style=flat-square)

This is local Java project for discord bot, based on JDA library.

You also have to specify token and prefix in `.env` file, which must be created in the root of the project.
The easiest way to do it is to copy the `.env-example` and rename it to `.env`.

You can also build your own maven-jar-application and run it via command console.\
To compile this maven project into jar file, write it in console (don't forget to install maven if you haven't downloaded it yet):

`1. mvn compile`\
`2. mvn package`

You will see compiled jar file in target folder, you also need to copy your .env file with your parameters in target folder.

To open jar file you have to write `java -jar TouhouClub-1.6.jar` in console (you have to be in the same directory as the jar file).
