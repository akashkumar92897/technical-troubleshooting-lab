# No Internet Connectivity

## Scenario

A user reports that their Windows computer is connected to a network, but they cannot access websites or other internet-based services.

The objective is to determine where connectivity is failing by checking the network connection, IP configuration, gateway, external connectivity, DNS resolution, and application or browser behavior.

---

## Symptoms

Reported symptoms may include:

- Websites do not load.
- Applications cannot connect to online services.
- Windows shows limited or no internet access.
- The device appears connected to Wi-Fi or Ethernet but internet access does not work.
- Other devices may or may not be experiencing the same problem.

---

## Information to Collect

Before troubleshooting, gather relevant information from the user.

### Basic Questions

- Is the computer connected through Wi-Fi or Ethernet?
- Does the network icon show a connection?
- When did the problem start?
- Was internet access working previously?
- Are other websites affected?
- Are other applications affected?
- Are other devices on the same network able to access the internet?
- Did the user recently change any network settings?
- Is a VPN currently connected?

### Scope

Determine whether the issue affects:

- One device
- Multiple devices
- One user
- Multiple users
- One website/application
- All internet access

The scope helps determine whether the problem is likely to be local or network-wide.

---

## Possible Causes

Possible causes include:

- Wi-Fi or Ethernet connectivity problem
- Incorrect IP configuration
- DHCP issue
- Default gateway problem
- DNS resolution failure
- VPN configuration problem
- Browser-specific issue
- Firewall or security configuration
- Network outage
- Router or network equipment problem

These are possible causes and should be tested rather than assumed.

---

## Troubleshooting Steps

### Step 1 — Check Physical or Wireless Connectivity

Verify:

- Ethernet cable is connected, if applicable.
- Wi-Fi is enabled.
- The correct wireless network is selected.
- Airplane mode is disabled.
- The device shows an active network connection.

If the device is not connected to the network, resolve the connection problem before continuing.

---

### Step 2 — Check IP Configuration

On Windows, use:

```text
ipconfig