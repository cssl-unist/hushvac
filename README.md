# Efficient Use-after-Free Prevention with Opportunistic Page-Level Sweeping

## Usage
### Run an application with HushVac
```
make
```
To replace malloc for all dynamically linked binaries running within a shell, use
```
LD_PRELOAD=$(pwd)/libhushvacnpmt.so

```
For example,
```
LD_PRELOAD=$(pwd)/libhushvacnpmt.so vi READMe.md
```

## Authors
- Chanyoung Park (UNIST)    chanyoung@unist.ac.kr
- Hyungon Moon (UNIST)      hyungon@unist.ac.kr


## Publications
```
@inproceedings{Park_2024,
  series={NDSS 2024},
  title={Efficient Use-After-Free Prevention with Opportunistic Page-Level Sweeping},
  url={http://dx.doi.org/10.14722/ndss.2024.24804},
  DOI={10.14722/ndss.2024.24804},
  booktitle={Proceedings 2024 Network and Distributed System Security Symposium},
  publisher={Internet Society},
  author={Park, Chanyoung and Moon, Hyungon},
  year={2024},
  collection={NDSS 2024}
}
```
