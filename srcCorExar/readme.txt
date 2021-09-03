make
cp corExar /sbin/
cp 99-corExar.rules /etc/udev/rules.d/
udevadm control --reload

// Replug device.
