# aliBuild

A simple build tool for ALFA software and its externals. 
The tool is a fork of the original [ALICE project](https://github.com/alisw/alibuild) 
Recipes for the externals software are stored in
[alphadist](https://github.com/FairRootGroup/alfadist)

Instant gratification with:

    git clone https://github.com/FairRootGroup/alfabuild.git
    cd alfabuild && git checkout dev && cd - 
    git clone https://github.com/FairRootGroup/alfadist.git
    cd alfadist && git checkout jul15p2_v-15.07a_merge
    alfabuild/alfaBuild -j 8 -a osx_x86-64 --defaults clang build fairsoft

Possible architectures (tested marked with *):

    On Linux, x86-64:
    RHEL5 / SLC5 compatible: slc5_x86-64
    RHEL6 / SLC6 compatible: slc6_x86-64
    RHEL7 / CC7 compatible: slc7_x86-64
    Ubuntu 14.04 compatible: ubuntu1404_x86-64 (*)
    Ubuntu 15.04 compatible: ubuntu1504_x86-64
    Ubuntu 15.10 compatible: ubuntu1510_x86-64

    On Mac, x86-64:
    Mavericks, Yosemite and El-Captain: osx_x86-64 (*)

Possible default files (in alfadist):

    clang
    gcc


Full documentation at:

<https://alisw.github.io/alibuild>
