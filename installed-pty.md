
---

# Arch Linux System Packages

This document provides an organized overview of the installed packages on this Arch Linux system. The components are categorized for clarity, reflecting the system's foundational utilities, desktop environment integrations, and various software tools.

---

## I. Core System & Development Essentials

These are the fundamental building blocks of the Arch Linux operating system and essential tools for development and system management.

```
┌── System Core & Base
│   ├── base 3-2
│   ├── base-devel 1-2
│   ├── filesystem 2025.05.03-1
│   ├── linux 6.14.7.arch2-1
│   ├── linux-api-headers 6.14-1
│   ├── linux-firmware 20250508.788aadc8-2
│   ├── linux-firmware-whence 20250508.788aadc8-2
│   ├── linux-headers 6.14.7.arch2-1
│   ├── glibc 2.41+r48+g5cb575ca9a3d-1
│   ├── systemd 257.5-3
│   ├── systemd-libs 257.5-3
│   └── systemd-sysvcompat 257.5-3
│
├── Command-Line Utilities
│   ├── bash 5.2.037-5
│   ├── bc 1.08.2-1
│   ├── brightnessctl 0.5.1-3
│   ├── coreutils 9.7-1
│   ├── diffutils 3.12-2
│   ├── fastfetch 2.44.0-1
│   ├── findutils 4.10.0-2
│   ├── grep 3.12-2
│   ├── groff 1.23.0-7
│   ├── gzip 1.14-2
│   ├── hdparm 9.65-2
│   ├── htop 3.4.1-1
│   ├── iproute2 6.15.0-1
│   ├── iptables 1:1.8.11-2
│   ├── iputils 20240905-1
│   ├── iw 6.9-1
│   ├── less 1:668-1
│   ├── lsof 4.99.4-1
│   ├── m4 1.4.20-1
│   ├── make 4.4.1-2
│   ├── man-db 2.13.1-1
│   ├── mdadm 4.4-1
│   ├── procps-ng 4.0.5-3
│   ├── psmisc 23.7-1
│   ├── sed 4.9-3
│   ├── sudo 1.9.16.p2-2
│   ├── sysstat 12.7.7-1
│   ├── tar 1.35-2
│   ├── texinfo 7.2-1
│   ├── util-linux 2.41-4
│   ├── util-linux-libs 2.41-4
│   └── which 2.23-1
│
└── Development Tools & Libraries
    ├── autoconf 2.72-1
    ├── automake 1.17-1
    ├── binutils 2.44+r94+gfe459e33c676-1
    ├── bison 3.8.2-8
    ├── dkms 3.2.1-1
    ├── fakeroot 1.37.1.2-1
    ├── flex 2.6.4-5
    ├── gcc 15.1.1+r7+gf36ec88aa85a-1
    ├── gcc-libs 15.1.1+r7+gf36ec88aa85a-1
    ├── git 2.49.0-2
    ├── go 2:1.24.3-1
    ├── jdk17-openjdk 17.0.15.u6-1
    ├── jre-openjdk 24.0.1.u9-1
    ├── libtool 2.5.4+r23+g5b582aed-1
    ├── llvm-libs 19.1.7-2
    ├── lua 5.4.7-1
    ├── luajit 2.1.1741730670-1
    ├── openjdk-src (implicit from jdk)
    ├── perl 5.40.2-1
    ├── python 3.13.3-1
    ├── yay 12.4.2-1
    └── yay-debug 12.4.2-1
```

---

## II. Wayland & Desktop Environment Components

Packages crucial for the Hyprland Wayland compositor and related desktop integrations.

```
┌── Hyprland & Wayland Base
│   ├── hyprland 0.49.0-1
│   ├── hyprcursor 0.1.12-3
│   ├── hyprgraphics 0.1.3-4
│   ├── hypridle 0.1.6-4
│   ├── hyprlock 0.8.2-1
│   ├── hyprpaper 0.7.5-1
│   ├── hyprlang-git 0.6.3.r1.g163c83b-1
│   ├── hyprutils-git 0.7.1.r0.g674ea57-1
│   ├── hyprwayland-scanner-git 0.4.4.r3.ge511882-1
│   ├── hyprland-qt-support 0.1.0-6
│   ├── hyprland-qtutils 0.1.4-2
│   ├── wayland 1.23.1-2
│   ├── wayland-protocols 1.44-1
│   ├── xdg-desktop-portal 1.20.3-1
│   ├── xdg-desktop-portal-hyprland-git 1.3.9.r7.g6036ce9-1
│   └── xdg-desktop-portal-wlr 0.7.1-1
│
├── Desktop Utilities & Integration
│   ├── alacritty 0.15.1-1               - Terminal Emulator
│   ├── dunst 1.12.2-1                   - Notification Daemon
│   ├── gammastep 2.0.11-1               - Redshift/f.lux alternative
│   ├── nm-applet 1.36.0-1               - NetworkManager applet for system tray
│   ├── network-manager-applet (alias)
│   ├── networkmanager 1.52.0-1
│   ├── blueman 2.4.4-1                  - Bluetooth Manager
│   ├── bluez 5.82-1                     - Bluetooth Stack
│   ├── bluez-utils 5.82-1
│   ├── cliphist 1:0.6.1-1               - Clipboard History
│   ├── wl-clipboard 1:2.2.1-2           - Wayland Clipboard Utilities
│   ├── grim 1.4.1-3                     - Screenshot Tool
│   ├── slurp 1.5.0-1                    - Region Selector for screenshots
│   ├── rofi 1.7.9.1-1                   - Application Launcher
│   ├── nwg-look 1.0.5-1                 - GTK Theme/Icon Config for Wayland
│   ├── waybar 0.12.0-1                  - Status Bar
│   ├── pavucontrol 1:6.1-1              - Volume Control
│   ├── playerctl 2.4.1-4                - Media Player Control
│   ├── ly 1.0.3-2                       - Login Manager (optional, if used)
│   ├── uwsm 0.21.5-1                    - User Wayland Session Manager
│   └── dconf 0.40.0-3                   - Settings Management Backend
│
├── Fonts & Cursors
│   ├── adwaita-cursors 48.0-1
│   ├── adwaita-fonts 48.2-1
│   ├── adwaita-icon-theme 48.0-1
│   ├── adwaita-icon-theme-legacy 46.2-3
│   ├── breeze-icons 6.14.0-1
│   ├── cantarell-fonts 1:0.303.1-2
│   ├── default-cursors 3-1
│   ├── gnu-free-fonts 20120503-8
│   ├── hicolor-icon-theme 0.18-1
│   ├── noto-fonts-emoji 1:2.047-1
│   └── ttf-font-awesome 6.7.2-1
```

---

## III. Software & Applications

A selection of user-facing applications for productivity, media, and specialized tasks.

```
┌── Office & Productivity
│   ├── calcurse 4.8.1-2               - Terminal Calendar
│   ├── JetBrains (not a package, implies installed IDEs)
│   └── obsidian 1.8.10-1              - Markdown Knowledge Base
│
├── Browsers & Internet
│   ├── firefox 139.0-1
│   ├── flatpak 1:1.16.1-1             - Application Packaging
│   ├── spotify 1:1.2.63.394-1         - Music Streaming Client
│   └── spicetify-cli 2.39.7-1         - Spotify Customizer
│
├── Multimedia & Graphics
│   ├── aalib 1.4rc5-18                - ASCII Art Library
│   ├── gimp 3.0.4-2                   - Image Editor
│   ├── godot (not a package, implies installed game engine)
│   ├── mesa 1:25.1.1-1                - OpenGL/Vulkan Implementation
│   ├── mesa-demos 9.0.0-6
│   ├── mesa-utils 9.0.0-6
│   ├── vmaf 3.0.0-1                   - Video Quality Assessment
│   └── virtualbox 7.1.8-4             - Virtualization Software
│       └── virtualbox-host-dkms 7.1.8-4
│
├── Database Management
│   ├── mariadb 11.7.2-3
│   ├── mariadb-clients 11.7.2-3
│   ├── mariadb-libs 11.7.2-3
│   └── mysql-workbench 8.0.42-4
│
├── Miscellaneous Utilities
│   ├── cmatrix 2.0-3                  - Scrolling Matrix Code
│   ├── electron34 34.5.6-1            - Framework for Desktop Apps
│   ├── nvtop 3.2.0-1                  - NVIDIA GPU Monitor
│   ├── peaclock 0.4.3-2               - Desktop Clock
│   ├── postman-bin 11.37.1-1          - API Development Tool
│   ├── tlp 1.8.0-1                    - Laptop Power Management
│   └── visual-studio-code-bin 1.99.1-1 - Code Editor
```

---

## IV. Libraries & Dependencies

Core libraries that support the functionality of various applications and system components.

```
┌── Core Libraries
│   ├── alsa-lib 1.2.14-1
│   ├── bzip2 1.0.8-6
│   ├── c-ares 1.34.5-1
│   ├── cairo 1.18.4-1
│   ├── curl 8.13.0-2
│   ├── dbus 1.16.2-1
│   ├── dbus-broker 36-4
│   ├── expat 2.7.1-1
│   ├── ffmpeg 2:7.1.1-3
│   ├── fontconfig 2:2.16.2-1
│   ├── freetype2 2.13.3-3
│   ├── glib2 2.84.2-1
│   ├── gnutls 3.8.9-1
│   ├── graphene 1.10.8-2
│   ├── harfbuzz 11.2.1-1
│   ├── icu 76.1-1
│   ├── json-c 0.18-2
│   ├── libarchive 3.8.0-1
│   ├── libcap 2.76-1
│   ├── libdrm 2.4.124-1
│   ├── libevent 2.1.12-4
│   ├── libffi 3.4.8-1
│   ├── libgcrypt 1.11.1-1
│   ├── libgpg-error 1.55-1
│   ├── libidn2 2.3.7-1
│   ├── libjpeg-turbo 3.1.0-1
│   ├── libpng 1.6.48-1
│   ├── libseccomp 2.5.6-1
│   ├── libsecret 0.21.7-1
│   ├── libssh 0.11.1-1
│   ├── libssh2 1.11.1-1
│   ├── libtasn1 4.20.0-1
│   ├── libtiff 4.7.0-1
│   ├── libunistring 1.3-1
│   ├── libusb 1.0.28-1
│   ├── libxml2 2.14.3-1
│   ├── libxslt 1.1.43-2
│   ├── lz4 1:1.10.0-2
│   ├── ncurses 6.5-4
│   ├── nettle 3.10.1-1
│   ├── openssl 3.5.0-1
│   ├── p11-kit 0.25.5-1
│   ├── pcre2 10.45-1
│   ├── pipewire 1:1.4.2-1
│   ├── pipewire-alsa 1:1.4.2-1
│   ├── pipewire-audio 1:1.4.2-1
│   ├── pipewire-jack 1:1.4.2-1
│   ├── pipewire-pulse 1:1.4.2-1
│   ├── pixman 0.46.0-1
│   ├── polkit 126-2
│   ├── python-gobject 3.52.3-3
│   ├── readline 8.2.013-1
│   ├── sqlite 3.49.2-1
│   ├── zlib 1:1.3.1-2
│   ├── zlib-ng 2.2.4-1
│   └── zstd 1.5.7-2
│
└── Qt & GTK Frameworks
    ├── atkmm 2.28.4-1
    ├── cairo 1.18.4-1
    ├── cairomm 1.14.5-1
    ├── cairomm-1.16 1.18.0-1
    ├── glibmm 2.66.8-1
    ├── glibmm-2.68 2.84.0-1
    ├── gtk3 1:3.24.49-2
    ├── gtk4 1:4.18.5-2
    ├── gtkmm3 3.24.10-1
    ├── gtkmm-4.0 4.18.0-2
    ├── pango 1:1.56.3-1
    ├── pangomm 2.46.4-1
    ├── pangomm-2.48 2.56.1-1
    ├── qt5-base 5.15.17+kde+r122-1
    ├── qt5-declarative 5.15.17+kde+r21-1
    ├── qt6-base 6.9.0-1
    ├── qt6-declarative 6.9.0-2
    ├── qt6-wayland 6.9.0-2
    └── xterm 399-1
```

---

## V. Drivers & Hardware Utilities

Specific packages for managing graphics, audio, and other hardware components.

```
┌── NVIDIA Graphics
│   ├── envycontrol 3.5.2-1          - GPU switcher for Optimus laptops
│   ├── nvidia-dkms 570.153.02-1     - Kernel modules
│   ├── nvidia-settings 570.153.02-1 - Configuration utility
│   └── nvidia-utils 570.153.02-1    - Core utilities
│
├── Audio & Multimedia Codecs
│   ├── alsa-card-profiles 1:1.4.2-1
│   ├── alsa-topology-conf 1.2.5.1-4
│   ├── alsa-ucm-conf 1.2.14-2
│   ├── pipewire 1:1.4.2-1
│   ├── wireplumber 0.5.10-1
│   ├── playerctl 2.4.1-4
│   ├── opus 1.5.2-1
│   └── x264 3:0.164.r3108.31e19f9-2
│
├── Other Hardware Utilities
│   ├── amd-ucode 20250508.788aadc8-2 - AMD microcode updates
│   ├── lm_sensors 1:3.6.2-1           - Hardware monitoring
│   ├── efibootmgr 18-3                - UEFI boot manager
│   ├── efivar 39-1
│   └── usbutils 018-1
```

---

## VI. Miscellaneous & Dependencies

A collection of less categorized but still important dependencies and tools.

```
┌── Various Dependencies
│   ├── abseil-cpp 20250512.0-1
│   ├── antlr4-runtime 4.13.2-1
│   ├── aom 3.12.1-1
│   ├── blosc 1.21.6-1
│   ├── brotli 1.1.0-3
│   ├── btrfs-progs 6.14-1
│   ├── bubblewrap 0.11.0-1
│   ├── ca-certificates 20240618-1
│   ├── ca-certificates-mozilla 3.112-1
│   ├── ca-certificates-utils 20240618-1
│   ├── composefs 1.0.7-1
│   ├── crypto++ 8.9.0-1
│   ├── cryptsetup 2.7.5-2
│   ├── dav1d 1.5.1-1
│   ├── db5.3 5.3.28-5
│   ├── debugedit 5.1-1
│   ├── device-mapper 2.03.32-1
│   ├── dosfstools 4.2-5
│   ├── double-conversion 3.3.1-1
│   ├── duktape 2.7.0-7
│   ├── egl-gbm 1.1.2.1-1
│   ├── egl-wayland 4:1.1.19-1
│   ├── egl-x11 1.0.1-1
│   ├── eglexternalplatform 1.2.1-1
│   ├── ell 0.77-1
│   ├── exempi 2.6.6-1
│   ├── exiv2 0.28.5-1
│   ├── fftw 3.3.10-7
│   ├── file 5.46-4
│   ├── flac 1.5.0-1
│   ├── fmt 11.2.0-1
│   ├── freeglut 3.6.0-2
│   ├── fribidi 1.0.16-2
│   ├── fuse-common 3.17.1-1
│   ├── fuse2 2.9.9-5
│   ├── fuse3 3.17.1-1
│   ├── gdbm 1.25-1
│   ├── gdk-pixbuf2 2.42.12-2
│   ├── gegl 0.4.62-1
│   ├── gettext 0.25-1
│   ├── giflib 5.2.2-2
│   ├── glslang 1:1.4.313.0-1
│   ├── glu 9.0.3-2
│   ├── gmp 6.3.0-2
│   ├── gnome-keyring 1:48.0-1
│   ├── gnulib-l10n 20241231-1
│   ├── gnupg 2.4.7-2
│   ├── gobject-introspection-runtime 1.84.0-1
│   ├── gperftools 2.16-1
│   ├── gpgme 1.24.3-2
│   ├── gpm 1.20.7.r38.ge82d1a6-6
│   ├── graphite 1:1.3.14-4
│   ├── grub 2:2.12.r292.g73d1c959-1
│   ├── gsettings-desktop-schemas 48.0-1
│   ├── gsettings-system-schemas 48.0-1
│   ├── gsm 1.0.22-2
│   ├── gssdp 1.6.3-2
│   ├── gst-plugin-pipewire 1:1.4.2-1
│   ├── gst-plugins-bad-libs 1.26.1-1
│   ├── gst-plugins-base-libs 1.26.1-1
│   ├── gstreamer 1.26.1-1
│   ├── gtest 1.17.0-1
│   ├── gtk-layer-shell 0.9.2-1
│   ├── gtk-update-icon-cache 1:4.18.5-2
│   ├── guile 3.0.10-1
│   ├── gupnp 1:1.6.8-2
│   ├── gupnp-igd 1.6.0-2
│   ├── gvfs 1.57.2-3
│   ├── hwdata 0.395-1
│   ├── iana-etc 20250502-1
│   ├── imath 3.1.12-4
│   ├── iputils 20240905-1
│   ├── iso-codes 4.18.0-1
│   ├── iwd 3.8-1
│   ├── jansson 2.14.1-1
│   ├── jasper 4.2.5-1
│   ├── java-environment-common 3-6
│   ├── java-runtime-common 3-6
│   ├── jbigkit 2.1-8
│   ├── jemalloc 1:5.3.0-5
│   ├── json-glib 1.10.6-1
│   ├── jsoncpp 1.9.6-3
│   ├── karchive 6.14.0-1
│   ├── kauth 6.14.0-1
│   ├── kbd 2.7.1-2
│   ├── kbookmarks 6.14.0-1
│   ├── kcmutils 6.14.0-1
│   ├── kcodecs 6.14.0-1
│   ├── kcolorscheme 6.14.0-1
│   ├── kcompletion 6.14.0-1
│   ├── kconfig 6.14.0-1
│   ├── kconfigwidgets 6.14.0-1
│   ├── kcoreaddons 6.14.0-1
│   ├── kcrash 6.14.0-1
│   ├── kdbusaddons 6.14.0-1
│   ├── kdecoration 6.3.5-1
│   ├── keyutils 1.6.3-3
│   ├── kglobalaccel 6.14.0-1
│   ├── kguiaddons 6.14.0-1
│   ├── ki18n 6.14.0-1
│   ├── kiconthemes 6.14.0-1
│   ├── kio 6.14.0-1
│   ├── kirigami 6.14.1-1
│   ├── kitemviews 6.14.0-1
│   ├── kjobwidgets 6.14.0-1
│   ├── kmod 34.2-1
│   ├── knewstuff 6.14.0-1
│   ├── knotifications 6.14.0-1
│   ├── kpackage 6.14.0-1
│   ├── krb5 1.21.3-1
│   ├── kservice 6.14.0-1
│   ├── kwallet 6.14.1-1
│   ├── kwidgetsaddons 6.14.0-1
│   ├── kwindowsystem 6.14.0-1
│   ├── kxmlgui 6.14.0-1
│   ├── l-smash 2.14.5-4
│   ├── lame 3.100-5
│   ├── lapack 3.12.1-2
│   ├── lcms2 2.17-1
│   ├── leancrypto 1.3.0-1
│   ├── lensfun 1:0.3.4-5
│   ├── libaec 1.1.3-2
│   ├── libaio 0.3.113-3
│   ├── libappindicator-gtk3 12.10.0.r298-4
│   ├── libass 0.17.3-1
│   ├── libassuan 3.0.0-1
│   ├── libasyncns 1:0.8+r3+g68cd5af-3
│   ├── libatasmart 0.19-6
│   ├── libavc1394 0.5.4-6
│   ├── libayatana-appindicator 0.5.94-1
│   ├── libayatana-indicator 0.9.4-1
│   ├── libb2 0.98.1-3
│   ├── libblockdev 3.3.0-1
│   ├── libblockdev-crypto 3.3.0-1
│   ├── libblockdev-fs 3.3.0-1
│   ├── libblockdev-loop 3.3.0-1
│   ├── libblockdev-mdraid 3.3.0-1
│   ├── libblockdev-nvme 3.3.0-1
│   ├── libblockdev-part 3.3.0-1
│   ├── libblockdev-swap 3.3.0-1
│   ├── libbluray 1.3.4-3
│   ├── libbpf 1.5.0-1
│   ├── libbs2b 3.1.0-9
│   ├── libbsd 0.12.2-2
│   ├── libbytesize 2.11-1
│   ├── libcanberra 1:0.30+r2+gc0620e4-4
│   ├── libcap-ng 0.8.5-3
│   ├── libcdio 2.2.0-1
│   ├── libcdio-paranoia 10.2+2.0.2-1
│   ├── libcloudproviders 0.3.6-1
│   ├── libcolord 1.4.7-2
│   ├── libcups 2:2.4.12-2
│   ├── libcurl-gnutls 8.13.0-2
│   ├── libdaemon 0.14-6
│   ├── libdatrie 0.2.13-4
│   ├── libdbusmenu-glib 16.04.0.r498-2
│   ├── libdbusmenu-gtk3 16.04.0.r498-2
│   ├── libde265 1.0.16-1
│   ├── libdecor 0.2.3-1
│   ├── libdeflate 1.23-1
│   ├── libdisplay-info 0.2.0-2
│   ├── libdovi 3.3.1-1
│   ├── libdvdnav 6.1.1-2
│   ├── libdvdread 6.1.3-2
│   ├── libebur128 1.2.6-2
│   ├── libedit 20250104_3.1-1
│   ├── libei 1.4.0-1
│   ├── libelf 0.193-2
│   ├── libepoxy 1.5.10-3
│   ├── libevdev 1.13.4-1
│   ├── libexif 0.6.25-1
│   ├── libfdk-aac 2.0.3-1
│   ├── libfontenc 1.1.8-1
│   ├── libfreeaptx 0.2.2-1
│   ├── libfreexl 2.0.0-2
│   ├── libgeotiff 1.7.4-1
│   ├── libgexiv2 0.14.5-1
│   ├── libgirepository 1.84.0-1
│   ├── libglvnd 1.7.0-1
│   ├── libgnomekbd 1:3.28.1-1
│   ├── libgudev 238-3
│   ├── libheif 1.19.8-1
│   ├── libice 1.1.2-1
│   ├── libiec61883 1.2.0-8
│   ├── libimobiledevice 1.3.0-16
│   ├── libimobiledevice-glue 1.3.1-1
│   ├── libinih 58-1
│   ├── libinput 1.28.1-1
│   ├── libisl 0.27-1
│   ├── libjxl 0.11.1-3
│   ├── libksba 1.6.7-2
│   ├── liblc3 1.1.3-1
│   ├── libldac 2.0.2.3-2
│   ├── libldap 2.6.10-1
│   ├── libliftoff 0.5.0-1
│   ├── libluv 1.48.0_2-1
│   ├── liblzf 3.6-5
│   ├── libmalcontent 0.13.0-1
│   ├── libmd 1.1.0-2
│   ├── libmm-glib 1.24.0-1
│   ├── libmng 2.0.3-4
│   ├── libmnl 1.0.5-2
│   ├── libmodplug 0.8.9.0-6
│   ├── libmpc 1.3.1-2
│   ├── libmpdclient 2.22-1
│   ├── libmypaint 1.6.1-2
│   ├── libmysofa 1.3.3-1
│   ├── libndp 1.9-1
│   ├── libnet 2:1.3-1
│   ├── libnetfilter_conntrack 1.0.9-2
│   ├── libnewt 0.52.25-1
│   ├── libnfnetlink 1.0.2-2
│   ├── libnftnl 1.2.9-1
│   ├── libnghttp2 1.65.0-1
│   ├── libnghttp3 1.9.0-1
│   ├── libnice 0.1.22-2
│   ├── libnl 3.11.0-1
│   ├── libnm 1.52.0-1
│   ├── libnma 1.10.6-3
│   ├── libnma-common 1.10.6-3
│   ├── libnotify 0.8.6-1
│   ├── libnsl 2.0.1-1
│   ├── libnvme 1.13-1
│   ├── libogg 1.3.5-2
│   ├── libopenmpt 0.7.13-2
│   ├── libp11-kit 0.25.5-1
│   ├── libpcap 1.10.5-2
│   ├── libpciaccess 0.18.1-2
│   ├── libpgm 5.3.128-3
│   ├── libpipeline 1.5.8-1
│   ├── libplacebo 7.351.0-1
│   ├── libplist 2.6.0-2
│   ├── libproxy 0.5.9-1
│   ├── libpsl 0.21.5-2
│   ├── libpulse 17.0+r43+g3e2bb8a1e-1
│   ├── libraw 0.21.4-1
│   ├── libraw1394 2.1.2-4
│   ├── librsvg 2:2.60.0-2
│   ├── librttopo 1.1.0-6
│   ├── libsamplerate 0.2.2-3
│   ├── libsasl 2.1.28-5
│   ├── libsigc++ 2.12.1-1
│   ├── libsigc++-3.0 3.6.0-1
│   ├── libsm 1.2.6-1
│   ├── libsndfile 1.2.2-3
│   ├── libsodium 1.0.20-1
│   ├── libsoup3 3.6.5-1
│   ├── libsoxr 0.1.3-4
│   ├── libspatialite 5.1.0-3
│   ├── libspiro 1:20240903-1
│   ├── libspng 0.7.4-2
│   ├── libstemmer 3.0.1-1
│   ├── libsysprof-capture 48.0-5
│   ├── libteam 1.32-2
│   ├── libthai 0.1.29-3
│   ├── libtheora 1.2.0-1
│   ├── libtirpc 1.3.6-2
│   ├── libtpms 0.10.0-1
│   ├── libunibreak 6.1-1
│   ├── libunwind 1.8.1-3
│   ├── liburing 2.9-1
│   ├── libusbmuxd 2.1.0-1
│   ├── libutempter 1.2.3-1
│   ├── libutf8proc 2.10.0-1
│   ├── libuv 1.51.0-1
│   ├── libva 2.22.0-1
│   ├── libvdpau 1.5-3
│   ├── libverto 0.3.2-5
│   ├── libvorbis 1.3.7-4
│   ├── libvpl 2.15.0-1
│   ├── libvpx 1.15.0-1
│   ├── libvterm 0.3.3-2
│   ├── libwacom 2.15.0-2
│   ├── libwebp 1.5.0-1
│   ├── libwireplumber 0.5.10-1
│   ├── libwmf 0.2.13-4
│   ├── libx11 1.8.12-1
│   ├── libxau 1.0.12-1
│   ├── libxaw 1.0.16-1
│   ├── libxcb 1.17.0-1
│   ├── libxcomposite 0.4.6-2
│   ├── libxcrypt 4.4.38-1
│   ├── libxcursor 1.2.3-1
│   ├── libxcvt 0.1.3-1
│   ├── libxdamage 1.1.6-2
│   ├── libxdmcp 1.1.5-1
│   ├── libxext 1.3.6-1
│   ├── libxfixes 6.0.1-2
│   ├── libxfont2 2.0.7-1
│   ├── libxft 2.3.9-1
│   ├── libxi 1.8.2-1
│   ├── libxinerama 1.1.5-2
│   ├── libxkbcommon 1.9.2-1
│   ├── libxkbcommon-x11 1.9.2-1
│   ├── libxkbfile 1.1.3-1
│   ├── libxklavier 5.4-6
│   ├── libxmlb 0.3.22-1
│   ├── libxmu 1.2.1-1
│   ├── libxnvctrl 570.153.02-1
│   ├── libxpm 3.5.17-2
│   ├── libxrandr 1.5.4-1
│   ├── libxrender 0.9.12-1
│   ├── libxshmfence 1.3.3-1
│   ├── libxss 1.2.4-2
│   ├── libxt 1.3.1-1
│   ├── libxtst 1.2.5-1
│   ├── libxv 1.0.13-1
│   ├── libxxf86vm 1.1.6-1
│   ├── libyaml 0.2.5-3
│   ├── libzip 1.11.4-1
│   ├── licenses 20240728-1
│   ├── lilv 0.24.26-1
│   ├── lmdb 0.9.33-1
│   ├── lua51-lpeg 1.1.0-3
│   ├── luit 20240910-1
│   ├── lzo 2.10-5
│   ├── mailcap 2.1.54-2
│   ├── mpdecimal 4.0.1-1
│   ├── mpfr 4.2.2-1
│   ├── mpg123 1.32.10-1
│   ├── msgpack-c 6.1.0-2
│   ├── mtdev 1.1.7-1
│   ├── mobile-broadband-provider-info 20240407-1
│   ├── mypaint-brushes1 1.3.1-2
│   ├── nspr 4.36-1
│   ├── nss 3.112-1
│   ├── ocl-icd 2.3.3-1
│   ├── opencore-amr 0.1.6-2
│   ├── openexr 3.3.3-1
│   ├── openjpeg2 2.5.3-1
│   ├── openssh 10.0p1-3
│   ├── orc 0.4.41-1
│   ├── ostree 2025.2-2
│   ├── pacman 7.0.0.r6.gc685ae6-2
│   ├── pacman-mirrorlist 20250522-1
│   ├── pahole 1:1.30-1
│   ├── pam 1.7.0-2
│   ├── pambase 20230918-2
│   ├── parted 3.6-2
│   ├── patch 2.8-1
│   ├── pciutils 3.13.0-2
│   ├── pcre 8.45-4
│   ├── pcsclite 2.3.3-1
│   ├── perl-error 0.17030-1
│   ├── perl-mailtools 2.22-1
│   ├── perl-timedate 2.33-7
│   ├── pinentry 1.3.1-5
│   ├── pkgconf 2.4.3-1
│   ├── plocate 1.1.23-1
│   ├── polkit-qt6 0.200.0-1
│   ├── poppler 25.05.0-1
│   ├── poppler-data 0.4.12-2
│   ├── poppler-glib 25.05.0-1
│   ├── popt 1.19-2
│   ├── portaudio 1:19.7.0-3
│   ├── proj 9.6.0-1
│   ├── pugixml 1.15-2
│   ├── python-cairo 1.28.0-1
│   ├── python-dbus 1.4.0-1
│   ├── python-distlib 0.3.9-2
│   ├── python-filelock 3.18.0-1
│   ├── python-platformdirs 4.3.6-2
│   ├── python-pyxdg 0.28-4
│   ├── python-virtualenv 20.28.0-1
│   ├── qca-qt6 2.3.10-2
│   ├── qhull 2020.2-5
│   ├── qt5-translations 5.15.17-1
│   ├── qt6-5compat 6.9.0-1
│   ├── qt6-shadertools 6.9.0-1
│   ├── qt6-svg 6.9.0-1
│   ├── qt6-tools 6.9.0-2
│   ├── qt6-translations 6.9.0-1
│   ├── rapidjson 1.1.0-6
│   ├── rav1e 0.7.1-1
│   ├── re2 1:20240702-5
│   ├── rtkit 0.13-3
│   ├── rubberband 4.0.0-1
│   ├── sbc 2.0-2
│   ├── sdbus-cpp 2.1.0-2
│   ├── sdl12-compat 1.2.68-2
│   ├── sdl2-compat 2.32.56-1
│   ├── sdl3 3.2.14-1
│   ├── seatd 0.9.1-1
│   ├── serd 0.32.4-1
│   ├── shaderc 2025.2-2
│   ├── shadow 4.17.4-1
│   ├── shared-mime-info 2.4-2
│   ├── slang 2.3.3-3
│   ├── snappy 1.2.2-2
│   ├── sndio 1.10.0-1
│   ├── solid 6.14.0-1
│   ├── sord 0.16.18-1
│   ├── sound-theme-freedesktop 0.8-6
│   ├── spdlog 1.15.3-1
│   ├── speex 1.2.1-2
│   ├── speexdsp 1.2.1-2
│   ├── spirv-tools 1:1.4.313.0-1
│   ├── sratom 0.6.2-1
│   ├── srt 1.5.4-1
│   ├── startup-notification 0.12-8
│   ├── suitesparse 7.10.3-1
│   ├── svt-av1 3.0.2-1
│   ├── syndication 6.14.0-1
│   ├── tdb 1.4.13-1
│   ├── tinysparql 3.9.2-2
│   ├── tomlplusplus 3.4.0-1
│   ├── tpm2-tss 4.1.3-1
│   ├── tree-sitter 0.25.3-1
│   ├── tree-sitter-c 0.23.5-1
│   ├── tree-sitter-lua 0.2.0-1
│   ├── tree-sitter-markdown 0.3.1-1
│   ├── tree-sitter-query 0.5.0-1
│   ├── tree-sitter-vim 0.4.0-1
│   ├── tree-sitter-vimdoc 3.0.0-1
│   ├── tslib 1.23-1
│   ├── tzdata 2025b-1
│   ├── udisks2 2.10.1-5
│   ├── unibilium 2.1.2-1
│   ├── unixodbc 2.3.12-3
│   ├── unzip 6.0-22
│   ├── upower 1.90.9-1
│   ├── v4l-utils 1.30.1-1
│   ├── vapoursynth R70-2
│   ├── vid.stab 1.1.1-2
│   ├── volume_key 0.3.12-10
│   ├── vsqlite++ 0.3.13-9
│   ├── vulkan-icd-loader 1.4.313.0-1
│   ├── webrtc-audio-processing-1 1.3-4
│   ├── wpa_supplicant 2:2.11-3
│   ├── x265 4.0-1
│   ├── xapp 2.8.9-1
│   ├── xbitmaps 1.1.3-2
│   ├── xcb-imdkit 1.0.9-1
│   ├── xcb-proto 1.17.0-3
│   ├── xcb-util 0.4.1-2
│   ├── xcb-util-cursor 0.1.5-1
│   ├── xcb-util-errors 1.0.1-2
│   ├── xcb-util-image 0.4.1-3
│   ├── xcb-util-keysyms 0.4.1-5
│   ├── xcb-util-renderutil 0.3.10-2
│   ├── xcb-util-wm 0.4.2-2
│   ├── xcur2png 0.7.1-8
│   ├── xdg-dbus-proxy 0.1.6-1
│   ├── xdg-utils 1.2.1-1
│   ├── xerces-c 3.3.0-2
│   ├── xf86-input-libinput 1.5.0-1
│   ├── xf86-video-vesa 2.6.0-2
│   ├── xkeyboard-config 2.44-1
│   ├── xorg-bdftopcf 1.1.2-1
│   ├── xorg-docs 1.7.3-2
│   ├── xorg-font-util 1.4.1-2
│   ├── xorg-fonts-100dpi 1.0.4-3
│   ├── xorg-fonts-75dpi 1.0.4-2
│   ├── xorg-fonts-alias-100dpi 1.0.5-1
│   ├── xorg-fonts-alias-75dpi 1.0.5-1
│   ├── xorg-fonts-encodings 1.1.0-1
│   ├── xorg-iceauth 1.0.10-1
│   ├── xorg-mkfontscale 1.2.3-1
│   ├── xorg-server 21.1.16-1
│   ├── xorg-server-common 21.1.16-1
│   ├── xorg-server-devel 21.1.16-1
│   ├── xorg-server-xephyr 21.1.16-1
│   ├── xorg-server-xnest 21.1.16-1
│   ├── xorg-server-xvfb 21.1.16-1
│   ├── xorg-sessreg 1.1.4-1
│   ├── xorg-setxkbmap 1.3.4-2
│   ├── xorg-smproxy 1.0.8-1
│   ├── xorg-util-macros 1.20.2-1
│   ├── xorg-x11perf 1.7.0-1
│   ├── xorg-xauth 1.1.4-1
│   ├── xorg-xbacklight 1.2.4-1
│   ├── xorg-xcmsdb 1.0.7-1
│   ├── xorg-xcursorgen 1.0.9-1
│   ├── xorg-xdpyinfo 1.3.4-2
│   ├── xorg-xdriinfo 1.0.7-2
│   ├── xorg-xev 1.2.6-1
│   ├── xorg-xgamma 1.0.7-2
│   ├── xorg-xhost 1.0.10-1
│   ├── xorg-xinit 1.4.4-1
│   ├── xorg-xinput 1.6.4-2
│   ├── xorg-xkbcomp 1.4.7-1
│   ├── xorg-xkbevd 1.1.6-1
│   ├── xorg-xkbprint 1.0.7-1
│   ├── xorg-xkbutils 1.0.6-1
│   ├── xorg-xkill 1.0.6-2
│   ├── xorg-xlsatoms 1.1.4-2
│   ├── xorg-xlsclients 1.1.5-2
│   ├── xorg-xmodmap 1.0.11-2
│   ├── xorg-xpr 1.2.0-1
│   ├── xorg-xprop 1.2.8-1
│   ├── xorg-xrandr 1.5.3-1
│   ├── xorg-xrdb 1.2.2-2
│   ├── xorg-xrefresh 1.1.0-1
│   ├── xorg-xset 1.2.5-2
│   ├── xorg-xsetroot 1.1.3-2
│   ├── xorg-xvinfo 1.1.5-2
│   ├── xorg-xwayland 24.1.6-1
│   ├── xorg-xwd 1.0.9-2
│   ├── xorg-xwininfo 1.1.6-2
│   ├── xorg-xwud 1.0.7-1
│   ├── xorgproto 2024.1-2
│   ├── xvidcore 1.3.7-3
│   ├── xxhash 0.8.3-1
│   ├── xz 5.8.1-1
│   ├── yyjson 0.11.1-1
│   ├── zeromq 4.3.5-2
│   ├── zimg 3.0.5-1
│   ├── zix 0.6.2-1
│   └── zram-generator 1.2.1-1
```
