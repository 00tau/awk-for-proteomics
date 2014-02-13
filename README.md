awk-for-proteomics
==================

Small scripts for data manipulation

To use you need to clone this repository.  After that you may need to make the
scripts executable but then you are good to go.  For example to produce a new
mgf-file from a given mgf-file but with all the highest intensities deleted,
you simply run:

```
% git clone https://github.com/00tau/awk-for-proteomics.git
% cd awk-for-proteomics
% chmod +x nothighest
% ./nothighest myold.mgf > mynew.mgf
```

If you know that you have access to a Linux system but you don't know how, you
may ask your system administrator to assist you.
