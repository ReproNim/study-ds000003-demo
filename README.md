# study-ds000003-demo

A small demo [BIDS study](https://bids.neuroimaging.io/extensions/beps/bep_035.html) in the OpenNeuroStudies shape, built by `code/build-study.sh` of the enclosing superstudy.

- `sourcedata/ds000003-demo/` - the raw BIDS dataset, a subdataset of https://github.com/ReproNim/ds000003-demo at `demo-minimized`
- `sourcedata/sourcedata+subjects.tsv`, `sourcedata/sourcedata.tsv` - per-subject and per-dataset metadata, as a real OpenNeuroStudies study carries
- `derivatives/` - where a tool run over this study puts its output
