# Bentso working group tasks

## bentso 0.1 release

Lead: Chris Mutel

checklist:

- [x] Store ENTSO API key as environment variable
- [x] CI for linux and windows
- [x] CI for test coverage 
- [x] Auto-building docs 
- [x] Register package on PyPI
- [x] Cache data retrieved from ENTSO in default directory
- [x] Use caches from other directories/network mounts
- [x] Simple interface to specify data to retrieve

### Inputs

 - query meeting ENTSO specification, expressed in terms of b

### Outputs

 - pickled query responses

### Reproducibility objectives

 - DataPackaged query responses
 - provenance metadata (host, query, timestamp, client + server version)
 - attribution metadata (?)
