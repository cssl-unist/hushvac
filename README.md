# Efficient Use-after-Free Prevention with Opportunistic Page-Level Sweeping

## Usage
### Run an application with HushVac
```
make
```
To replace malloc for all dynamically linked binaries running within a shell, use
```
LD_PRELOAD=$(pwd)/libhushvaccnpmt.so

```
For example,
```
LD_PRELOAD=$(pwd)/libhushvaccnpmt.so vi READMe.md
```

## Authors
- Chanyoung Park (UNIST)    chanyoung@unist.ac.kr
- Hyungon Moon (UNIST)      hyungon@unist.ac.kr


## Publications
```
```
