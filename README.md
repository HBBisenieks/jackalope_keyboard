# Jackalope Keyboard
[![forthebadge](https://forthebadge.com/images/badges/contains-technical-debt.svg)](https://forthebadge.com)

`NOTE:` Current source was built against `ergogen@3.1.1` and will not work with the `4.0.0` release (or newer).

A 50-key ergonomic ~(currently single-piece)~ single-piece or split column-staggered keyboard ~(with a split version planned for the future???)~ inspired by the Absolem, Kryia, and Iris.

The Jackalope layout is focussed on maximizing comfort for the thumbs and reducing reach for the fingers.

## To-Do:
- [x] Finalize prototype PCBs
- [ ] Verify PCBs
- [ ] BOM and build guide
- [ ] Default firmware

## Firmware
The Jackalope can run either [QMK](https://github.com/HBBisenieks/qmk_firmware/tree/jackalope_boards/keyboards/jackalope) 
with a pro-micro or KMK with a KB2040. Default keymap is still a work-in-progress pending 
actual hardware testing.

## Images
Renders of the left and right split PCBs:

![3D render of a split keyboard PCB. The board is shaped vaguely like the state of Vermont on its side. There is a drawing of a rabbit in a box printed on the board.](images/jackalope_split_v2_0.png)

![3D render of a split keyboard PCB. The board is shaped vaguely like the state of New Hampshire on its side. There is a drawing of a pair of antlers printed on the board.](images/jackalope_split_v2_0_right.png)

## Old images of first-generation monoblock PCB and layout
![3D render of a keyboard pcb. The board is vaguely bat-shaped and has 6 columns of 3 keys plus and inner column of 2 keys above a 5-key thumb cluster on either side of the board, with space for a microcontroller in the center](images/jackalope_unibody.png)

![Image of v0.1 plate with screw holes for a 3d-printed case](images/jackalope_3d_plate.png)

Built using [Ergogen](https://ergogen.xyz/#).
