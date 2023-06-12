# zing-corne

ZMK config and relevant files for my custom built split mechanical keyboard.

![Split keyboard](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rJ6Sjp6qW7xbiAurwrsaD5yY4e21c9H0rIznXP8QhAVTqRbdGJAOzUO6liVFnT3sK3fCAXkS1OjmltfOwiL9Wt7Q6_zA=w1920-h1080)

My board is based on a popular split keyboard PCB shape called the Corne ([github.com/crkbd](https://github.com/foostan/crkbd)), which features 3x6 column staggered keys and 3 thumb keys on each side. It has 3 layers to access all the keys of a normal board, as well as some custom macros. The main advantage of this design is that your fingers never need to leave the home row, meaning you type faster, more comfortably, and can make more effective use of keyboard shortcuts. Being split, it also allows your arms to fall more naturally on the table - wherever you like. All these seemingly insignificant tweaks add up to a decent improvement in ergonomics over the course of years spent typing.

#### Components

- `MCU`: [nice!nano v2](https://nicekeyboards.com/nice-nano/) (wireless)
- `PCB`: Standard [v3.0.1 Cherry-Corne](https://github.com/foostan/crkbd/tree/main/corne-cherry/doc/v3) designs
- `OLED`: 0.91" 128x32 I2C white OLEDS
- `Batteries`: 1000mah Lipo
- `Sockets`: Gateron hotswap sockets
- `Headers`: Millmax "315" low profile sockets
- `Diodes`: 1N4148W  SMD Diode SOD-123
- `Switches`: [Akko Lavender Purple](https://en.akkogear.com/product/akko-cs-lavender-purple-switch-45pcs/) | Tactile
- `Keycaps`: [Akko Olivia]()
- `Case`:  [Custom design](https://www.printables.com/model/347524-corne-keyboard-case-5-and-6-columns) by [VOID](https://www.printables.com/@void)
    - Tented at ~12 degrees with M5 Hex screws
    - Printed in translucent resin
- `Plates`: 1.5mm Alu plates cut by [worthmfg.co.za](https://worthmfg.co.za/)

#### Software

MCU's flashed with official [ZMK firmware](https://github.com/zmkfirmware/zmk)

#### Keymap:

![Split Keyboard](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81otbUCP6zZFBFsY6KPMLzsmqZekzGliN7N2hEaKL42Kfq8o5Ofxrff6bLZUSYR4k0T7Wgiv0DR1W1yhEacB7D1ZR9So=w1920-h1080)

## More Images

![Split keyboard](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qjeiGPDkCluah6yp83OlA_TczThZwAYL1p1XmSw9QuxJnkbkebsqFCnSGEM86NBBh1Ws9nzr9qyzVc8QJslRCO93Q13A=w1920-h1080) 

![Split keyboard](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81oV9iV--XWm0QQlCSL3x5Gva7dcTHwanTqM3BEAvuKsZbYUGgfA4QJMrRbffqNwMA70Gm36JK2KZveN9pZj9VNfrLEHtw=w1920-h1080)

![Split keyboard](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qp_5r2h534zlPBszj-M00HTSiDkwjddT2-P2eyZmciEpXhvefO_ys5Njg-EUCEYzHTCNqeTKuEi5dtYMzTsgHSwxjWMQ=w1920-h1080) 

![Split keyboard](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qgD1Rm5nGw8X4IyvKGOOz59S_RCC1_ChaS3FQ9HM99WLWSHPGqYMY42PgcMBLziuW9byOVT_NzjW2MCUN_jkc8hg5wxA=w1920-h1080) 

## Build log

#### 1. Parts arrive
- Cases and PCBs arrived from manufacturing in china via [elecrow.com](https://www.elecrow.com/)
- Switches, keycaps and socket arrived from [ctrlshiftesc.co.za](https://www.ctrlshiftesc.co.za/)

![Build Log 1](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qxHsikeFV0H6P-QWwlv7keqyu7Y-QRJ9FiEJc_sx5-zorIKwEHAOX-IN6ZOHKOMgn332icO6NpgluEeE2-w0xKOE9X_Q=w1920-h1080)

#### 2. Soldering

- Completing all the soldering took around 3 evenings. This was my first time soldering this many parts and it was a good learning experience. I was using 4mm flux solder, with some extra flux on the side. My soldering iron was the cheapest one my local hardware store sold me a few years back, but it worked alright. 

Diodes and hotswap sockets

![Build Log 2](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81oWq-saeuJtmmIhT9WgzmZuVNQ_gd_6GYk7lKSom7h5frMRvLzcAXKwkW-U-PbCGhm-MKKYOe2cS1CukMU8_VJfg9rLuQ=w1920-h1080)

MCU's and batteries 

![Build Log 3](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81ogXiz8c1hEmsy8gXZaVsoD-m4DKj_HHTStVVNY8LR-irXhEt8NlryBmrFEfAhZTyN-raYi2MtQ2BGj8UBjWj1hxYFZvQ=w1920-h1080)

#### 3. Wrapping up

- Adding foam to case mounts
- Add + adjust tenting screws and feet
- Add plates + mount switches to plates
- Mounting the plates to their case

![Build Log 4](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rO-VxNdPCvVQzVtxrkiU0t3stmMLltyQFZPqLC4REFZC6woDl2BuPxDxyyfrojiPbO7caPUPPuW67aeVZpuupTwATwLg=w1778-h1080)

![Build Log 5](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rdEThmderMkaMFuzsVCckaHYe4M05d_TIGgkoi8mUjTbQG_6AVQ3InA64rxBNn3iyzi-2xoCHjwSKBO8UGamZz75n3og=w1778-h1080)

![Build Log 6](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81pD3Dcssyb50xb1jD1rxRjAUKnsO84L0dBlTM-nvtVOgk-ibyUi9J5Y3K8WIijOEz3_kV9T1TgmIuam2V1gH3E243iksg=w1920-h1080) 

![Build Log 7](https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81rAAewdz15SI7biANgXjukMJ20CSnj2ziRTcNpjCKjasOcQrAP4M-fmvUlcTxhaH_Q_QzVYu4EPcZx62R3MbNK0UAYAoA=w1920-h1080) 

### Final product

I'm very happy with how this board turned out, from the aesthetics to the functionality it really is all that I was aiming for. I'm still tweaking the keymap occasionally as I find more optimal locations for certain keys, but so far the ease of access to all the keys is very noticeable and I find myself using the mouse less and less. I was never a fan of layers but I think the tradeoff for access to everything is well worth it, as basing every movement off the home row allows for a much more optimized workflow once you commit the keymap to memory. 


![Build Log 8](
https://lh3.googleusercontent.com/u/0/drive-viewer/AFGJ81qjeiGPDkCluah6yp83OlA_TczThZwAYL1p1XmSw9QuxJnkbkebsqFCnSGEM86NBBh1Ws9nzr9qyzVc8QJslRCO93Q13A=w1778-h1080)

#### Future plans

- I have a set of sk6812mini-e RGB LEDs which I would like to add as back-lighting underneath each key. This seems to be supported by ZMK but not out of the box, so some tweaking of the code and manual bypassing on the PCB might be required to achieve what I want. 
