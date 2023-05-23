# openwrt_packages
tempat simpan packages openwrt

# Install mulimiter for openwrt
opkg update && opkg install wget unzip && wget https://github.com/Jeriyant/openwrt_packages/raw/main/mulimiter.zip && unzip mulimiter.zip && cd mulimiter && sh install

# Install wrtbwmon
opkg update && opkg install wget unzip &&
wget
unzip
cd wrtbwmon
sh install.sh
