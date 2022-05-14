# EE_CORES
Compilation of official EmuELEC libretro cores and some experimental ones.

This repository includes some of the original compilations of libretro cores that are already included in the official EmuELEC releases, I will try to keep it as up to date as possible.

How?,you can extract any core from another version with the same name and drop it to /TMP/CORES ("cores" folder if using network share) and replace the ones there, you might want to make a copy of the original first to replace it, in any case they will all be reset by resetting system scripts.

The idea is also to add some random experimental (unofficial) cores for testing, if there is no replacement core (new or different name) copy the xxxx_libretro.so to /tmp/cores (or Cores in the shared resource network) then edit es_systems.cfg, add the corresponding core to the section you want to appear, or create a new one for that core, restart ES and now you should be able to run that core directly, but note that you might not get better performance of random cores.

The ultimate goal of the repository is to make it easier for those who work better with older builds (usually lower-middle-range devices) and/or to test new others. the idea would be to integrate it into ES at some point by the developer, but only as a possibility, not sure.

All credit to ShantiGilbert, developer of EmuELEC.
