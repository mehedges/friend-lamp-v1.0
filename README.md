# friend-lamp-v1.0
This is my take on the friend lamp project! It is very important to note this project is based off of the one by tmckay. I created this repository because I definitely deviated from the instructions there, and this repository is coming from & made for people that might not have previous experience with RaspberryPi and web services. I am more hardware-oriented and did not realizze the project had heavy software requirements. If tmckay would like me to edit this or take it down, I definitely will; but again, this is just my spin on the project. I highly recommend checking out their project here:

[Instructables Page](https://www.instructables.com/DIY-Long-Distance-Best-Friend-Lights/)

[Their GitHub Page](https://github.com/tmckay1/best_friend_light)

<p align="center">
  <img width="460" src="[https://picsum.photos/460/300](https://github.com/mehedges/friend-lamp-v1.0/assets/102606124/9abcbcd7-098a-4d06-a401-509a36542d43)">
</p>

## Plans for Future Updates
I originally made this project for my mom while I'm away at college, since she mentions she worries about me sometimes (in a sweet way lol). But, I also have online friends in Europe that requested a lamp for themselves, which would be awesome if I got it working worldwide. Technically, that should be possible. Also, I have so many ideas for a newer, 'updated' version of the one I just made for my mom. Of course she will get the first updated lamp, but I will also make another folder and everything for v2.0. Below I will put some starting materials you will need for v1.0.

## Hardware
The goal here for me, a college student, is to save money. 
|                                                                                         |           Part           |     Price     |                 Link to Part                    |
|                                    -------------                                        |     -------------        | ------------- |                   -------------                 |
|<img src="https://cdn-shop.adafruit.com/970x728/3400-00.jpg" width="100" />              |     Raspberry Pi 0       |     $15.00    |[Adafruit](https://www.adafruit.com/product/3400)|
|<img src="https://cdn-shop.adafruit.com/970x728/1294-03.jpg" width="100" />              |     8GB MicroSD Card     |     $9.95     |[Adafruit](https://www.adafruit.com/product/1294)|
|<img src="https://m.media-amazon.com/images/I/51H5cvVGxUL._AC_SL1000_.jpg" width="100" />|KY-004 (OR Tactile Switch)| $6.49 (3 pack)|[Amazon](https://www.amazon.com/KY-004-Button-Switch-Sensor-Module/dp/B0786BDFT5)|
|<img src="https://cdn11.bigcommerce.com/s-3fd3md1ghs/images/stencil/1280x1280/products/29723/11400/rgb-led-diffused__74395.1577790268.jpg?c=2" width="100" />|4-Pin RGB LED| $1.88 (x2)|[Digikey](https://www.digikey.com/en/products/detail/kingbright/WP154A4SUREQBFZGC/3084119?utm_adgroup=&utm_source=google&utm_medium=cpc&utm_campaign=PMax%20Shopping_Product_Medium%20ROAS%20Categories&utm_term=&utm_content=&utm_id=go_cmp-20223376311_adg-_ad-__dev-c_ext-_prd-3084119_sig-Cj0KCQiAtOmsBhCnARIsAGPa5yZKuHfFNeNOZGDt0-6JHBbu6RP6r3f0rWSvfbtb0RbuAug3cY-6Dr4aAsVfEALw_wcB&gad_source=1&gclid=Cj0KCQiAtOmsBhCnARIsAGPa5yZKuHfFNeNOZGDt0-6JHBbu6RP6r3f0rWSvfbtb0RbuAug3cY-6Dr4aAsVfEALw_wcB)|

### Miscellaneous Needed Materials
- Electrical solder + Soldering iron
- Wires
- Micro USB (to USB)
- Some sort of stand (I used a cardboard box for mine)
- Acrylic plastic sheet (+sander if the diffused/frosted look is wanted)
- Hot glue gun + hot glue

## Software
Again, I'm trying to save money. All of these programs are free.
|         Program          |                          What it Does             |                         Link to Download                |
|     -------------        |                -------------                      |                         -------------                   |
| Raspberry Pi Imager      | Flashes the SD card with an operating system (OS) | [Raspberry Pi OS](https://www.raspberrypi.com/software/)|
| Bonjour                  | Allows the Raspberry Pi to print out on Putty     | [Website Link](https://support.apple.com/kb/DL999?locale=en_US)|
| Putty                    | Creates a SSH to connect and control the Raspberry Pi. NEEDED! | [Website Link](https://www.putty.org)      |
| Advanced IP Scanner      | Not required, but very helpful when checking to see if the Pies are online| [Here](https://www.advanced-ip-scanner.com)|
| AirTable                 | Allows Pies to connect to each other via WiFi, vs local network (for Pies not on the same WiFi)| [Link](https://www.airtable.com/lp/campaign/brand?utm_source=google&utm_medium=paidsearch&utm_extra5=kwd-325289323194&utm_extra2=936407691&utm_extra10=47735600558&creative=611964234627&utm_extra8=c&cx=us&utm_campaign=demand_na_productoperation_creator&utm_content=text&utm_term=airtable&gad_source=1&gclid=Cj0KCQiAtOmsBhCnARIsAGPa5yb9q4I9tKWIUQj190MgX_98i6qhv1bomkUV4HECtTjx7p94hkKnTdYaAoc5EALw_wcB)|
