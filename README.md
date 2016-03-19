## TWRP device tree for Galaxy Note 3 (Japan)

Add to `.repo/local_manifests/hltekdi.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/hltekdi" name="android_device_samsung_hltekdi" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/idleKernel-note3/tree/ik-twrp

