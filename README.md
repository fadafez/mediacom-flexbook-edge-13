# mediacom-flexbook-edge-13

This repository contains a kernel configuration made for the Mediacom FlexBook edge 13 Notebook. It will make the touchpad recognized by the kernel.

The configuration is inspired from the work you can find on [https://github.com/brotfessor/sipodev](brotfessor/sipodev repository). 

# Update

A kernel patch has been sent and should be merged in the upcoming kernel releases.

### Edit 27 jul 2020

Kernel patch commit link:
https://git.kernel.org/pub/scm/linux/kernel/git/stable/stable-queue.git/diff/queue-5.7/hid-i2c-hid-add-mediacom-flexbook-edge13-to-descript.patch?id=225b59f53eee6d772797b8fb0042e087e9ba74fa

It looks like that it will be included in the following kernel versions: 
- 4.4: no
- 4.9: yes
- 4.14: yes
- 4.19: yes
- 5.x: yes

It's probable that the hid-i2c quirks patch for this kind of devices has been included after v4.4 version. Users with kernel before 4.4 need to include the patch manually, or upgrade to kernel >= 4.9 
