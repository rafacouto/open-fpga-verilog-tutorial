
# Synthesis and upload with PlatformIO

You only need to install [PlatformIO CLI][PIO01]:

    pip install -U platformio

There is a project file _platformio.ini_ under each directory of the tutorial example. Enter into that directory and execute the _pio_ command to synthesize the hardware and upload the bitstream to your plugged board in:

## icestick1k

Environment created to [Lattice iCEstick ICE40-HX1K][ICE01].

    pio run -e icestick1k -t upload

## icezum

Environment created to [IceZUM Alhambra][ICE02].

    pio run -e icezum -t upload


[ICE01]: http://www.pighixxx.com/test/portfolio-items/icestick/
[ICE02]: http://www.pighixxx.com/test/portfolio-items/icezum/
[PIO01]: http://platformio.org/get-started/cli

