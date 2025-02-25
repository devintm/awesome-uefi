❯ lsd --tree
 .
├──  my-efi
│   ├──  Boot
│   │   ├──  BCD
│   │   ├──  bootnxt
│   │   ├──  bootuwf.dll
│   │   ├──  bootvhd.dll
│   │   └──  memtest.exe
│   ├──  bootmgr
│   ├──  EFI
│   │   ├──  BOOT
│   │   │   └──  bootx64.efi
│   │   ├──  CLOVER
│   │   │   ├──  ACPI
│   │   │   │   ├──  origin
│   │   │   │   ├──  patched
│   │   │   │   └──  WINDOWS
│   │   │   ├──  CLOVERX64.efi
│   │   │   ├──  config.plist
│   │   │   ├──  drivers
│   │   │   │   ├──  BIOS
│   │   │   │   │   ├──  EnglishDxe.efi
│   │   │   │   │   └──  XhciDxe.efi
│   │   │   │   ├──  off
│   │   │   │   │   ├──  BIOS
│   │   │   │   │   │   ├──  FileSystem
│   │   │   │   │   │   │   ├──  ApfsDriverLoader.efi
│   │   │   │   │   │   │   ├──  FSInject.efi
│   │   │   │   │   │   │   ├──  GrubEXFAT.efi
│   │   │   │   │   │   │   ├──  GrubISO9660.efi
│   │   │   │   │   │   │   ├──  GrubNTFS.efi
│   │   │   │   │   │   │   └──  GrubUDF.efi
│   │   │   │   │   │   └──  FileVault2
│   │   │   │   │   └──  UEFI
│   │   │   │   │       ├──  FileSystem
│   │   │   │   │       │   ├──  ApfsDriverLoader.efi
│   │   │   │   │       │   ├──  Fat.efi
│   │   │   │   │       │   ├──  VBoxExt2.efi
│   │   │   │   │       │   ├──  VBoxExt4.efi
│   │   │   │   │       │   ├──  VBoxHfs.efi
│   │   │   │   │       │   └──  VBoxIso9600.efi
│   │   │   │   │       ├──  FileVault2
│   │   │   │   │       │   ├──  AppleKeyFeeder.efi
│   │   │   │   │       │   └──  HashServiceFix.efi
│   │   │   │   │       ├──  HID
│   │   │   │   │       │   ├──  AptioInputFix.efi
│   │   │   │   │       │   ├──  Ps2MouseDxe.efi
│   │   │   │   │       │   ├──  UsbKbDxe.efi
│   │   │   │   │       │   └──  UsbMouseDxe.efi
│   │   │   │   │       ├──  MemoryFix
│   │   │   │   │       │   └──  OpenRuntime.efi
│   │   │   │   │       └──  Other
│   │   │   │   │           ├──  AudioDxe.efi
│   │   │   │   │           ├──  CsmVideoDxe.efi
│   │   │   │   │           ├──  EmuVariableUefi.efi
│   │   │   │   │           ├──  NvmExpressDxe.efi
│   │   │   │   │           ├──  OsxFatBinaryDrv.efi
│   │   │   │   │           └──  PartitionDxe.efi
│   │   │   │   └──  UEFI
│   │   │   │       └──  EnglishDxe.efi
│   │   │   ├──  kexts
│   │   │   │   ├──  10.11
│   │   │   │   ├──  10.12
│   │   │   │   ├──  10.13
│   │   │   │   ├──  10.14
│   │   │   │   ├──  10.15
│   │   │   │   ├──  11
│   │   │   │   ├──  12
│   │   │   │   ├──  13
│   │   │   │   ├──  14
│   │   │   │   ├──  Off
│   │   │   │   └──  Other
│   │   │   ├──  misc
│   │   │   ├──  OEM
│   │   │   │   └──  SystemProductName
│   │   │   │       ├──  config-sample.plist
│   │   │   │       └──  UEFI
│   │   │   │           └──  config-sample.plist
│   │   │   ├──  ROM
│   │   │   ├──  themes
│   │   │   │   ├──  embedded
│   │   │   │   │   ├──  screenshot.png
│   │   │   │   │   └──  theme.plist
│   │   │   │   ├──  logo_main.png
│   │   │   │   ├──  pointer-metal.png
│   │   │   │   └──  random
│   │   │   │       └──  theme.plist
│   │   │   └──  tools
│   │   ├──  DEV
│   │   │   ├──  doom.efi
│   │   │   ├──  gptsync_x64.efi
│   │   │   ├──  OneFileLinux.efi
│   │   │   ├──  RU-EFI-5.41.0434.efi
│   │   │   ├──  setup_var.efi
│   │   │   ├──  shell2.0.efi
│   │   │   ├──  Shell2.0_Full.efi
│   │   │   ├──  shell2.2-24H2.efi
│   │   │   ├──  shell2.2.efi
│   │   │   ├──  Shell_Full.efi
│   │   │   ├──  tetris.efi
│   │   │   └──  vim.efi
│   │   ├──  LIMINE
│   │   │   ├──  BOOTX64.EFI
│   │   │   ├──  limine-bios-cd.bin
│   │   │   ├──  limine-bios-hdd.h
│   │   │   ├──  limine-bios-pxe.bin
│   │   │   ├──  limine-bios.sys
│   │   │   ├──  limine-uefi-cd.bin
│   │   │   └──  limine.conf
│   │   ├──  Microsoft
│   │   │   ├──  Boot
│   │   │   │   └──  BCD
│   │   │   └──  Recovery
│   │   │       └──  BCD
│   │   ├──  REFIND
│   │   │   ├──  background.png
│   │   │   ├──  drivers_x64
│   │   │   │   ├──  btrfs_x64.efi
│   │   │   │   ├──  ext2_x64.efi
│   │   │   │   ├──  ext4_x64.efi
│   │   │   │   ├──  hfs_x64.efi
│   │   │   │   ├──  iso9660_x64.efi
│   │   │   │   └──  reiserfs_x64.efi
│   │   │   ├──  icons
│   │   │   │   ├──  arrow_left.png
│   │   │   │   ├──  arrow_right.png
│   │   │   │   ├──  boot_linux.png
│   │   │   │   ├──  boot_win.png
│   │   │   │   ├──  func_about.png
│   │   │   │   ├──  func_bootorder.png
│   │   │   │   ├──  func_csr_rotate.png
│   │   │   │   ├──  func_exit.png
│   │   │   │   ├──  func_firmware.png
│   │   │   │   ├──  func_hidden.png
│   │   │   │   ├──  func_install.png
│   │   │   │   ├──  func_reset.png
│   │   │   │   ├──  func_shutdown.png
│   │   │   │   ├──  mouse.png
│   │   │   │   ├──  os_arch.png
│   │   │   │   ├──  os_artful.png
│   │   │   │   ├──  os_bionic.png
│   │   │   │   ├──  os_centos.png
│   │   │   │   ├──  os_chakra.png
│   │   │   │   ├──  os_chrome.png
│   │   │   │   ├──  os_clover.png
│   │   │   │   ├──  os_crunchbang.png
│   │   │   │   ├──  os_debian.png
│   │   │   │   ├──  os_devuan.png
│   │   │   │   ├──  os_elementary.png
│   │   │   │   ├──  os_endeavouros.png
│   │   │   │   ├──  os_fedora.png
│   │   │   │   ├──  os_freebsd.png
│   │   │   │   ├──  os_frugalware.png
│   │   │   │   ├──  os_gentoo.png
│   │   │   │   ├──  os_gummiboot.png
│   │   │   │   ├──  os_haiku.png
│   │   │   │   ├──  os_hwtest.png
│   │   │   │   ├──  os_kubuntu.png
│   │   │   │   ├──  os_legacy.png
│   │   │   │   ├──  os_linux.png
│   │   │   │   ├──  os_linuxmint.png
│   │   │   │   ├──  os_lubuntu.png
│   │   │   │   ├──  os_mac.png
│   │   │   │   ├──  os_mageia.png
│   │   │   │   ├──  os_mandriva.png
│   │   │   │   ├──  os_manjaro.png
│   │   │   │   ├──  os_netbsd.png
│   │   │   │   ├──  os_network.png
│   │   │   │   ├──  os_opensuse.png
│   │   │   │   ├──  os_redhat.png
│   │   │   │   ├──  os_refind.png
│   │   │   │   ├──  os_refit.png
│   │   │   │   ├──  os_slackware.png
│   │   │   │   ├──  os_suse.png
│   │   │   │   ├──  os_systemd.png
│   │   │   │   ├──  os_trusty.png
│   │   │   │   ├──  os_ubuntu.png
│   │   │   │   ├──  os_uefi.png
│   │   │   │   ├──  os_unknown.png
│   │   │   │   ├──  os_void.png
│   │   │   │   ├──  os_win.png
│   │   │   │   ├──  os_win8.png
│   │   │   │   ├──  os_win_alt1.png
│   │   │   │   ├──  os_xenial.png
│   │   │   │   ├──  os_xubuntu.png
│   │   │   │   ├──  os_zesty.png
│   │   │   │   ├──  selection_big.png
│   │   │   │   ├──  selection_small.png
│   │   │   │   ├──  tool_apple_rescue.png
│   │   │   │   ├──  tool_fwupdate.png
│   │   │   │   ├──  tool_memtest.png
│   │   │   │   ├──  tool_mok_tool.png
│   │   │   │   ├──  tool_netboot.png
│   │   │   │   ├──  tool_part.png
│   │   │   │   ├──  tool_rescue.png
│   │   │   │   ├──  tool_shell.png
│   │   │   │   ├──  tool_windows_rescue.png
│   │   │   │   ├──  transparent.png
│   │   │   │   ├──  vim.png
│   │   │   │   ├──  vol_efi.png
│   │   │   │   ├──  vol_external.png
│   │   │   │   ├──  vol_internal.png
│   │   │   │   ├──  vol_net.png
│   │   │   │   ├──  vol_optical.png
│   │   │   │   ├──  win95.png
│   │   │   │   ├──  win_default.png
│   │   │   │   ├──  win_options.png
│   │   │   │   ├──  win_vmtx.png
│   │   │   │   ├──  win_wsl.png
│   │   │   │   └──  win_wsl1.png
│   │   │   ├──  refind.conf
│   │   │   ├──  refind_x64.efi
│   │   │   ├──  tools_x64
│   │   │   │   └──  Shell_Full.efi
│   │   │   └──  vars
│   │   │       └──  PreviousBoot
│   │   ├──  TOOLS
│   │   │   ├──  gdisk.efi
│   │   │   ├──  gdisk_x64.efi
│   │   │   ├──  ipxe.efi
│   │   │   ├──  memtest86.efi
│   │   │   ├──  shell.efi
│   │   │   └──  shellx64.efi
│   │   ├──  win11-hyperv
│   │   │   └──  BCD
│   │   └──  win11-vmtx
│   │       └──  BCD
│   ├──  limine.conf
│   ├──  NST
│   │   └──  boot.sdi
│   ├──  README.md
│   └──  System Volume Information
├──  README.md
└──  screenshots
    ├──  screenshot1-refind.jpg
    ├──  screenshot2-refind-windows-submenu.jpg
    ├──  screenshot3-refind.jpg
    └──  screenshot4-tetrefis.jpg
