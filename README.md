![NetHunter_banner](https://github.com/user-attachments/assets/9ae2f0ef-fa85-41d1-8dbf-5260bb69690b)

# NetHunter Kernel - Samsung Galaxy S10 Exynos9820 Beyond1lte

Official lineage documentation has been moved to <a href="Documentation/README">Documentation</a>

This is a Kernel port for Kali NetHunter from LineageOS 21

Made for Samsung Galaxy S10 (Exynos9820/Beyond1lte)

## Building

You can find official build on Kali Linux website, or build it yourself from my sources.

First, clone this repository with it's submodules.

```
git clone --recurse-submodules https://github.com/V0lk3n/nethunter_kernel_samsung_exynos9820.git -b nethunter-lineage-21
```

Enter into Kali Linux Kernel Builder and copy local.config to it.

```
cd nethunter_kernel_samsung_exynos9820/kali-nethunter-kernel-builder
cp ../nh_files/local.config .
```
Build the kernel.

```
./build.sh
```

For more informations, take a read of the official Kali Linux Nethunter documentations.
