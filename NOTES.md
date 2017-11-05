# update-alternatives

`update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/nhos-gnome-logo/nhos-logo.plymouth 160
update-alternatives --install /usr/share/plymouth/themes/text.plymouth text.plymouth /usr/share/plymouth/themes/nhos-gnome-text/nhos-text.plymouth 160
update-alternatives --config default.plymouth
update-alternatives --config text.plymouth
update-initramfs -u
`
