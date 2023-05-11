# ace-dht-logging
DHT logging for the Java implementation of the ACE framework

## Usage

Add dependency

```
    <groupId>it.cnr.iit</groupId>
    <artifactId>ace-dht-logging</artifactId>
    <version>0.0.1</version>
```

to your `ace-java` project and you are ready to communicate with the DHT through websockets.

---

`ace-java` projects out there:
 
1) [RISE Implementation](https://bitbucket.org/marco-tiloca-sics/ace-java/)
2) [CNR Implementation](https://github.com/Daven00/ace-java) (forked from [1.](https://bitbucket.org/marco-tiloca-sics/ace-java/))
    -  `ucs` branch contains Usage Control as decision maker and implementation of [revoked-token-notification](https://datatracker.ietf.org/doc/draft-ietf-ace-revoked-token-notification/) draft.
    - `sifis-home` branch extends the `ucs` branch to integrate it within the [SIFIS-Home](https://github.com/sifis-home/) framework.
3) [RISE Implementation #2](https://github.com/rikard-sics/sifis-home/tree/master/ace) (forked from [1.](https://bitbucket.org/marco-tiloca-sics/ace-java/))

[2.](https://github.com/Daven00/ace-java) and [3.](https://github.com/rikard-sics/sifis-home/tree/master/ace) are currently using logging to the DHT. That's why this repo has been created: to be used as a dependency.