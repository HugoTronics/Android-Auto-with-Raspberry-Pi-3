# Android Auto with Raspberry Pi 3

<p align="center">
    <img src="https://img.shields.io/badge/Platform-Raspberry%20Pi-red?style=for-the-badge&logo=raspberry-pi" alt="Raspberry Pi">
    <img src="https://img.shields.io/badge/Software-Crankshaft-green?style=for-the-badge&logo=android-auto" alt="Crankshaft">
    <img src="https://img.shields.io/badge/3D%20Printing-Support-yellow?style=for-the-badge&logo=autodesk" alt="3D Printing">
</p>

## 📖 Project Overview

This project demonstrates how to transform a Raspberry Pi 3 into an Android Auto system for your vehicle using Crankshaft. The guide covers the complete setup, from hardware selection to software configuration and 3D-printed support structures, all while maintaining a non-invasive installation in your car.

### Features

- **Low-cost Hardware Setup**: Leverage Raspberry Pi and affordable components.
- **Crankshaft Software**: Turn your Pi into an Android Auto head unit with plug-and-play functionality.
- **3D Printing**: Custom support designs for an integrated and clean installation.
- **Customization**: Tailor Android Auto settings, including sound, brightness, and connectivity.

![IMG20240907150234](https://github.com/user-attachments/assets/1b422bac-c6b5-4c25-b642-c80aa3f94fd4)

## :link: Explore the Full Project

For a detailed guide on transforming your Raspberry Pi 3 into an Android Auto system, including hardware setup, software configuration, and 3D printing tips, check out the full article:

<p align="center">
    <a href="https://hugotronics.github.io/android-auto-crankshaft-project-diy-installation-with-raspberry-pi-3/" target="_blank">
        <img src="https://img.shields.io/badge/Read%20the%20Full%20Article-%230084ff.svg?style=for-the-badge&logo=read-the-docs" alt="Read the Full Article">
    </a>
</p>

This article includes:

- **Step-by-Step Hardware Installation**: Detailed instructions on connecting the Raspberry Pi, touchscreen, and audio components.
- **Software Setup with Crankshaft**: Learn how to configure the Raspberry Pi for Android Auto functionality.
- **Customization Options**: Adjust audio, screen brightness, and other settings to enhance your driving experience.
- **3D Printing Guide**: Tips for designing and printing custom mounts to seamlessly integrate the system into your car.

Don’t miss the opportunity to explore this comprehensive guide and get the most out of your Raspberry Pi Android Auto project!


## 🚀 Getting Started

### Files Included

1. **STL Files**:
    - `STL files\Raspi_case_body.stl`: 3D model of the main body of the Raspberry Pi case, designed to house and protect the Raspberry Pi 3.
    - `STL files\Raspi_cover.stl`: 3D model of the protective cover that snaps onto the case body.
    - `STL files\Raspi_screen_cover.stl` : 3D model of the cover to securely hold the 7-inch touchscreen
    - `STL files\Sunshade.STL` : 3D model of the sunshade designed to fit around the touchscreen.

### Materials Needed

- **Raspberry Pi 3**: Ideal for Android Auto setup with Wi-Fi, Bluetooth, and USB ports.
- **Official 7-Inch Raspberry Pi Touchscreen**: Easy-to-connect display with GPIO power.
- **MicroSD Card (16GB or more)**: For OS and Crankshaft installation.
- **USB Sound Card and External Microphone**: For audio output and voice commands.
- **12V to USB Adapter**: To power the setup via your car's cigarette lighter.
- **3D Printed Support**: Designed to hold the Pi and screen securely in the car.

### Hardware Setup

1. **Connect the Display**:
   - Attach the 7-inch touchscreen to the Raspberry Pi using the ribbon cable for display and GPIO pins for power.
   
2. **Audio Setup**:
   - Connect the USB sound card to the Pi and link the audio output to your car stereo using a 3.5mm jack cable.
   
3. **Power Supply**:
   - Use a 12V to USB adapter to power the Pi from your car’s cigarette lighter.

### Software Installation

1. **Download Crankshaft**:
   - [Crankshaft](https://getcrankshaft.com): A ready-to-use image for turning your Pi into an Android Auto head unit.

2. **Install Etcher**:
   - [Balena Etcher](https://www.balena.io/etcher): Use this tool to flash the Crankshaft image onto your microSD card.
 
3. **Configure Crankshaft**:
   - Insert the microSD card into the Raspberry Pi. Crankshaft will auto-configure for your phone when connected.

### Customization Options

- **Sound Settings**: Adjust audio output levels and equalizer settings directly from the Crankshaft interface.
- **Screen Brightness**: Modify display brightness for optimal viewing under various lighting conditions.
- **Sleep Mode**: Manage power settings to conserve energy when the car is off.
- **Bluetooth & Wi-Fi**: Enable wireless connections to minimize cables inside your vehicle.

## 🧰 Installation in the Car

1. **3D Printed Mounting**:
   - Use custom 3D printed parts to securely mount the Raspberry Pi and screen on the dashboard.
   - Recommended 3D Printing Settings:
     - **Material**: PETG or ABS for high durability and resistance to temperature changes inside the car.
     - **Layer Height**: 0.2mm for a good compromise between speed and print quality.
     - **Infill**: 20-30% to provide sufficient strength while minimizing material use.

2. **Non-Invasive Setup**:
   - Utilize Velcro strips and cable ties to position the components without drilling or permanently altering the car.

3. **Cable Management**:
   - Keep cables organized and out of sight with cable clips and Velcro, maintaining a clean installation.

## 📚 Useful Links

- [Crankshaft](https://getcrankshaft.com/): Android Auto software for Raspberry Pi.
- [Balena Etcher](https://etcher.balena.io/): Flashing tool for microSD cards.
- [Everlanders YouTube Channel](https://www.youtube.com/c/Everlanders): DIY car projects and inspiration.
- [DB Tech YouTube Channel](https://www.youtube.com/channel/UCVy16RS5eEDh8anP8j94G2A): Tutorials on tech projects with Raspberry Pi.

## 🛠️ Future Improvements

- **Integration with Rearview Cameras**: Add backup camera functionality.
- **Enhanced Audio Control**: Explore advanced sound processing options.
- **Wireless Android Auto**: Implement fully wireless connections to eliminate all cables.

## 📬 Contact and Support

For any questions or further assistance, feel free to open an issue on this repository or contact me at [corsahu@gmail.com](mailto:corsahu@gmail.com).

---

Happy building and safe driving with your custom Android Auto setup!
