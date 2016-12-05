# JCoinche
The famous french game : Belote with additionals rules

## Build

In the root directory :

$> gradle build

## Server

Default port server : 4242

$> java -jar jcoinche_server/build/libs/jcoinche_server.jar

## Console Client

$> java -jar jcoinche_client/build/libs/jcoinche_client.jar [ip] [port]

## Graphic Client

$> java -Djava.library.path="./lwjgl" -jar jcoinche_slick2d/build/libs/jcoinche_slick2d.jar [ip] [port]

## Platforms

Server and Console client are working on windows, linux and mac.
Graphic client is only available on Mac and Linux.
