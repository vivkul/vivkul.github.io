---
layout: post
title:  "Preparedness for installing CAFFE"
---

Official website is good. Solutions can definitely be found online.
possible precautions:
Follow the prerequisites religiously
CuDNN version: It takes time to get the product downloaded (around 2 days)
changes can be made in Makefile.config (e.g. if BLAS isn't via ATLAS, or opencv_imgcodecs is shown to have uninterpretable strings, etc)
while compiling, it may not find the libraries, so be prepared to create symlinks manually
be prepared to reinstall everything, better to keep backups of build to save time(there may be segmentation fault while importing caffe in python due to numpy version mis-match, numpy may be required to be reinstalled to integrate with openBLAS)
be prepared for jugaad and edit files (protobuf may be of different version than needed (even different from that mentioned in pre-requisites) so may be required to comment few lines in a file as a lot of hassles otherwise)
