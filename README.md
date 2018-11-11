# module-roundcornerfix

Fix the round corner display for Mix2s with AOSP based ROM.

By: add an overlay apk to `/system/vendor/overlay` to fix the corner display.

It won't affect your screenshot like some roundcorner apps.

WARNING:Do NOT install this module in MIUI.

Tested on Mix2s with Pixel Experience GSI PIE.

Tip: If you are using GSI and install failed with `phhgsi_arm64_a is not supported`,just edit `/system/build.prop` and change `ro.product.device=phhgsi_arm64_a` to `ro.product.device=polaris`, reboot and install.

Before: https://photos.app.goo.gl/5U8ns16vM1z2xKf98 (right angle due to manufacturing processes)

After: https://photos.app.goo.gl/GBssPJ2ZLun5TkTw5 (round corner added to make it smooth)


# Credits

@topjohnwu 
@Joey Huab

Many thanks.
