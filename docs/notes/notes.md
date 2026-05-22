
# Loose Ideas
- In [src/fake_rtc.c](../../src/fake_rtc.c), time does not tick if `OW_FLAG_PAUSE_TIME` is set, and there's a manual time set function too. This would solve one of my problems of playing at all hours and being stuck always at night because it's realtime. Enable the fake clock in [overworld.h](../../include/config/overworld.h), and set the flag here too.
