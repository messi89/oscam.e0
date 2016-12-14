# Oscam E0 Readers & Cacheex patch

This patch improve oscam compatiblity with the new E0.

Author: [Messi89](https://github.com/messi89)

## Building OSCam with this patch

- Get the lastest oscam sources from SVN:
    svn checkout http://www.streamboard.tv/svn/oscam/trunk oscam-svn

- Save the e0-reader-cacheex.patch file:
    wget 

- Go to oscam-svn directory:
    cd oscam-svn

- Patch the source with the EMU patch:
    patch -p0 < ../e0-reader-cacheex.patch
    
- OR: Instead of 'patch', you may also use 'svn patch':
    svn patch ../e0-reader-cacheex.patch
  
- Run `./config.sh -g` to choose the features you want.

- Run `make` to compile OSCam.
