# NHoS Plymouth theme for Ubuntu/GNOME

This package provides an NHoS theme for the plymouth bootloader.

This theme is based on plymouth-theme-ubuntu-gnome-logo/text provided by ubuntu-gnome-default-settings.

### Packaging for launchpad.net
Build and sign source package

`debuild -S`

Push package to launchpad

`dput -f ppa:nhsbuntu/ppa plymouth-theme-nhos-gnome-logo_0.x.x_source.changes`

### Packaging for packagecloud.io
Build and sign package with key

`dpkg-buildpackage -kemail@address-key.com`

Push package to packagecloud

`package_cloud push nhsbuntu/nhos-default-settings plymouth-theme-nhos-gnome-logo_0.x.x_all.deb`


## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct.

## Authors

* **Rob Dyke** - *NHoS customisations* - [robdyke](https://github.com/robdyke)

## Copyright
* Portions Copyright (C) 2011 Canonical Ltd
* Portions Copyright (C) 2017 Open Health Hub CIC
* Portions Copyright (C) 2017 Neova Health LLP

## License

This project is licensed under the GNU GPL v3 - see the [LICENSE](LICENSE) file for details.
