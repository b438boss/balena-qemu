Change log
-----------

# v2.29.2+rev2
## (2019-02-26)

# v2.29.2+rev1
## (2019-01-17)

* Update the meta-resin submodule from v2.26.0 to v2.29.2 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.29.0
### (2018-12-19)

* OS will default apps.json to an empty json file [Andrei Gherzan]
* Update balena-engine to include low entropy fixes [Andrei Gherzan]
* Move an NM patch to the right place to reduce a warning [Zubair Lutfullah Kakakhel]
* Update balena-supervisor to v9.0.1 [Pablo Carranza Velez]
* Fix cases where RESIN_BOOT_PARTITION_FILES includes invalid entries [Andrei Gherzan]
* Enable some common linux kernel serial device drivers [Andrei Gherzan]
* Configure NetworkManager to only ignore our vpn interface but manage other tun devices [Andrei Gherzan]
* networkmanager: Add pppd to FILES [Zubair Lutfullah Kakakhel]
* networkmanager: Add balena-client-id.patch in bbappend [Zubair Lutfullah Kakakhel]
* Bump network manager from v1.12.2 to v1.14.4 [Zubair Lutfullah Kakakhel]
* Update balena-supervisor to v8.7.0 [Pablo Carranza Velez]
* Fix test cases for kernel module header compilation [Zubair Lutfullah Kakakhel]
* Add chrony v3.2 recipe in various layers to keep minimum chrony version on devices above v3.2 [Zubair Lutfullah Kakakhel]
* chrony/pyro: Add v3.2 recipe [Zubair Lutfullah Kakakhel]
* chrony/morty: Add v3.2 recipe [Zubair Lutfullah Kakakhel]
* chrony/krogoth: Bump recipe version to v3.2 [Zubair Lutfullah Kakakhel]
* Update resin-supervisor to v8.6.8 [Zubair Lutfullah Kakakhel]

## meta-resin-2.28.0
### (2018-12-05)

* Update os-config to 1.0.0 [Zahari Petkov]
* Update libqmi to version 1.20.2 [Florin Sarbu]
* Update libmbim to version 1.16.2 [Florin Sarbu]
* kernel-modules-headers: Add basic sanity test [Zubair Lutfullah Kakakhel]
* Fix kernel module header generation [Zubair Lutfullah Kakakhel]
* image-resin.bbclass: Fix config.json pretty format [Andrei Gherzan]
* Allow supervisor update on unmanaged devices [Andrei Gherzan]
* Update resin-supervisor to v8.6.3 [Cameron Diver]

## meta-resin-2.27.0
### (2018-11-23)

* Expose randomMacAddressScan config.json knob [Andrei Gherzan]
* Move modemmanager udev rules in /lib/udev/rules.d [Andrei Gherzan]
* Fix modemmanager bbappend files [Andrei Gherzan]
* dnsmasq: Define 8.8.8.8 as a fallback nameserver [Andrei Gherzan]
* Increase timeout for filesystem label [Vicentiu Galanopulo]
* Add support for Huawei ME936 modem in MBIM mode [Florin Sarbu]
* Backport systemd sd-shutdown improvements for sumo versions [Florin Sarbu]
* Include avahi d-bus introspection files in rootfs [Andrei Gherzan]
* Fix custom udev rules when rule is removed from config.json [Zubair Lutfullah Kakakhel]
* resin-mounts: Add NetworkManager conf.d bind mounts [Zubair Lutfullah Kakakhel]
* Add support to pass custom configuration to NetworkManager [Zubair Lutfullah Kakakhel]
* README.md: Add info about SSH and Avahi services [Andrei Gherzan]
* Avoid xtables lock in resin-proxy-config [Andrei Gherzan]
* Migrate the supervisor to balena repositories [Florin Sarbu]
* Update balena-supervisor to v8.3.5 [Cameron Diver]
* Update supported modems list [Florin Sarbu]
</details>

# v2.26.0+rev3
## (2019-01-14)

# v2.26.0+rev2
## (2018-12-17)

* Switch from resin-yocto-scripts to balena-yocto-scripts [Florin Sarbu]

# v2.26.0+rev1
## (2018-11-07)

* Update the meta-resin submodule from v2.25.0 to v2.26.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.26.0
### (2018-11-05)

* Rename resin-unique-key to balena-unique-key [Andrei Gherzan]
* Don't let resin-unique-key rewrite config.json [Andrei Gherzan]

## meta-resin-2.25.0
### (2018-11-02)

* Generate ssh host key at first boot (not at first connection) [Andrei Gherzan]
* Fix extraneous space in kernel-resin.bbclass config [Florin Sarbu]
* Drop obsolete eval from kernel-resin's do_kernel_resin_reconfigure [Florin Sarbu]
* Add SyslogIdentifier for balena and resin-supervisor healthdog services [Matthew McGinn]
</details>

* Update the resin-yocto-scripts submodule to master HEAD [Florin Sarbu]

# v2.25.0+rev1
## (2018-11-05)

* Update the meta-resin submodule from v2.21.0 to v2.25.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.25.0
### (2018-11-02)

* Generate ssh host key at first boot (not at first connection) [Andrei Gherzan]
* Fix extraneous space in kernel-resin.bbclass config [Florin Sarbu]
* Drop obsolete eval from kernel-resin's do_kernel_resin_reconfigure [Florin Sarbu]
* Add SyslogIdentifier for balena and resin-supervisor healthdog services [Matthew McGinn]

## meta-resin-2.24.1
### (2018-11-01)

* Update resin-supervisor to v8.0.0 [Pablo Carranza Velez]

## meta-resin-2.24.0
### (2018-10-24)

* resin-info: Small tweak for balenaCloud product [Andrei Gherzan]
* Update resin-supervisor to v7.25.8 [Pablo Carranza Velez]
* Rename resinOS to balenaOS [Andrei Gherzan]

## meta-resin-2.23.0
### (2018-10-22)

* Update resin-supervisor to v7.25.5 [Cameron Diver]
* recipes-containers: Increase healthcheck timeout to 180s [Gergely Imreh]
* .gitignore: add node_modules and package-lock files [Giovanni Garufi]

## meta-resin-2.22.1
### (2018-10-20)

* Update resin-supervisor to v7.25.3 [Pablo Carranza Velez]

## meta-resin-2.22.0
### (2018-10-19)

* Update resin-supervisor to v7.25.2 [Andrei Gherzan]
* Include a CONTRIBUTING.md file [Andrei Gherzan]
* Update to ModemManager v1.8.2 [Andrei Gherzan]
* Updates on contributing-device-support.md [Vicentiu Galanopulo]

## meta-resin-2.21.0
### (2018-10-18)

* Improve systemd service ordering in rollbacks [Zubair Lutfullah Kakakhel]
* Update resin-supervisor to v7.24.1 [Andrei Gherzan]
</details>

* Update autohat v0.0.5 [Andrei Gherzan]

# v2.21.0+rev1
## (2018-10-18)

* Update the meta-resin submodule to v2.21.0 [Andrei Gherzan]

<details>
<summary> View details </summary>

## meta-resin-2.21.0
### (2018-10-18)

* Improve systemd service ordering in rollbacks
* Update resin-supervisor to v7.24.1

## meta-resin-2.20.0
### (2018-10-18)

* Avoid expander on flasher based on root kernel argument
* Resin-vars: Implement custom ssh keys service
* Fix redsocks interface creation when no proxy configured
* Replace NM's DHCP request option "Client indentifier" with udhcpc style option
* Fix for rollbacks in case of old balenaOS version
* Update resin-supervisor to v7.21.4
* Warn if rules are found in /etc/udev/rules.d
* Add support to load custom udev rules from config.json
* Aufs-util: Package auplink separately
* Enable kernel config dependencies for MBIM and QMI
* Set UPX to use LZMA compression by default
* Downgrade UPX to 3.94 for ARM
* Balena update for rollbacks. mobynit can now mount rootfs from sysroot.
* Fix proxy when using containers over bridge network
* Add support for aufs 4.9.9+, 4.9.94+, 4.18
* Add rollback-altboot service before balena service
* Add Automated Rollback recipe
* Add Automated Rollback support in u-boot env_resin.h
* Add a hook to support Automated Rollbacks
* Update HUP grub hook to support Automated Rollbacks
* Update HUP u-boot hook to support Automated Rollbacks
* Move kernel-image-initramfs from resin-image recipe to packagegroup-resin.inc
* Have 99-resin-grub hostapp-update-hook decide which grub to use

## meta-resin-2.19.0
### (2018-09-23)

* Update Balena to fix tty console hanging in some cases
* Pin down cargo deps (using Cargo.lock) to versions known working with rust 1.24.1 (for sumo)
* Remove duplicate packaging of bcm43143
* Set ModemManager to ignore Inca Roads Serial Device
* Add support for aufs 4.14.56+
* Update resin-supervisor to v7.19.7
</details>

# v2.19.0+rev2
## (2018-09-27)

* Update autohat v0.0.3 [Horia Delicoti]

# v2.19.0+rev1
## (2018-09-25)

* Update the meta-resin submodule to v2.19.0 [Florin Sarbu]

<details>
<summary> View details </summary>

## meta-resin-2.19.0
### (2018-09-23)

* Update Balena to fix tty console hanging in some cases
* Pin down cargo deps (using Cargo.lock) to versions known working with rust 1.24.1 (for sumo)
* Remove duplicate packaging of bcm43143
* Set ModemManager to ignore Inca Roads Serial Device
* Add support for aufs 4.14.56+
* Update resin-supervisor to v7.19.7

## meta-resin-2.18.1
### (2018-09-14)

* Add a parsable representation of the changelog

## meta-resin-v2.18.0
### (2018-09-12)

* Update grub hooks to prepare to load kernel from root [Zubair Lutfullah Kakakhel]
* Update resin-supervisor to v7.19.4 [Cameron Diver]
* Kernel-resin.bbclass: Enable CONFIG_IP_NF_TARGET_LOG as a module [John (Jack) Brown]
* Balena: Update to current HEAD of 17.12-resin [Andrei Gherzan]
* Compress os-config with UPX on arm64 too [Andrei Gherzan]
* Update upx to 3.95 [Andrei Gherzan]
* Add support to skip flasher detection in env_resin.h [Zubair Lutfullah Kakakhel]
* Add the kernel to the rootfs [Zubair Lutfullah Kakakhel]
* Rework resin-supervisor systemd dependency on balena [Florin Sarbu]
* Enhanced security options for dropbear - sumo [Andrei Gherzan]
* Enhanced security options for dropbear - rocko [Andrei Gherzan]
* Enhanced security options for dropbear - pyro [Andrei Gherzan]
* Enhanced security options for dropbear - morty [Andrei Gherzan]
* Enhanced security options for dropbear - krogoth [Andrei Gherzan]

## meta-resin-2.17.0
### (2018-09-03)

* Resin-proxy-config: The no_proxy file fails to parse when missing EOL [Rich Bayliss]

## meta-resin-2.16.0
### (2018-08-31)

* Os-config: UPX is broken on aarch64 [Theodor Gherzan]
* Allow flasher types to pin preloaded devices [Theodor Gherzan]
* Disable PIE for go [Zubair Lutfullah Kakakhel]
* Disable PIE for balena [Zubair Lutfullah Kakakhel]

</details>

* Update the poky submodule to sumo-19.0.1 [Florin Sarbu]
* Add a parsable representation of the changelog [Giovanni Garufi]

# v2.15.1+rev1
## (2018-08-31)

* Update the meta-resin submodule to version v2.15.1 [Florin Sarbu]
* Add versionist support [Giovanni Garufi]

# v2.14.3+rev1
## (2018-08-15)

* Update the meta-resin submodule to version v2.14.3 [Florin]
* Update autohat to HEAD of master [Horia]

# v2.14.1+rev2
## (2018-08-05)

* Disable UPX compression for os-config [Florin]

# v2.14.1+rev1
## (2018-08-03)

* Update the meta-resin submodule to version v2.14.1 [Florin]
* Update the resin-yocto-scripts submodule to 8312741e13604a9d166370349061876afb22c0fa (on master branch) [Florin]
* Enable squashfs support in the kernel [Florin]

# v2.14.0+rev1
## (2018-07-20)

* Update the meta-resin submodule to version v2.14.0 [Florin]
* Switch docker storage driver from aufs to overlayfs [Florin]
* Switch to Yocto Sumo 19.0.0 [Florin]

# v2.13.6+rev1
## (2018-07-13)

* Update the meta-resin submodule to version v2.13.6 [Florin]

# v2.13.5+rev1
## (2018-07-10)

* Update the meta-resin submodule to version v2.13.5 [Florin]
* Update the resin-yocto-scripts submodule to 59ccd8558435ff6424827fb36ccb43b14650f4d4 (on master branch) [Florin]

# v2.12.7+rev1
## (2018-05-07)

* Update the meta-resin submodule to version v2.12.7 [Florin]

# v2.12.6+rev1
## (2018-05-02)

* Update the meta-resin submodule to version v2.12.6 [Florin]
* Update the resin-yocto-scripts submodule to f7718efbbf53369aaacb7eb54e707ee8a5d4fc4b (on master branch) [Florin]

# v2.12.5+rev1
## (2018-03-27)

* Update the meta-resin submodule to version v2.12.5 [Florin]
* Update the resin-yocto-scripts submodule to 9cecb1ca4d9d4713dd337148b7d04a17afdba772 (on master branch) [Florin]
* Update running instructions for non-KVM case [Gergely]

# v2.9.6+rev1
## (2018-01-13)

* Update the meta-resin submodule to version v2.9.6 [Florin]

# v2.9.2+rev1
## (2017-12-20)

* Update the meta-resin submodule to version v2.9.2 [Florin]
* Install in the rootfs the 99-resin-grub hostapp hook needed for GRUB to switch the root partition when doing host OS updates [Florin]
* Update the resin-yocto-scripts submodule to 6f7a9ab326bb822196e3e48b08ef1d73d08caec6 (on master branch) [Florin]

# v2.7.4+rev1
## (2017-10-28)

* Update the meta-resin submodule to version v2.7.4 [Florin]
* Update the resin-yocto-scripts submodule to e3a06d48a2f8b7e32d3047c33066a5b896e6ae93 (on master branch) [Florin]
* Update meta-openembedded to latest pyro branch [Will]
* Update poky to latest pyro branch [Will]
* Include meta-rust layer [Will]
* Add meta-rust layer [Will]
* Update to Yocto Pyro [Will]
* Update resin-yocto-scripts to latest master [Will]

# v2.3.0+rev1
## (2017-08-17)

* Update the meta-resin submodule to version v2.3.0 [Florin]

# v2.2.0+rev1
## (2017-07-30)

* Update the meta-resin submodule to version v2.2.0 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]

# v2.1.0+rev1
## (2017-07-25)

* Update the meta-resin submodule to version v2.1.0 [Florin]
* Update the resin-yocto-scripts submodule to HEAD of master [Florin]
* Make Yocto use libsdl-native instead of host libsdl [Florin]

# v2.0.4+rev1
## (2017-05-22)

* Update the meta-resin submodule to version v2.0.4 [Florin]
* Update the resin-yocto-scripts submodule [Florin]
* Update resin-yocto-scripts to master [Will]
* Adding new autohat tests + fixes [Horia]

# v2.0.2+rev1
## (2017-05-10)

* meta-resin: Bump to 2.0.2 [Andrei]
* Update resin-yocto-scripts [Will]
* Update autohat submodule [Will]
* Update Poky and meta-openembedded submodules to morty [Will]
* Update tests/autohat - Fixes HOSTOS version parsing bug + Adds new tests [Praneeth]
* Update grub.cfg - Search QEMU root device by label instead of hda/sda/vda paths [Praneeth]
* Update linux-yocto_%.bbappend - To enable support for running the image on Google Cloud [Praneeth]

# v2.0.0-rc5.rev1
## (2017-03-26)

* Update the meta-resin submodule to version v2.0.0-rc5 [Florin]
* Update tests/autohat - Bring in stability improvements and new tests [Praneeth]
* Increase size of the resin initramfs image from 8192K to 16384K to accommodate for size increase due to x86 arch [Florin]
* Update the meta-resin submodule to version v2.0.0-rc3 [Florin]

# v2.0.0-beta12.rev1
## (2017-02-27)

* Bump tests/autohat to current HEAD [Andrei]
* Bump resin-yocto-scripts to current HEAD [Andrei]
* meta-resin: Bump to 2.0.0-beta12 [Andrei]

# v2.0.0-beta11.rev1
## (2017-02-15)

* Update meta-resin to v2.0.0-beta.11 [Andrei]

# v2.0.0-beta10.rev1
## (2017-02-14)

* Update meta-resin to v2.0.0-beta.10 [Andrei]

# v2.0.0-beta.9
## (2017-02-08)

* Update meta-resin to v2.0-beta.9 [Andrei]

# v2.0.0-beta.8
## (2017-01-27)

* Update meta-resin to v2.0-beta.8 [Andrei]
* Update resin-yocto-scripts to HEAD of the master branch [Florin]
* Update tests/start.sh - Enable AutoHaT support for Qemu 32 bit images [Horia]
* Update tests/autohat - Bring in stability improvements and new tests [Praneeth]

# v2.0.0-beta.7
## (2016-12-05)

* Update meta-resin to v2.0-beta.7 [Florin]

# v2.0.0-beta.6
## (2016-12-05)

* Update meta-resin to v2.0-beta.6 [Andrei]

# v2.0.0-beta.5
## (2016-11-30)

* Update meta-resin to v2.0-beta.5 [Andrei]

# v2.0.0-beta.3
## (2016-11-07)

* Update meta-resin to v2.0-beta.3 [Andrei]
* Cleanup docker-resin-supervisor-disk of unneeded variables [Andrei]
* Update resin-yocto-scripts to fix logging in container builds

# v2.0.0-beta.1
## (2016-10-11)

* Update meta-resin to v2.0-beta.1 [Andrei]
* Add meta-filesystem as we need aufs-utils [Andrei]
* Add build support for resinos [Andrei]
* Update resin-yocto-script to include changes in our image types [Theodor]
* Replace the concept of a debug image with a development image [Theodor]
* Update meta-resin to include avahi [Florin]
* Update resin-yocto-scripts to include kernel headers handling as gzip [Florin]

# v1.16.0
## (2016-09-27)

* Update meta-resin to v1.16 [Florin]

# v1.15.0
## (2016-09-24)

* Update meta-resin to v1.15 [Florin]

# v1.14.0
## (2016-09-23)

* Update meta-resin to v1.14 [Florin]

# v1.13.0
## (2016-09-23)

* Update meta-resin to v1.13 [Florin]

# v1.12.0
## (2016-09-21)

* Update meta-resin to v1.12 [Florin]
* Update resin-yocto-scripts to include resinhup upload to dockerhub [Florin]
* Update tests/autohat - Fetching the new resin-cli and adding additional tests [Praneeth]
* Update meta-resin [Florin]
* Change .coffee to announce partition 1 now holds config.json and also introduce versioning (v1) [Florin]

# v1.11.0
## (2016-08-31)

* Update meta-resin to v1.11 [Florin]

# v1.10.0
## (2016-08-24)

* Update meta-resin to v1.10 [Florin]

# v1.9.0
## (2016-08-24)

* Update meta-resin to v1.9 [Florin]
* Update resin-yocto-scripts for including kernel modules headers deploy [Florin]

# v1.8.0
## (2016-08-02)

* Bump meta-resin to v1.8 [Andrei]

# v1.7.2
## (2016-07-26)

* Bump resin-yocto-scripts to current HEAD to include ability to run tests based on variable [Praneeth]

# v1.7.1
## (2016-07-26)

* No more debug images in staging

# v1.7.0
## (2016-07-14)

* Update meta-resin to v1.7
* Add support for qemux86 and qemux86-64 [Andrei]
