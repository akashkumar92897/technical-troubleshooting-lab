# DNS Resolution Failure

## Scenario

A user reports that their computer has an active internet connection, but they cannot access a specific application or website using its domain name.

Other internet services may continue to work normally.

The objective is to determine whether the problem is related to DNS resolution and distinguish it from a general network connectivity problem.

---

## Symptoms

Reported symptoms may include:

- The computer is connected to the network.
- General internet connectivity appears to be working.
- Some websites or applications are accessible.
- A specific domain or application cannot be reached.
- The browser may display a message indicating that the server or domain could not be found.
- The application may fail when using a hostname but work when connecting through another method.

---

## Information to Collect

Before troubleshooting, gather relevant information from the user.

### Basic Questions

- What website or application cannot be accessed?
- What exact error message is displayed?
- When did the problem start?
- Was the service working previously?
- Can other websites be accessed?
- Are other users experiencing the same problem?
- Does the problem occur on other devices?
- Is the user connected through Wi-Fi or Ethernet?
- Is a VPN or proxy being used?
- Has any network configuration recently changed?

### Scope

Determine whether the issue affects:

- One device
- Multiple devices
- One user
- Multiple users
- One domain
- Multiple domains

The scope can help determine whether the issue is local or related to shared DNS or network infrastructure.

---

## What is DNS?

DNS stands for **Domain Name System**.

DNS translates human-readable domain names into IP addresses that systems can use to communicate with network services.

For example:

```text
example.com
     ↓
    DNS
     ↓
93.184.216.34