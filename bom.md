# Bill of Materials
## Madmartigan Raspberry Pi Cluster

Item | Qty. | Price | Purpose
---- | ---- | ----- | -------
[Raspberry Pi 2 Model B](http://canada.newark.com/raspberry-pi/raspberrypi-2-modb-1gb/sbc-raspberry-pi-2-model-b-1gb/dp/38Y6467) | 6 | $43.62 | To run Drupal on Nginx
[50W 6-port USB desktop charger](http://www.amazon.com/gp/product/B00KHP6UVQ/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B00KHP6UVQ&linkCode=as2&tag=httpwwwmidw06-20&linkId=YEKQEOUTP3WTLSJJ) | 1 | $19.99 | Provide adequate power for Pis
[6-pack micro USB cables](http://www.amazon.com/gp/product/B00N8VHW72/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B00N8VHW72&linkCode=as2&tag=httpwwwmidw06-20&linkId=63VSGWYRPJFO4IZO) | 1 | $9.99 | Connect the charger to the Pis.
[16GB SanDisk Extreme microSD card](http://www.amazon.com/gp/product/B00M55BX3G/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B00M55BX3G&linkCode=as2&tag=httpwwwmidw06-20&linkId=J6BZWUNLYSW2EBST) | 6 | $14.99 | Storage for each Pi.<sup>1</sup>
[8-port unmanaged Gigabit network switch](http://www.amazon.com/gp/product/B001QUA6RA/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=B001QUA6RA&linkCode=as2&tag=httpwwwmidw06-20&linkId=24SPP5YZJR6KK7GH) | 1 | $29.99 | To build a high-speed private network.
**TOTAL** | = | **$** |

need to change suppliers for parts to CDN suppliers / prices. Raspberry Pi already updated.

<sup>1</sup>Why use a more expensive card like the SanDisk Extreme when any old microSD card would suffice? Well, the microSD card you use can have a *huge* impact on the overall performance of the cluster—especially for applications that need fast small-file random write performance, like MySQL!