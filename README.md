# zing-corne

ZMK config and relevant files for my custom built split mechanical keyboard.

![Corne Split keyboard](https://drive.google.com/uc?export=download&id=1buwcjaTtP-bixvK8RokWmaSVNxP5ng07)

This board is based on a popular split keyboard PCB shape called the Corne ([github.com/crkbd](https://github.com/foostan/crkbd)), which features 3x6 column staggered keys and 3 thumb keys on each side. It has 4 software layers to access all the keys of a normal board as well as some custom macros. The main advantage of this design is that your fingers never need to leave the home row, meaning you can type faster and more comfortably, along with the massive benefit of being able to make more effective use of keyboard shortcuts. Being split, it also allows your arms to fall more naturally on the table - wherever you like. My(and some others) feeling is that all these seemingly insignificant tweaks add up to a decent improvement in efficiency and comfort over years spent typing.

#### Components

- `MCU`: [nice!nano v2](https://nicekeyboards.com/nice-nano/) (wireless)
- `PCB`: Standard [v3.0.1 Cherry-Corne](https://github.com/foostan/crkbd/tree/main/corne-cherry) designs
- `Case`:  [Custom design](https://www.printables.com/model/347524-corne-keyboard-case-5-and-6-columns) by [VOID](https://www.printables.com/@void) 3D printed in translucent resin
    - Tented at ~12 degrees with M5 Hex screws
- `OLED`: 0.91" 128x32 I2C white OLEDS
- `Batteries`: 1000mah Lipo
- `Sockets`: Gateron hotswap sockets
- `Headers`: Millmax "315" low profile sockets
- `Diodes`: 1N4148W  SMD Diode SOD-123
- `Switches`: [Akko Lavender Purple](https://en.akkogear.com/product/akko-cs-lavender-purple-switch-45pcs/) | Tactile
- `Keycaps`: Akko Olivia
- `Plates`: 1.5mm Alu plates cut by [worthmfg.co.za](https://worthmfg.co.za/)

#### Software

MCU's flashed with official [ZMK firmware](https://github.com/zmkfirmware/zmk)

#### Keymap:
https://drive.google.com/file/d/1Rsu_RsL1Tqd7BehhD5s77JVPMbl-TvSc/view?usp=drive_link
![Keymap](https://drive.google.com/uc?export=download&id=164UkFmWi9hpZboM4zFPKddqZNDWt3v12)

## More Images

 . | .
:-------------------------:|:-------------------------:
![Image 1](https://drive.google.com/uc?export=download&id=1qwpn0RdphlMMUIOCoJ8nOM6VqmmMmIrO)  |  ![Image 2](https://drive.google.com/uc?export=download&id=1qGlHGfKatSPvJc_orPUM_LFvU4ntXT5s)
![Image 3](https://drive.google.com/uc?export=download&id=1nZT9-5t7eJYpJ11t2qusjSYI8clt2RlG)  |  ![Image 4](https://drive.google.com/uc?export=download&id=1YZ6TvnSLvlK902VqRdnefE5CMl6f9Hp_) 

## Build

#### Parts arrive

Between manufacturing and shipping it took around 3 weeks to source all the parts needed for the build. The cases and PCB's were printed in China and the MCU's I ordered from the Netherlands. Finally, finding all the small components from various local shops took quite a bit of time, but luckily the local enthusiast community were able to help me find everything I needed - or have it made(thanks [worthmfg](www.worthmfg.co.za)). 

 . | .
:----------------:|:-----------------:
![Build Log 1](https://drive.google.com/uc?export=download&id=1yDVTsRvE4QmIhGS0eG--45uwRT8hJo-O) | ![Build Log 2](https://drive.google.com/uc?export=download&id=13WDyi8zqnrfgoeAzCZKk-FPsyE0lqeZH)
![Build Log 1](https://drive.google.com/uc?export=download&id=13Tapr8rVS3OERfTyWiQ0tHp5pUXLHyqy) | ![Build Log 2](https://drive.google.com/uc?export=download&id=1N4mrTOmZIegTZ5_yXQ_TdnRSsFtVtjzg)
![Build Log 1](https://drive.google.com/uc?export=download&id=13R39AF1N1cvL9eAJAaMKd5iWn1EeQUvw) | ![Build Log 2](https://drive.google.com/uc?export=download&id=1xUNa-5lFKIgjhbhrL5NOpY6N9lIBqiNk)

#### Soldering

- Completing all the soldering took around 3 evenings. This was my first time soldering this many parts and it was pretty fun. I was using 4mm flux solder, with some extra flux on the side. My soldering iron was the cheapest one my local hardware store sold me a few years back, but it worked alright. Unfortunately I did ruin one of my PCB's at this point, trying to de-solder an LED. Luckily had plenty extra. 

Diodes and hotswap sockets soldered
![Build Log 2](https://drive.google.com/uc?export=download&id=1wsp2xBia9ygC9KmZxI-X65Uhe2NC0dNM)

Adding MCU's and batteries
![Build Log 3](https://drive.google.com/uc?export=download&id=11Zp0kAxjq2zd0RfPk1ECXs_uQBNjy0S0)

#### Wrapping up

- Adding foam to case mounts
- Add + adjust tenting screws and feet
- Add plates + mount switches to plates
- Mounting the plates to their case

 . | .
:-------------------------:|:-------------------------:
![Build Log 4](https://drive.google.com/uc?export=download&id=1jElJuW8wl7XJIwvveLs36MVLmqTV-5mI)  |  ![Build Log 5](https://drive.google.com/uc?export=download&id=1ujdHZH2Q6stA8qjjg1B2nWOIZwZuM3SV)
![Build Log 6](https://drive.google.com/uc?export=download&id=1Z3O_cVCxkxcOj75_ZTSPXjhk8OimZYBs)  |  ![Build Log 7](https://drive.google.com/uc?export=download&id=1GPgfGgMh2BxxhLiaC3PO6ATREQABMXND) 


### Final product

I'm so stoked with how this board turned out, from the aesthetics to the functionality it's exactly what I was aiming for. I'm still tweaking the keymap occasionally as I find more optimal locations for certain keys, but so far the ease of access to all the keys is awesome and I find myself using the mouse less and less. I have never been a big fan of layers, but at the moment I consider the tradeoff well worth it - my experience so far is that having every movement based off the same position makes for much more fluid use of the keyboard.

![Build Log 8](https://drive.google.com/uc?export=download&id=1qwpn0RdphlMMUIOCoJ8nOM6VqmmMmIrO)

#### Future plans

- I have a set of sk6812mini-e RGB LEDs which I would like to add as back-lighting underneath each key. This seems to be supported by ZMK but not out of the box(in the configuration I would like), so some tweaking of the code and physical bypassing on the PCB might be required to achieve what I want. 
