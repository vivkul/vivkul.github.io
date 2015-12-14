---
layout: post
title:  "Preparedness for installing CAFFE"
comments: true
---

[Official website](http://caffe.berkeleyvision.org/installation.html) is helpful in providing the directions for installations and solutions to problems, if encountered, can be found online (though not easily). Still, there are some precautions to be taken while installing CAFFE.

- Follow the [prerequisites](http://caffe.berkeleyvision.org/installation.html#prerequisites) religiously.
- CuDNN installation: It takes time to get the product downloaded (around 2 days for approval from NVIDIA) so do it early.
- Changes may be made in Makefile.config (e.g. if BLAS isn't via ATLAS, or libopencv_imgcodecs.so causes undefined reference to symbols, etc) before installation.
- While compiling, it may not find the libraries, so be prepared to create symlinks manually.
- Be prepared to reinstall everything. So, better to keep backups of `build` after each correct step of compilation to save time (there may be segmentation fault while importing caffe in python due to numpy version mis-match, numpy may be required to be reinstalled to integrate with openBLAS)
- Be prepared for jugaad and edit files (a different version of protobuf may be than needed (even different from that mentioned in prerequisites) so commentting a few lines in a file may be required as a shortcut to avoid a lot of hassles otherwise)
