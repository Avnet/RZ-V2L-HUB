# RZBoard V2L - Information Hub

![5](https://github.com/Avnet/RZ-V2L-HUB/assets/44109284/6a6582e3-29ef-4bfe-adc2-5dd52a620f01)

Welcome to the information hub for RZBoard V2L, an exciting AI on the edge device. RZ/V2L is capable of [low-power, real-time AI inferencing](https://youtu.be/pZxYlWScN6s?si=x3NiITPa7GP88W0n) thanks to its DRP-AI accelerator. This repository serves as a central hub for all resources related to RZBoard V2L.

## Table of Contents
- [About](#about)
- [Related Repositories](#related-repositories)
- [Related Blog Posts](#related-blog-posts)
- [Getting Started & Manuals](#getting-started-and-manuals)

## About
RZBoard V2L is a power efficient, vision-AI accelerated development board in popular single board computer format with well supported expansion interfaces. This Renesas RZ/V2L processor-based platform is ideal for development of cost-efficient Vision-AI and a range of energy-efficient Edge AI applications. 

<details>
    <summary>More information & Specs</summary>

### Processing
It’s RZ/V2L processor has two 1.2GHz Arm® Cortex®-A55 cores plus a 200MHz Cortex-M33 core, a MALI 3D GPU and Image Scaling Unit. This processor SoC further differentiates itself with an on-chip DRP-AI accelerator plus H.264 video (1920 x 1080) encode/decode function in silicon, making it ideal for implementing cost-effective embedded-vision applications.


### Form Factor & Interfaces
![image](https://github.com/Avnet/RZ-V2L-HUB/assets/44109284/1a795eb7-9978-48fc-986e-40ab5f9e8514)

RZBoard V2L is engineered in a compact Raspberry Pi form-factor with a versatile set of expansion interfaces, including Gigabit Ethernet, 801.11ac Wi-Fi and Bluetooth 5, two USB 2.0 host and a USB 2.0 OTG interface, MIPI DSI and CSI camera interfaces, CANFD interface, Pi-HAT compatible 40-pin expansion header and Click Shuttle expansion header.

The board supports analog audio applications via it’s audio codec and stereo headphone jack. It also pins-out five 12bit ADC inputs for interfacing with analog sensors. 5V input power is sourced via a USB-C connector and managed via a single-chip Renesas RAA215300 PMIC device.

### Memory & Storage

Onboard memory includes 2GB DDR4, 32GB eMMC and 16MB QSPI flash memory, plus microSD slot for removable media.

### Software & BSP
Software enablement includes CIP Kernel based Linux BSP (maintained for 10 years+) plus reference designs that highlight efficient vision AI implementations using the DRP-AI core.

### Accessories
Available accessory options include a MIPI 7-inch display, MIPI CSI camera and 5V/3A USB Type C power supply.
</details>


## Related Repositories
- [RZBoard Metalayer](https://github.com/Avnet/meta-rzboard): Contains the Yocto metalayer specific to the Rz V2L as well as **building information**
- [AI SDK](https://renesas-rz.github.io/rzv_ai_sdk/2.00/ai-sdk.html): Contains the Renesas AI SDK & **many** demo applications
- [AI Library](https://github.com/Ignitarium-Renesas/RZV2L_AiLibrary): API functions for leveraging AI applications that will run on Renesas RZ/V2L Board
- [Trail Cam Demo](https://github.com/Avnet/RzBoard-Trail-Camera-Demo): Demo of trail-cam capabilites
- [AI Launch Demo](https://github.com/Avnet/rzboard_demo_launcher): Demo of AI & IoT capabilities of the Rz V2L
- [Flashing Utility](https://github.com/Avnet/rzboard_flash_util): Platform agnostic RzV2L flashing utility

## Related Blog Posts

| Topic | Description | Difficulty |
| -- | -- | -- |
| [AI Apps Integrating Linux with RTOS for Real Time Detection](https://www.hackster.io/bernard-ngabonziza/ai-apps-integrating-linux-with-rtos-for-real-time-detection-3e7b66) | Fast boot real-time inference at the edge by integrating Linux with RTOS on Avnet's RzBoard | Advanced |
| [Train & Deploy ML Model on RzBoard with Edge-Impulse](https://www.hackster.io/bernard-ngabonziza/train-deploy-ml-model-on-rzboard-with-edge-impulse-ff846e) | Running embedded Machine Learning on RzBoard: Train a Machine learning Model on edge impulse and Deploy it on RzBoard as DRP-AI library | Advanced |
| [Build your yocto image for RzBoard and Network boot it](https://www.hackster.io/bernard-ngabonziza/build-your-yocto-image-for-rzboard-and-network-boot-it-0e96b4) | Building an RZ/V2L image from an ubuntu machine | Advanced |
| [Build an RzBoard Yocto Image integrated with FreeRTOS](https://www.hackster.io/bernard-ngabonziza/build-an-rzboard-yocto-image-integrated-with-freertos-085ceb) | Build your Yocto Image and integrate it with FreeRTOS on RzBoard for real time detection ML Apps | Advanced |
| [Run Machine Learning on the RzBoard](https://www.hackster.io/monica/run-machine-learning-on-the-rzboard-326098) | Translate an onnx model so you can easily run it on Avnet's RzBoard | Intermediate |
| [DRP-AI dashboard for vision-AI processing on RZBoard V2L](https://www.hackster.io/peter-fenn/drp-ai-dashboard-for-vision-ai-processing-on-rzboard-v2l-527098) | Browser-based AI inference exercises using USB camera and power-efficient DRP-AI acceleration | Intermediate |
| [Monitoring retail checkout lines with Renesas RZ/V2L](https://www.hackster.io/sologithu/monitoring-retail-checkout-lines-with-renesas-rz-v2l-kit-769df0) | Counting people at different checkout lines using an Edge Impulse YOLOv5 | Intermediate |
| [Product inspection with Renesas RZ/V2L and Edge Impulse](https://www.hackster.io/sologithu/product-inspection-with-renesas-rz-v2l-and-edge-impulse-cf0700) | Performing quality inspection for manufactured parts using Edge Impulse | Intermediate |
| [Counting inventory with Renesas RZ/V2L kit](https://www.hackster.io/sologithu/counting-inventory-with-renesas-rz-v2l-kit-a9cb2e) | Count and analyze different inventory products using an Edge Impulse YOLOv5 model | Intermediate |


## Getting Started and Manuals
### Product Brief
- [Block Diagram](https://www.avnet.com/wps/wcm/connect/onesite/0db4f6f2-d463-40d0-9175-60b0adf1a310/P22_762_RZBoard-V2L-diagram.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-0db4f6f2-d463-40d0-9175-60b0adf1a310-o2QupOk)
- [Product Brief](https://www.avnet.com/wps/wcm/connect/onesite/82f0d2aa-3c73-4275-8849-d1e39a7b9ac9/FY23_800_RZBoard_V2L_Product_Brief_al.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-82f0d2aa-3c73-4275-8849-d1e39a7b9ac9-oksCzeU)
### Getting Started Guide
- [Yocto User Manual](https://www.avnet.com/wps/wcm/connect/onesite/9fe02bc9-8335-4da2-924a-1bdde941e534/RzBoard-Linux-Yocto-UserManual-v2.2.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-9fe02bc9-8335-4da2-924a-1bdde941e534-oFe8N5b)
### Hardware Guide
- [Quick Start Guide](https://www.avnet.com/wps/wcm/connect/onesite/ce8a3314-917a-4f34-88fe-9070f3ead337/RzBoard+V2L+Quick+StartGuide+v1.1.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-ce8a3314-917a-4f34-88fe-9070f3ead337-ogmeZpu)
- [User Guide](https://www.avnet.com/wps/wcm/connect/onesite/86d72e54-3eef-4ceb-8464-de54e28dd79f/RzBoard+V2L+Hardware+User+Guide+%28v1.0%29.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-86d72e54-3eef-4ceb-8464-de54e28dd79f-ogmeSxB)
### Development Guides
- [Yocto Development Guide](https://www.avnet.com/wps/wcm/connect/onesite/463da618-000a-4989-aad6-785cf45bb84d/RZBoard-Linux-Yocto-Development-Guide-v2.6.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-463da618-000a-4989-aad6-785cf45bb84d-oFe8GfG)
