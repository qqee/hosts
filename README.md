##Advertisement filter list.

<a href="https://github.com/qqee/hosts/raw/master/hosts" title="Download HOSTS file">Download HOSTS file (3MB)</a>

------------------------

#####Openwrt / Linux
15 5 * * * sh "wget --no-check-certificate https://github.com/qqee/hosts/raw/master/hosts -O /tmp/hostx && mv /tmp/hostx /etc/dnsmasq.d/hosts && /etc/init.d/dnsmasq restart"

#####Windows
wget --no-check-certificate https://github.com/qqee/hosts/raw/master/hosts -O hostx && move hostx %windir%/system32/drivers/etc/hosts/hosts

