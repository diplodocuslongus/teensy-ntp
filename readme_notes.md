Linking .pio/build/teensy_ntp/firmware.elf
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: .pio/build/teensy_ntp/src/teensy-ntp.cpp.o: in function `updateTime(unsigned long)':
teensy-ntp.cpp:(.text._Z10updateTimem+0x26): undefined reference to `WebContent::setPPSData(unsigned long, unsigned long, unsigned long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0x4c): undefined reference to `NTPClock::getOffset(unsigned long, unsigned long, unsigned long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0x8e): undefined reference to `ClockPID_c::add_sample(unsigned long, unsigned long, long long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0xb2): undefined reference to `NTPClock::setPpb(long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0xd8): undefined reference to `NTPServer::setDispersion(unsigned long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0xe0): undefined reference to `NTPServer::setReftime(unsigned long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0x114): undefined reference to `WebContent::setLocalClock(unsigned long, double, double, double, long, unsigned long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0x192): undefined reference to `NTPClock::setTime(unsigned long, unsigned long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0x1a4): undefined reference to `ClockPID_c::add_sample(unsigned long, unsigned long, long long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0x284): undefined reference to `webcontent'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text._Z10updateTimem+0x294): undefined reference to `ClockPID'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: .pio/build/teensy_ntp/src/teensy-ntp.cpp.o: in function `_GLOBAL__sub_I_gps':
teensy-ntp.cpp:(.text.startup._GLOBAL__sub_I_gps+0x64): undefined reference to `NTPClients::NTPClients()'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.startup._GLOBAL__sub_I_gps+0x6a): undefined reference to `InputCapture::InputCapture()'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.startup._GLOBAL__sub_I_gps+0x84): undefined reference to `NTPServer::NTPServer(NTPClock*)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: .pio/build/teensy_ntp/src/teensy-ntp.cpp.o: in function `setup':
teensy-ntp.cpp:(.text.setup+0x58): undefined reference to `DateTime::DateTime(char const*, char const*)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.setup+0x8e): undefined reference to `InputCapture::begin()'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.setup+0x96): undefined reference to `NTPServer::setup()'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.setup+0x9c): undefined reference to `DateTime::ntptime() const'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.setup+0xac): undefined reference to `NTPClock::setTime(unsigned long, unsigned long)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.setup+0xba): undefined reference to `WebServer::begin()'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.setup+0xc2): undefined reference to `WebContent::begin()'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.setup+0x150): undefined reference to `webserver'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.setup+0x154): undefined reference to `webcontent'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: .pio/build/teensy_ntp/src/teensy-ntp.cpp.o: in function `loop':
teensy-ntp.cpp:(.text.loop+0x6c): undefined reference to `GPSDateTime::decode()'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.loop+0x78): undefined reference to `GPSDateTime::GPSnow()'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.loop+0x7e): undefined reference to `DateTime::ntptime() const'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.loop+0xb4): undefined reference to `NTPClock::getTime(unsigned long, unsigned long*, unsigned long*)'
/home/ludozb/.platformio/packages/toolchain-gccarmnoneeabi-teensy/bin/../lib/gcc/arm-none-eabi/11.3.1/../../../../arm-none-eabi/bin/ld: teensy-ntp.cpp:(.text.loop+0xba): undefined reference to `NTPClients::expireClients()'
collect2: error: ld returned 1 exit status
*** [.pio/build/teensy_ntp/firmware.elf] Error 1
===================================================== [FAILED] Took 3.21 seconds =
