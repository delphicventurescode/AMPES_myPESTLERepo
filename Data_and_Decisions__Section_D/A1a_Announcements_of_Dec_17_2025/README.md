## 💻 VirtualBox Setup Guide: Fedora, Manjaro, SliTaz, & Tiny Core

When creating a new VirtualBox guest, you select the **Type** and **Version** to optimize the virtual machine's settings (like hardware emulation and kernel parameters) for the chosen operating system.

| Operating System | Based On / Notes | VirtualBox Type | VirtualBox Version | Recommended RAM (Min) | Recommended HDD (Min) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Fedora Workstation** | A community-driven version of Red Hat Enterprise Linux (RHEL). | **Linux** | **Fedora (64-bit)** | 2 GB (4 GB for smoother use) | 20 GB |
| **Manjaro XFCE** | Based on Arch Linux, but with a focus on user-friendliness. | **Linux** | **Arch Linux (64-bit)** | 2 GB | 20 GB |
| **SliTaz Linux** | An ultra-lightweight, independent distro. | **Linux** | **Other Linux (32-bit)** or **Linux 2.6 / 3.x / 4.x (32-bit)** | 256 MB | 8 GB |
| **Tiny Core Linux** | Extreme minimalism, runs mostly in RAM. | **Linux** | **Other Linux (32-bit)** or **Linux 2.6 / 3.x / 4.x (32-bit)** | 256 MB | 500 MB to 1 GB |

### Key Considerations for These Distributions:

* **Fedora Workstation:** VirtualBox has a specific `Fedora` option, which is the best choice. Due to the desktop environment (GNOME), it benefits greatly from **more RAM (4GB is ideal)** and **Video Memory (128MB)** to run smoothly.
* **Manjaro XFCE:** Manjaro is based on **Arch Linux**. Selecting the `Arch Linux` option gives the VM the most appropriate settings, though some users may choose `Other Linux (64-bit)` if the Arch option is not present in older VirtualBox versions.
* **SliTaz & Tiny Core:** These are designed to be extremely small and are often available only as 32-bit images. Since they are so minimal, you must choose a generic option like **`Other Linux`** or a low-kernel version like **`Linux 2.6 / 3.x / 4.x`** with the appropriate bit-version (32-bit or 64-bit). You can allocate very little RAM and disk space, which is great for learning the core OS concepts.
