# Windows Security Guide

When you first install or run ExpellusAI, Windows may show security warnings. This is normal for new software and does not mean ExpellusAI is unsafe.

## Windows SmartScreen

### What You'll See
A blue popup saying *"Windows protected your PC"* or *"Microsoft Defender SmartScreen prevented an unrecognized app from starting."*

### How to Proceed
1. Click **"More info"** on the SmartScreen popup
2. Click **"Run anyway"**

### Why This Happens
SmartScreen warns about applications that haven't yet built a reputation with Microsoft. As more users install ExpellusAI, this warning will automatically disappear.

## Smart App Control (SAC)

### What It Is
Smart App Control is a newer Windows 11 feature that blocks unsigned or unrecognized applications entirely (no "Run anyway" option).

### If SAC Blocks ExpellusAI
You'll need to either:
- **Turn off Smart App Control**: Settings → Privacy & Security → Windows Security → App & Browser Control → Smart App Control → Off
- **Note**: Once turned off, SAC cannot be re-enabled without a Windows reset

### Important
Turning off SAC is a system-wide change. If you're uncomfortable with this, please [contact us](https://expellusai.com/contact) and we can help find an alternative solution.

## Antivirus False Positives

Some antivirus software may flag ExpellusAI because it:
- Simulates mouse clicks and keyboard input (core functionality)
- Takes screenshots for screen analysis (core functionality)
- Accesses other application windows (required for automation)

These are all expected behaviors for a desktop automation tool. If your antivirus flags ExpellusAI, you can safely add it to your allowlist/exclusions.

## Our Security Practices

- All code is developed in-house by Team LazyTech
- The installer is built with industry-standard tools
- No data is collected without your knowledge — see our [Privacy Policy](https://expellusai.com/privacy)
- Screen data and credentials are processed and stored locally on your machine

## More Information

For the full guide with screenshots and step-by-step instructions, visit:
**[expellusai.com/resources/windows-security-guide](https://expellusai.com/resources/windows-security-guide)**
