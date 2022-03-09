# uefi-bios
How to set-up / configure a UEFI BIOS

- Link system fan (SYS_FAN) rotation speed to CPU temperature
- Make sure the RAM runs at its correct / specified speed

## Text
Early UEFIs had text-based UI, very similar to that of old legacy BIOSes.
The earliest UEFI that I've seen looked like a legacy BIOS with "UEFI Boot" option added as an afterthought (IIRC, that system had a Pentium 4 or Core 2 in it).
Nowadays, most desktop board manufacturers just use AMI's Aptio UEFI BIOS and put their own UI on top of it.
Secure Boot isn't vendor locked. You can boot any OS as long as it's bootloader is signed with a trusted key. By default, most BIOSes come with only Microsoft's keys in their keystores, but you can easily add your own keys. Also, modern versions of Ubuntu (and probably Linux Mint as well) come with signed bootloaders which can boot with Secure Boot enabled without any modification.

## Links
- https://gamingtechies.com/best-bios-setting/
- https://linustechtips.com/topic/1373266-which-uefibios-settings-we-should-change-when-setting-up-a-new-computer/
- https://www.pcmag.com/how-to/bios-basics-how-to-configure-your-pcs-firmware-for-first-use
- https://www.pcgamer.com/how-to-a-guide-to-bios-settings/
- https://www.quora.com/What-are-the-best-BIOS-settings-for-gaming
- https://spearblade.com/general-gaming/gamers-guide-to-bios/
- https://www.exone.de/ratgeber/bios-einstellungen/
- https://www.youtube.com/watch?v=BgWq6__3jXM Default BIOS Settings Hinder Your Gaming Performance: Project SeVeN
- https://www.youtube.com/watch?v=ezubjTO7rRI PC BIOS Settings

## Todo
- Which buttons to press for which mainboard manufacturer to enter the UEFI BIOS
