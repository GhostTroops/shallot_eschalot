#make from 
# https://github.com/katmagic/Shallot
# https://github.com/ReclaimYourPrivacy/eschalot
#in kali linux
```
git clone https://github.com/hktalent/shallot_eschalot
cd shallot_eschalot
ln `pwd`/libcrypto.so.10 /lib/x86_64-linux-gnu/libcrypto.so.10
ln `pwd`/libssl.so.10 /lib/x86_64-linux-gnu/libssl.so.10
ln `pwd`/shallot /usr/local/bin/shallot
ln `pwd`/eschalot /usr/local/bin/eschalot
chmod +x /usr/local/bin/eschalot
chmod +x /usr/local/bin/shallot

```
