# Ru(fonetic) keyboard layout for Linux

If you are looking for a russian phonetic keyboard layout as you got used to on a MacBook, you are in the right place.

Instructions:
* Clone the repo (or download all)
* In the shell:

```bash
cd xkb
cp -r home/user/.config/xkb ~/.config/xkb
```

* Restart your graphical sessions:
```bash
systemctl restart gdm.service
```

* Add `Russian(fonetic)` keyboard layout to you session:
  * In GNOME: `Settings -> Keyboard -> Input Sources` and add `Russian (fonetic)`
  * Check the ![visual layout](/assets/images/ru_fonetic.png] 
