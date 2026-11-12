🇨🇳 [中文](README.md) | 🇺🇸 English | 🇷🇺 [Русский](README_RU.md) | 🇮🇷 [فارسی](README_FA.md)

## Best VPN Recommendations and Server List for 2026
[https://github.com/jdnei/JiChangTuiJian](https://github.com/jdnei/JiChangTuiJian)<br>

<a id="ipv6"></a>

# 🌐 How to Enable and Test IPv6 (Updated November 12, 2026)

> Internet restrictions in mainland China are becoming increasingly strict, and many VPN servers are no longer accessible. Enabling IPv6 is strongly recommended as a potential solution. This is an essential skill that every VPN user should learn.<br>

## How to Enable IPv6

### Step 1: Check Whether IPv6 Is Available on Your Local Network

1. **Disconnect Your VPN or Proxy**

   Close all proxy applications and disable any system-wide proxy settings.

2. Visit:

   <https://ipleak.net/>

3. Check the results:

   - ✅ If two IP addresses appear and one looks similar to:

     ```text
     2a05:d014:1f70:b000:c129:d6be:c347:abcd
     ```

     This long address indicates that your local network already supports IPv6. You can proceed to the next step.

   - ❌ If you see:

     ```text
     IPv6 test not reachable. (error)
     ```

     IPv6 is not currently available on your local network, so this method will not work. Check your internet service provider's IPv6 support or your router's IPv6 settings first.

---

### Step 2: Enable IPv6 in Your VPN or Proxy Application

1. Open your VPN or proxy application.
2. Find and enable the **IPv6 inbound toggle**. Refer to the application-specific instructions below for its location.
3. **Completely close the application, then restart it.**

---

### Step 3: Verify That IPv6 Is Working

1. Enable your VPN or proxy and visit the following website again:

   <https://ipleak.net/>

2. If the results show something similar to:

   ```text
   IPv6 Address:
   2a05:d014:1f70:b000:c129:d6be:c347:abcd

   Location outside mainland China, for example:
   Amazon.com, Inc
   ```

   ✅ This indicates that IPv6 has been successfully enabled.

---

## Where to Enable IPv6 in Popular VPN Applications

### 📱 Android

| Application | Settings Path |
| --- | --- |
| **Bettbox** | More → Core Configuration → General → IPv6 |
| **Flclash** | Tools → Basic Configuration → IPv6 |
| **Flyclash** | ① Settings → Network → Allow IPv6　② Settings → Overrides → General → IPv6 Enabled |
| **Clash Meta** | ① Settings → Network → Allow IPv6　② Settings → Overrides → General → IPv6 Enabled |
| **Nekobox** | Settings → Routing Settings → Prefer IPv6 Routing |
| **V2rayNG** | Settings → VPN Settings → Enable IPv6 + Prefer IPv6 |
| **Clashmi** | Core Settings → Enable IPv6 |
| **Karing** | Top-Left Gear Icon → Enable IPv6 / Prefer IPv6 |

---

### 🍎 iOS

| Application | Settings Path |
| --- | --- |
| **Shadowrocket** | Configuration → Local Files ⓘ → Enable IPv6 + Prefer IPv6 |
| **Loon** | Configuration → Advanced Configuration → IP Stack → Prefer IPv6; also enable TUN IPv6 Configuration |
| **Karing** | Top-Left Gear Icon → Enable IPv6 / Prefer IPv6 |
| **Clashmi** | Core Settings → Enable IPv6 |

---

### 🖥 Windows

| Application | Settings Path |
| --- | --- |
| **V2rayN** | Settings → Parameter Settings → TUN Mode Settings → Enable IPv6 (TUN mode must be enabled during use) |
| **Clash Verge** | Settings → Enable IPv6 |
| **Bettbox** | More → Core Configuration → General → IPv6 |
| **Flclash** | Tools → Basic Configuration → IPv6 |
| **Clash Party / Sparkle** | Left Sidebar → Core Settings → Enable IPv6 |
| **Clashmi** | Core Settings → Enable IPv6 |
| **Karing** | Top-Left Gear Icon → Enable IPv6 / Prefer IPv6 |

> [!TIP]
> If the application names or settings paths do not exactly match your current version, search the application's settings for keywords such as **"IPv6"**, **"v6"**, or **"Inbound"**.

---

### 📖 Original Article

[How to Enable and Test IPv6](https://github.com/jdnei/ipv6#ipv6)
