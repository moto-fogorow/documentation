---
title: Partitions
---

:::note
Most sections are only accessible via mtkclient
:::

[//]: # (✅    | ❌)
| Partition       | Address     | Size        | Empty   | Writable |
|-----------------|-------------|-------------|---------|----------|
| preloader       | 0x0         | 0x80000     | ❌       | ❌        |
| pgpt            | 0x0         | 0x8000      | ❌       | ❌        |
| misc            | 0x8000      | 0x80000     | ❌       | ❌        |
| para            | 0x88000     | 0x80000     | ❌       | ❌        |
| expdb           | 0x108000    | 0x1400000   | ❌       | ❌        |
| frp             | 0x1508000   | 0x100000    | ❌       | ❌        |
| vbmeta_a        | 0x1608000   | 0x800000    | ❌       | ❌        |
| vbmeta_system_a | 0x1e08000   | 0x800000    | ❌       | ✅        |
| vbmeta_vendor_a | 0x2608000   | 0x800000    | ❌       | ✅        |
| vbmeta_b        | 0x2e08000   | 0x800000    | ✅       | ✅        |
| vbmeta_system_b | 0x3608000   | 0x800000    | ✅       | ✅        |
| vbmeta_vendor_b | 0x3e08000   | 0x800000    | ✅       | ✅        |
| md_udc          | 0x4608000   | 0x169a000   | ❌       | ❌        |
| metadata        | 0x5ca2000   | 0x2000000   | ✅       | ❌        |
| nvcfg           | 0x7ca2000   | 0x2000000   | ❌       | ❌        |
| nvdata          | 0x9ca2000   | 0x4000000   | ❌       | ❌        |
| persist         | 0xdca2000   | 0x3000000   | ❌       | ❌        |
| protect1        | 0x10ca2000  | 0x800000    | ❌       | ❌        |
| protect2        | 0x114a2000  | 0xb5e000    | ❌       | ❌        |
| seccfg          | 0x12000000  | 0x800000    | ❌       | ❌        |
| md1img_a        | 0x12800000  | 0x8000000   | ❌       | ❌        |
| spmfw_a         | 0x1a800000  | 0x100000    | ❌       | ❌        |
| scp_a           | 0x1a900000  | 0x600000    | ❌       | ❌        |
| sspm_a          | 0x1af00000  | 0x100000    | ❌       | ❌        |
| gz_a            | 0x1b000000  | 0x1000000   | ❌       | ❌        |
| lk_a            | 0x1c000000  | 0x200000    | ❌       | ❌        |
| boot_a          | 0x1c200000  | 0x2000000   | ❌       | ❌        |
| vendor_boot_a   | 0x1e200000  | 0x4000000   | ❌       | ✅        |
| init_boot_a     | 0x22200000  | 0x800000    | ✅       | ❌        |
| dtbo_a          | 0x22a00000  | 0x800000    | ❌       | ❌        |
| tee_a           | 0x23200000  | 0x600000    | ❌       | ❌        |
| sec1            | 0x23800000  | 0x200000    | ✅       | ❌        |
| proinfo         | 0x23a00000  | 0x300000    | ❌       | ❌        |
| efuse           | 0x23d00000  | 0x80000     | ❌       | ❌        |
| boot_para       | 0x23d80000  | 0x1a00000   | ❌       | ❌        |
| nvram           | 0x25780000  | 0x4000000   | ❌       | ❌        |
| logo            | 0x29780000  | 0x880000    | ❌       | ❌        |
| md1img_b        | 0x2a000000  | 0x8000000   | ❌       | ❌        |
| spmfw_b         | 0x32000000  | 0x100000    | ✅       | ❌        |
| scp_b           | 0x32100000  | 0x600000    | ✅       | ❌        |
| sspm_b          | 0x32700000  | 0x100000    | ✅       | ❌        |
| gz_b            | 0x32800000  | 0x1000000   | ❌       | ❌        |
| lk_b            | 0x33800000  | 0x200000    | ❌       | ❌        |
| boot_b          | 0x33a00000  | 0x2000000   | ❌       | ❌        |
| vendor_boot_b   | 0x35a00000  | 0x4000000   | ✅       | ✅        |
| init_boot_b     | 0x39a00000  | 0x800000    | ✅       | ❌        |
| dtbo_b          | 0x3a200000  | 0x800000    | ❌       | ❌        |
| tee_b           | 0x3aa00000  | 0x500000    | ✅       | ❌        |
| oem_mfd         | 0x3af00000  | 0x100000    | ❌       | ❌        |
| elabel          | 0x3b000000  | 0x1800000   | ❌       | ❌        |
| super           | 0x3c800000  | 0x200000000 | ❌       | ❌        |
| blackbox        | 0x23c800000 | 0x8000000   | ❌       | ❌        |
| userdata        | 0x244800000 | 0xc0000000  | ❌       | ❌        |
| mrdump          | 0xFFFF0258  | 0x1000000   | ✅       | ❌        |
| otp             | 0xFFFF01d8  | 0x2b00000   | ✅       | ❌        |
| flashinfo       | 0xFFFF0080  | 0x1000000   | ❌       | ❌        |
| sgpt            | 0xFFFF0000  | 0x8000      | ❌       | ❌        |
