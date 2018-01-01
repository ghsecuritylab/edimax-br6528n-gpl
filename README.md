# edimax-br6528n-gpl

This is a copy of GPL sources (toolchain and firmware) for EDIMAX BR-6528n wireless router from www.edimax.com

### Where to get:

* [Product page](http://www.edimax.com/edimax/merchandise/merchandise_detail/data/edimax/global/home_legacy_wireless_routers/br-6258n)
* [Download page](http://www.edimax.com/edimax/download/download/data/edimax/global/download/for_home/home_legacy_products/home_legacy_wireless_routers/br-6258n)
* [GPL Source Code](http://www.edimax.com/edimax/mw/cufiles/files/download/OpenSourceCode/transfer/Wireless/Router/BR-6258n/BR-6258n.rar)

### Next step:

* See [Edimax_RTL8196C_BR6258GN_GPL_20121022_readme](Edimax_RTL8196C_BR6258GN_GPL_20121022_readme)

### Prepare build system:

* Download http://archive.kernel.org/centos-vault/5.11/isos/i386/CentOS-5.11-i386-netinstall.iso
* Run in VirtualBox
* Packages source = Web site
   * Web site name = archive.kernel.org
   * CentOS directory = centos-vault/5.11/os/i386
* yum install rcs autoconf automake libtool binutils gcc
* sudo ln -s /path/to/edimax-br6528n-gpl/RTL8196C /home
* cd /home/RTL8196C
* ./BUILD

### Note about nested archives:

* All nested archives are extracted before importing to Git.
* RTL8196C/toolchain/rtl8196c-toolchain-1.1.tar.gz is replaced by empty file.
