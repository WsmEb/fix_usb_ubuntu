# fix_usb_ubuntu

1 - <h5> Try a <code> sudo apt install --reinstall ntfs-3g</code>, which will reinstall the Ubuntu NTFS driver. </h5>
2 - <h5> <code>sudo ntfsfix /dev/sda1 </code> </h5>
3 - <h5> <code>sudo ntfsfix -d /dev/sdb1 </code> </h5>

NOTE : try one of the solution above.
