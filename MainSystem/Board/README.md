# Jetson Nano (B01) Developer Kit Setup

1. Follow NVIDIA's guide: [Get Started Jetson Nano devkit](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)
2. Short the J48 pins (Connect the two pins together by placing a jumper over them). This allows for the Jetson to be powered from the DC barrel jack. This configuration allows for greater and more stable current draw from the Nano. For more information and procedural details check out [Kangalow's](https://www.jetsonhacks.com/author/kangalow/) guide:  [Jetson Nano – Use More Power!](https://www.jetsonhacks.com/2019/04/10/jetson-nano-use-more-power/) or NVIDIA's: [Power supply considerations for Jetson Nano Developer Kit](https://forums.developer.nvidia.com/t/power-supply-considerations-for-jetson-nano-developer-kit/71637)
    1. We will be connecting our power supply to the Jetson via the DC Barrel Jack
