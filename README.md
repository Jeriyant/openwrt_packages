# openwrt_packages
tempat simpan packages openwrt

# Install mulimiter for openwrt
opkg update && opkg install wget unzip && wget https://github.com/Jeriyant/openwrt_packages/raw/main/mulimiter.zip && unzip mulimiter.zip && cd mulimiter && sh install && cd .. && rm -rf mulimiter && rm -rf mulimiter.zip

# Install wrtbwmon
opkg update && opkg install wget unzip && wget https://github.com/Jeriyant/openwrt_packages/raw/main/wrtbwmon.zip && unzip wrtbwmon && cd wrtbwmon && sh install.sh && cd .. && rm -rf wrtbwmon && rm -rf wrtbwmon.zip
