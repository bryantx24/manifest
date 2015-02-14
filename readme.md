# SaberSunset #

## About ##

SaberSunset is a project that has it's main focus on performance and stability.
We improve the Android experience as it's maximum by using custom toolchains, in this case, [SaberMod](https://github.com/SaberMod),
together custom scripts and build flags.

You can know more about all this Android concept reading these articles:

[Truth behind Buzzwords](https://docs.google.com/document/d/1C-ehLWl6XcStOmB30QHDA_DOdceXiGIyzXT_0eIg5nQ/edit)

[GCC Optimizations](https://gcc.gnu.org/onlinedocs/gcc/Optimize-Options.html)

[Graphite](https://gcc.gnu.org/wiki/Graphite-4.8)

[GCC Index](https://gcc.gnu.org/onlinedocs/gcc/)

[Strict-Aliasing](http://dbp-consulting.com/tutorials/StrictAliasing.html)

[Suppressing Warnings](http://dbp-consulting.com/tutorials/SuppressingGCCWarnings.html)

Knowlegde is for free, and a good reading is always welcome. There are too many more articles and information
about all these subjects, but the links above provide really helpful ones, mainly for developers.

## Initialize ##

To get started with SaberSunset, you'll need to get familiar with [Github](https://help.github.com/)

To initialize your local repository using the SaberSunset trees, use this command:

    repo init -u https://github.com/SaberSunset/manifest.git -b ss5.0

## Getting Source ##

    repo sync -f -jx
	
x is the number of your cpu processors + 1.

## Building ##

    . build/envsetup.sh
    lunch
    make -jx otapackage

x is the number of your cpu processors + 1.  

## Thanks ##

Organizations:

AOSPA-Legacy Team \
SlimRoms \
CyanogenMod \
LG-Devs \
SlimSaber \
SimpleAOSP \
Optipop \
SaberMod

Developers:

pbeeler \
Cl3Kener \
frap129 \
darkobas \
fusionjack \
IAmTheOneTheyCallNeo \
Snuzzo \
arcardinal

And many other that I possible couldn't remember...
