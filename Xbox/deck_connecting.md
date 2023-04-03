# Connecting an Xbox One RB4 Guitar to a Steam Deck
## Prerequisites
* A Steam Deck
* An Xbox One RB4 Guitar
* An Xbox Wireless Adapter for Windows (Official or Unofficial)
* Having your Steam Deck's Filesystem unlocked using ``sudo steamos-readonly disable``

## ⚠️ Every time the steam deck has a major, you must re-unlock your filesystem and must follow the "Installing the Drivers" section again. 

## Installing the Drivers
1. Enter Desktop Mode on your Steam Deck.
2. Install the Linux Kernel Headers on your steam deck with ``sudo pacman -S linux-neptune-headers``
3. Install dkms on your steam deck with ``sudo pacman -S dkms``
4. Install cabextract on your steam deck with ``sudo pacman -S cabextract``
5. Download/Clone the xone Repository from [here](https://github.com/medusalix/xone)
6. ***Do not plug in your adapter yet!***
7. CD into the xone directory and run ``sudo ./install.sh --release``
8. Run ``sudo xone-get-firmware.sh`` to download the firmware for the Xbox Wireless Adapter. You will have to agree to the Microsoft Terms of Serivce.
9. You can plug in your adapter and proceed to the next section.

## Connecting and Pairing the Guitar
1. Plug the Xbox Wireless Adapter into a USB-A to USB-C Adapter, or Dock.
2. Turn on the Xbox One RB4 Guitar.
3. Press the pair button on the Xbox Wireless Adapter. You may need to re-pair the device, even if had it paired before.
4. Press the pair button on the Xbox One RB4 Guitar.
5. The Xbox One RB4 Guitar should now be connected to your Deck.

# Done!

