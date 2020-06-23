# Redmi K30 Pro


List preinstalled apps with `adb shell pm list packages`


Uninstall some of them:

```sh
adb shell pm uninstall --user 0 com.miui.systemAdSolution
adb shell pm uninstall --user 0 com.miui.analytics
adb shell pm uninstall --user 0 com.android.browser
adb shell pm uninstall --user 0 com.miui.video
adb shell pm uninstall --user 0 com.miui.player
adb shell pm uninstall --user 0 com.xiaomi.gamecenter.sdk.service
adb shell pm uninstall --user 0 com.xiaomi.gamecenter	# no permission
```
