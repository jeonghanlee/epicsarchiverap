# Logs for Potential Cherry Pick Commits

Today, March 21, 2024, I only found the three commits are my interesting ones to do cherry pick.


* [ ] Commit `dea7acb`
Makes the PV Metric return the last connected state.

```bash
$ git diff --name-only 835061f dea7acb
src/main/org/epics/archiverappliance/engine/model/ArchiveChannel.java
src/main/org/epics/archiverappliance/engine/pv/EPICS_V3_PV.java
src/main/org/epics/archiverappliance/engine/pv/EPICS_V4_PV.java
src/main/org/epics/archiverappliance/engine/pv/PV.java
src/main/org/epics/archiverappliance/engine/pv/PVConnectionState.java
src/main/org/epics/archiverappliance/engine/pv/PVMetrics.java
src/test/org/epics/archiverappliance/engine/test/PVMetricsTest.java
```

* [ ] Commit `87bcebb`
```
$ git diff --name-only 835061f 87bcebb
src/test/org/epics/archiverappliance/engine/test/DoubleBufferTest.java
```

* [ ] Commit `8b4f22e`
```
$ git diff --name-only 835061f 8b4f22e
src/main/org/epics/archiverappliance/retrieval/postprocessors/Optimized.java
src/main/org/epics/archiverappliance/retrieval/postprocessors/SummaryStatsPostProcessor.java
src/test/org/epics/archiverappliance/engine/test/DoubleBufferTest.java
src/test/org/epics/archiverappliance/retrieval/postprocessor/OptimizedPostProcessorTest.java
```


