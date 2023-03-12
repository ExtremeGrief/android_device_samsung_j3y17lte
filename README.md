# TWRP device tree for the Samsung Galaxy J3 2017 (SM-J330X; j3y17lte)

## Build Steps

```bash
# Make sure you've synced the TWRP android-9.0
# source.

$ . build/envsetup.sh # Prepare build environment.
$ lunch omni_j3y17lte-eng # 'Lunch' the j3y17lte configuration.
$ mka recoveryimage # Build.
```

## License

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
```

This tree is based on: https://github.com/hendramanudinata03/android_device_samsung_j4lte.
