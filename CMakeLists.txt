cmake_minimum_required(VERSION 3.13.4)
project(ymfm)

add_library(ymfm
    src/ymfm_adpcm.h
    src/ymfm_adpcm.cpp
    src/ymfm_fm.h
    src/ymfm_fm.ipp
    src/ymfm_misc.h
    src/ymfm_misc.cpp
    src/ymfm_opl.h
    src/ymfm_opl.cpp
    src/ymfm_opm.h
    src/ymfm_opm.cpp
    src/ymfm_opn.h
    src/ymfm_opn.cpp
    src/ymfm_opq.h
    src/ymfm_opq.cpp
    src/ymfm_opx.h
    src/ymfm_opz.h
    src/ymfm_opz.cpp
    src/ymfm_pcm.h
    src/ymfm_pcm.cpp
    src/ymfm_ssg.h
    src/ymfm_ssg.cpp
    src/ymfm.h
)