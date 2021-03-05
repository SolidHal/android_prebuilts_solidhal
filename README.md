# SolidHals prebuilt apks

a collection of apks that don't already have up to date distribution on fdroid. can be built into a rom by including the following in a `manifest.xml`

```
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	  <project name="SolidHal/android_prebuilts_solidhal" path="prebuilts/solidhal" remote="github" revision="master" />
</manifest>
```
