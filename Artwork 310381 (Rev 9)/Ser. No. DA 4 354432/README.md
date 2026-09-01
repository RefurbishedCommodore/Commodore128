<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Commodore 128

![Name](https://img.shields.io/badge/Serial_No.-DA4_354432-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Artwork-310381-white?style=plastic)
![Name](https://img.shields.io/badge/Revision-9-white?style=plastic)
![Name](https://img.shields.io/badge/Video_format-PAL-white?style=plastic)

# Table of contents

<!-- TABLE OF CONTENTS -->
<details>
<summary>TOC - Click to enlarge</summary>
  <ul>
    <li>
      <a href="#starting-point">Starting point</a>
    </li>
    <li>
      <a href="#refurbishment-activities">Refurbishment activities</a>
    </li>
    <li>
      <a href="#disassembly">Disassembly</a>
    </li>
    <li>
      <a href="#mainboard">Mainboard</a>
    </li>
      <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
        <li>
          <a href="#initial-testing">Initial testing</a>
        </li>
        <li>
          <a href="#checking-the-voltages">Checking the voltages</a>
        </li>
        <li>
          <a href="#cleaning-the-user-and-datasette-port">Cleaning the user and datasette port</a>
        </li>
        <li>
          <a href="#adding-heatsinks">Adding heatsinks</a>
        </li>
      </ul>
    </li>
    <li>
      <a href="#casing">Casing</a>
    </li>      
  </ul>
</details>

# Starting point

This Commodore 128 looks really nice. As can be seen from the keyboard layout, this is a Norwegian version of the Commodore 128. Currently, I do not know whether it works or not, but from the outside it appears to be very well preserved.

There is some dirt and grease, but it is minimal. The yellowing is also barely noticeable. There is a small bubble (?) on the left side of the "Commodore 128" badge, and a coin-sized mark on the right-hand side of the machine. Other than that, I cannot see any damage or major marks.

From the underside, I can see that this machine has not been opened before. The warranty seal is still intact.

Below are some pictures of the breadbin Commodore 128 before refurbishment.

<p align="center">
    <img src="Images/Start_01.jpeg" alt="Description" width="800">
    <img src="Images/Start_02.jpeg" alt="Description" width="800">
    <img src="Images/Start_03.jpeg" alt="Description" width="800">
    <img src="Images/Start_04.jpeg" alt="Description" width="800">
    <img src="Images/Start_05.jpeg" alt="Description" width="800">
    <img src="Images/Start_06.jpeg" alt="Description" width="800">
</p>

Another nice thing about this Commodore 128 is that the original cardboard box is still intact.

<p align="center">
    <img src="Images/Start_07.jpeg" alt="Description" width="800">
    <img src="Images/Start_08.jpeg" alt="Description" width="800">
    <img src="Images/Start_09.jpeg" alt="Description" width="800">
    <img src="Images/Start_10.jpeg" alt="Description" width="800">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Refurbishment activities

The planned refurbishment activites for this Commodore 128 (Order may vary. Several of them in parallel):

- [ ] Refurbish mainboard
- [ ] Refurbish the keyboard
- [ ] Refurbish the casing
- [ ] Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that needs special attention.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

Disassembling the Commodore 128 is not difficult, but it is a bit more challenging than disassembling a Commodore 64. Patience is required to avoid damaging the brittle plastic.

The first step is to remove the six screws from the underside[^1]: three at the front, one in the middle, and two at the back.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="800">
</p>

The process of lifting the top cover can now begin. This is the part where the most care must be taken, so the process should be carried out in the following steps:

1. Release the small clips on each side of the top cover.
2. Disconnect the ground and keyboard connectors on the right-hand side.
3. Disconnect the power LED connector on the left-hand side.

**Step 1 — Release the small clips**

On each side of the top cover, there is a small plastic clip that holds it securely to the bottom cover. The locations of these clips are shown in the picture below, with the arrows pointing to them.

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="800">
</p>

With some plastic spudgers/prying tools, the top cover is *carefully* separated from the bottom cover. Note that the plastic is brittle, so there is no need to rush this step.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="600">
</p>

**Step 2 — Disconnect the ground and keyboard connectors**

The top cover is gently moved so that the right-hand side of the bottom cover is exposed. The ground connector can now be unscrewed[^2], and the keyboard connector can be disconnected.

Note that the keyboard connector requires a small prying tool (a chip lifter can be useful). **Do not pull on the wires when disconnecting this connector.**

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="600">
</p>

**Step 3 — Disconnect the power LED connector**

The top cover is now shifted towards the right, exposing the left-hand side. The power LED connector is now visible and can be disconnected.

<p align="center">
    <img src="Images/DIs_05.jpeg" alt="Description" width="600">
</p>

Finally, the top cover can be lifted away from the bottom cover. The interior, largely dominated by the RF shield, is now exposed. It appears to be in very nice condition.

There is some liquid residue, as can be seen in the picture below (bottom right). I suspect that this liquid may have entered through the reset switch opening, as there is some residue around the opening as well.

There is also some spot corrosion on the RF shield (see the boxed area), but this is marginal. See picture below - arrows with the "!" symbol mark the areas.

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="800">
</p>

There six screws holding the RF-shield in place[^3]; two in the front, one at the left side and three in the back. See picture above. **NOTE:** Before the RF-shield can be lifted, the eight metal tabs (four in the front, and four on the left hand side) must be bent out of the way.

<p align="center">
    <img src="Images/Dis_07.jpeg" alt="Description" width="400">
</p>

So, do you think we are done now and can lift the RF shield? Nope! There is still one last obstacle: the metal tabs clinging to the middle screw post need to be tackled. The four metal tabs are **carefully** pried away from the plastic post.

<p align="center">
    <img src="Images/Dis_08.jpeg" alt="Description" width="800">
</p>

Finally, the RF shield can now be lifted away from the PCB. And what a pleasant view! At first glance, the PCB appears to be in very good condition. A thorough visual inspection will come later.

<p align="center">
    <img src="Images/Dis_09.jpeg" alt="Description" width="900">
</p>

Lifting the PCB from the bottom cover is straightforward. The only thing to note is that the RF output connector requires some gentle wiggling to free it from the rear of the bottom cover.

Below is a picture of the bottom cover. As can be seen, it is in fine condition, although it does require some cleaning.

<p align="center">
    <img src="Images/Dis_10.jpeg" alt="Description" width="900">
</p>

A final step is to bend the three metal tabs on the right-hand side of the PCB. This will release the bottom RF shield from the PCB.

<p align="center">
    <img src="Images/Dis_11.jpeg" alt="Description" width="800">
</p>


# Mainboard

The mainboard is an Artwork 310381 Rev 9. As far as I know, this is the final revision of the Commodore 128 mainboard. But, alas, there are still quite a few bodge wires on the mainboard, both on the top and bottom sides of the PCB.

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="900">
    <img src="Images/Main_02.jpeg" alt="Description" width="900">
</p>

## Visual inspection

Visual inspection of the mainboard is probably the most important, but also one of the simplest and most effective, things to do when refurbishing a Commodore 128 (or any other computer, for that matter).

The PCB is in **very** good condition. There is some dust and grease, but I cannot see any signs of corrosion. There are also no signs of leaking or bulging capacitors.

Some other things to note:

- There is some sticky tape in a few places along the PCB border. This is present on both the top and bottom sides of the PCB. This is normal, however, and the tape does not appear to have accumulated much dust or grease, which can contribute to corrosion. The purpose of this tape is to prevent short circuits caused by contact with the large top RF shield.
- The datasette port shows signs of use. This is also normal, and cleaning both the user port and datasette port is good practice.
- There is a longitudinal scratch on the CIA in position U4. This is probably not a problem, but it is worth noting.
- All the thermal paste is completely dried out. This must be cleaned off and replaced.
- There is some flux residue on the backside of the PCB around the RGBI, serial, and A/V connectors. The flux itself seldom affects signals on the mainboard, but old flux can become sticky and accumulate dust and moisture, which can eventually lead to corrosion.

The table below lists all major custom ICs found on the mainboard. As shown, the MOS chips were produced between week 05 of 1987 and week 19 of 1987, suggesting this Commodore 64 was likely manufactured during the summer of 1987. Late this summer Michael Jackson released the magnificent *BAD*.

<div align="center">
    
| Chip/Area | Manufactor | Version | Date code | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU#1 | MOS | 8502R0 | W17 Y1987 | No |  |
| CPU#2 | ZILOG | Z0840006PSC | W05 Y1987 | No |  |
| SID | MOS | 6581R4AR | W11 Y1987 | Yes |  |
| VIC-IIe | MOS | 8566R3 | W19 Y1987 | Yes |  |
| VDC | MOS | 8563R9B | W11 Y1987 | Yes |  |
| MMU | MOS | 8722R2 | W19 Y1987 | Yes |  |
| PLA | MOS | 8721R3 | W14 Y1987 | No |  |
| CIA#1	 | MOS | 6526A | W12 Y1987 | Yes |  |
| CIA#2	 | MOS | 6526A | W12 Y1987 | Yes |  |
| ROM - C64 Kernal | Unknown | 325179-01 | Unknown | Yes | EPROM marked: "C128 64 Nor." |
| ROM - C128 Kernal | Unknown | 325177-03 | Unknown | Yes | EPROM marked: "Nor.Kern.C128" |
| ROM - BASIC LO | MOS | MOS 318018-02 | W09 Y1987 | Yes |  |
| ROM - BASIC HI | MOS | MOS 318019-02 | W10 Y1987 | Yes |  |
| ROM - Character | Unknown | 325178-01 | Unknown | Yes | EPROM marked: "C128 Char.Nor." |
| RAM | SAMSUNG | KM4164B-15 | Unknown | No | |
| Glue logic | MATSUSHITA, FAIRCHILD, TEXAS INSTRUMENTS, NEC, NATIONAL SEMICONDUCTOR |  |  |  | No MOS glue logic |

</div>

## Checking the voltages

For the Commodore 128 to work flawlessly, the voltage levels need to be within acceptable limits. It is good practice to measure these voltages and rule out any problems with the power supply.

The table below lists all the measured voltages. This table will also be updated after refurbishment. All the required voltages are present and within tolerance.

<div align="center">
  
| Measure point | Target voltage | Measured voltage<br>Before refurbish| Measured voltage<br>After refurbish | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| PSU (5V) | 5 V DC | 4.805 V | TBA  V | User port |
| PSU (9V) | 9 V AC | 9.582 V | TBA V | User port |
| Unregulated (9V) | 9 V DC | 11.69 V | TBA V | C106 |
| Regulated (12V) | 12 V DC | 12.00 V | TBA V| Pin #28 SID |

</div>

<!-- MARK START -->

# Casing


<!-- MARK STOP -->

**Footnotes**
[^1]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 8.0 mm
[^2]: Phillips pan head (6.6 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.5 mm, Fastener length: 6.5 mm
[^3]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 8.0 mm
