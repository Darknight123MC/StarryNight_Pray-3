# StarryNight Pray 3 | 星夜祈临 3

## Start up parameters | 启动参数
```
-XX:+AggressiveOpts -XX:+UseCompressedClassPointers -XX:+UseCompressedOops -XX:+UseConcMarkSweepGC -XX:+UseParNewGC -XX:+CMSConcurrentMTEnabled -XX:ParallelGCThreads=8 -Dsun.rmi.dgc.server.gcInterval=3600000 -XX:+UnlockExperimentalVMOptions -XX:+ExplicitGCInvokesConcurrent -XX:MaxGCPauseMillis=50 -XX:+AlwaysPreTouch -XX:+UseStringDeduplication -Dfml.ignorePatchDiscrepancies=true -Dfml.ignoreInvalidMinecraftCertificates=true -XX:-OmitStackTraceInFastThrow -XX:+OptimizeStringConcat -XX:+UseAdaptiveGCBoundary -XX:NewRatio=3 -XX:+UseFastAccessorMethods -Dfml.readTimeout=90 -Dfml.queryResult=confirm -Dusing.aikars.flags=mcflags.emc.gs
```