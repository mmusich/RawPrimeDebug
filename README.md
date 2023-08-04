# RawPrimeDebug
Scripts for CMS SiStrip RAW' debugging 
Tested in `CMSSW_12_5_2`.

## Recip to run

```
cmsrel CMSSW_12_5_2
cd CMSSW_12_5_2/src
cmsenv
voms -proxy-init -voms cms 
cmsRun repack_REPACK.py
cmsRun rawprime_RAW2DIGI_L1Reco_RECO.py
```
