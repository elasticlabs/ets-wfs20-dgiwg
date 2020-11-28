# ETS DGIWG WFS20

Forked from [Official Opengeospatial GitHub repository](https://github.com/opengeospatial/ets-wfs20-dgiwg). 

## Additions 
To ensure proper build with TEAMEngine 5.4 and verisonning aligment with other DGIWG application profile based ETS, we modified the following in `pom.xml`: 
### Fixed version mismatch with tag 
```
<artifactId>ets-wfs20-dgiwg</artifactId>
<version>0.4</version>
```
### Setup consistent versioning with `ets-wfs20` parent ETS to ensure proper build. 
```
<dependency>
  <groupId>org.opengis.cite</groupId>
  <artifactId>ets-wfs20</artifactId>
  <version>1.34</version>
</dependency>
```

