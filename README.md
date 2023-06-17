# zing-corne

ZMK config and relevant files for my custom built split mechanical keyboard.

![Corne Split keyboard](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rJ6Sjp6qW7xbiAurwrsaD5yY4e21c9H0rIznXP8QhAVTqRbdGJAOzUO6liVFnT3sK3fCAXkS1OjmltfOwiL9Wt7Q6_zA=w1920-h1080)

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

![Keymap](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81otbUCP6zZFBFsY6KPMLzsmqZekzGliN7N2hEaKL42Kfq8o5Ofxrff6bLZUSYR4k0T7Wgiv0DR1W1yhEacB7D1ZR9So=w1920-h1080)

## More Images

 . | .
:-------------------------:|:-------------------------:
![Image 1](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qjeiGPDkCluah6yp83OlA_TczThZwAYL1p1XmSw9QuxJnkbkebsqFCnSGEM86NBBh1Ws9nzr9qyzVc8QJslRCO93Q13A=w1920-h1080)  |  ![Image 2](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81oV9iV--XWm0QQlCSL3x5Gva7dcTHwanTqM3BEAvuKsZbYUGgfA4QJMrRbffqNwMA70Gm36JK2KZveN9pZj9VNfrLEHtw=w1920-h1080)
![Image 3](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qp_5r2h534zlPBszj-M00HTSiDkwjddT2-P2eyZmciEpXhvefO_ys5Njg-EUCEYzHTCNqeTKuEi5dtYMzTsgHSwxjWMQ=w1920-h1080)  |  ![Image 4](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qgD1Rm5nGw8X4IyvKGOOz59S_RCC1_ChaS3FQ9HM99WLWSHPGqYMY42PgcMBLziuW9byOVT_NzjW2MCUN_jkc8hg5wxA=w1920-h1080) 

## Build

#### Parts arrive

Between manufacturing and shipping it took around 3 weeks to source all the parts needed for the build. The cases and PCB's were printed in China and the MCU's I ordered from the Netherlands. Finally, finding all the small components from various local shops took quite a bit of time, but luckily the local enthusiast community were able to help me find everything I needed - or have it made(thanks [worthmfg](www.worthmfg.co.za)). 

 . | .
:----------------:|:-----------------:
![Build Log 1](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qxHsikeFV0H6P-QWwlv7keqyu7Y-QRJ9FiEJc_sx5-zorIKwEHAOX-IN6ZOHKOMgn332icO6NpgluEeE2-w0xKOE9X_Q=w1920-h1080) | ![Build Log 2](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81o6kMbZUASO-XklMvDg0b6cMNlzO9Q2bt508w6_zC7MfDjARVVnt351xEh9197gOSqrUGAgv8vxbh5gSMTJDe7mVgXQNQ=w1920-h1080)
![Build Log 1](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rWumcKTaNsF3h9pbBHZRJyFqwGUS3zrdy0E3zeL8HskGIm77OIlotdK_XhniqsxyBTCuPIFdHe-6ZhvTDX6x9OhJnftg=w1920-h1080) | ![Build Log 2](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81pRDMYW_II6_QKo9oD4ivo8NluhaJITRO00i6qVPpz_Tlb7vmw4aVRqolP7aQrqL2pdmdYkyn1GhdMrfOKio77xSppCkA=w1920-h1080)
![Build Log 1](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rR4Ht9f6JapwbgiPsrjJxLiI0zTDJAmulLpuqcBW3-8kWt8XNz7nciL-87CH35nCsOQxTyXvy-DcFKANgCcqHHxPihGw=w1920-h1080) | ![Build Log 2](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81p_WlrkzRABQ-slPq55yAi-KX9P64JttWih_vfmCJnfF0vHDDS9nWAc6d9x3DUsUPuybC5irtS8cbJAYGz9Rg9r0jW42w=w1920-h1080)

#### Soldering

- Completing all the soldering took around 3 evenings. This was my first time soldering this many parts and it was pretty fun. I was using 4mm flux solder, with some extra flux on the side. My soldering iron was the cheapest one my local hardware store sold me a few years back, but it worked alright. Unfortunately I did ruin one of my PCB's at this point, trying to de-solder an LED. Luckily had plenty extra. 

Diodes and hotswap sockets soldered
![Build Log 2](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81oWq-saeuJtmmIhT9WgzmZuVNQ_gd_6GYk7lKSom7h5frMRvLzcAXKwkW-U-PbCGhm-MKKYOe2cS1CukMU8_VJfg9rLuQ=w1920-h1080)

Adding MCU's and batteries
![Build Log 3](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81ogXiz8c1hEmsy8gXZaVsoD-m4DKj_HHTStVVNY8LR-irXhEt8NlryBmrFEfAhZTyN-raYi2MtQ2BGj8UBjWj1hxYFZvQ=w1920-h1080)

#### Wrapping up

- Adding foam to case mounts
- Add + adjust tenting screws and feet
- Add plates + mount switches to plates
- Mounting the plates to their case

 . | .
:-------------------------:|:-------------------------:
![Build Log 4](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rhP1iKtqZ5-TI5bad522bccgXb8WrhHZS-eMHDnBzHUZp5RR2bCgJoDYXKp2eqIX3ztF3VxfqC-a_HPHTq-XStGIgliw=w1920-h1080)  |  ![Build Log 5](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rLtsIyShmGPyAPyPLgvRgxIBM8mPzJguB5z2I8qfaDenb7R2Wpk2A0FG1ev1r-IzYETabFBKvfSAskcGsZmUoxkQ1Y=w1920-h1080)
![Build Log 6](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81pD3Dcssyb50xb1jD1rxRjAUKnsO84L0dBlTM-nvtVOgk-ibyUi9J5Y3K8WIijOEz3_kV9T1TgmIuam2V1gH3E243iksg=w1920-h1080)  |  ![Build Log 7](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rAAewdz15SI7biANgXjukMJ20CSnj2ziRTcNpjCKjasOcQrAP4M-fmvUlcTxhaH_Q_QzVYu4EPcZx62R3MbNK0UAYAoA=w1920-h1080) 


### Final product

I'm so stoked with how this board turned out, from the aesthetics to the functionality it's exactly what I was aiming for. I'm still tweaking the keymap occasionally as I find more optimal locations for certain keys, but so far the ease of access to all the keys is awesome and I find myself using the mouse less and less. I have never been a big fan of layers, but at the moment I consider the tradeoff well worth it - my experience so far is that having every movement based off the same position makes for much more fluid use of the keyboard.

![Build Log 8](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qjeiGPDkCluah6yp83OlA_TczThZwAYL1p1XmSw9QuxJnkbkebsqFCnSGEM86NBBh1Ws9nzr9qyzVc8QJslRCO93Q13A=w1778-h1080)

#### Future plans

- I have a set of sk6812mini-e RGB LEDs which I would like to add as back-lighting underneath each key. This seems to be supported by ZMK but not out of the box(in the configuration I would like), so some tweaking of the code and physical bypassing on the PCB might be required to achieve what I want. 
