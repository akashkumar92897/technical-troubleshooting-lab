# Software Installation Failure

## Scenario

A user reports that they are unable to install an approved software application on their Windows computer.

The installation process either fails with an error message or stops before the software is successfully installed.

The objective is to determine whether the issue is related to system compatibility, permissions, storage, an existing installation, dependencies, security controls, or the installer itself.

---

## Symptoms

Reported symptoms may include:

- Installation stops before completion.
- An error message appears during installation.
- The installer does not start.
- The installation completes but the application does not launch.
- The system reports insufficient permissions.
- The system reports insufficient storage.
- The installer reports missing dependencies.
- Another version of the application is already installed.

---

## Information to Collect

Before troubleshooting, gather relevant information from the user.

### Basic Questions

- What software are you trying to install?
- Is the software approved for use?
- What exact error message is displayed?
- When does the installation fail?
- Has the software been installed on this computer before?
- Is another version already installed?
- What Windows version is being used?
- How much free storage is available?
- Does the user have the required installation permissions?
- Was the installer downloaded from an approved source?
- Does the problem occur on other computers?

### Scope

Determine whether the issue affects:

- One computer
- Multiple computers
- One user
- Multiple users
- One specific software package
- Multiple software packages

The scope helps determine whether the problem is local or related to the software package or organizational environment.

---

## Possible Causes

Possible causes of installation failures include:

- Insufficient disk space
- Unsupported Windows version
- Missing system dependencies
- Insufficient permissions
- Existing or conflicting software installation
- Corrupted installer
- Incorrect installer version
- Security or endpoint protection restrictions
- Network or download problem
- Software configuration issue
- Installation package problem

These are possible causes and should be investigated rather than assumed.

---

## Troubleshooting Steps

### Step 1 — Confirm Software Approval

Before troubleshooting the installation itself, verify that the software is approved for installation according to organizational policy.

Support agents should not install unauthorized or unapproved software simply because a user requests it.

If the software is not approved, follow the organization's software request or approval process.

---

### Step 2 — Confirm System Compatibility

Check whether the software supports the user's environment.

Review:

- Windows version
- System architecture
- Required hardware
- Required dependencies
- Minimum storage requirements
- Required software versions

If the system does not meet the documented requirements, the installation may fail or the software may not function correctly.

---

### Step 3 — Check Available Storage

Verify that sufficient disk space is available.

An installer may require additional temporary storage beyond the final application size.

If storage is insufficient:

- Identify unnecessary files.
- Follow approved cleanup procedures.
- Avoid deleting business-critical or system files.
- Recheck available storage.

---

### Step 4 — Check Installation Permissions

Some software installations require elevated permissions.

Determine whether the user has the appropriate permissions or whether the installation must be performed through an approved administrative process.

Do not attempt to bypass organizational access controls.

---

### Step 5 — Check for an Existing Installation

Determine whether:

- The software is already installed.
- An older version is installed.
- A previous installation failed.
- Another application is conflicting with the installation.

If an existing version is found, follow the organization's approved upgrade, repair, or removal procedure.

Do not remove software without authorization.

---

### Step 6 — Verify the Installer

Check whether the installer:

- Came from an approved source.
- Matches the required software version.
- Downloaded successfully.
- Produces a consistent error.
- Works correctly on another approved system, where appropriate.

A corrupted or incomplete installation package may cause installation failures.

---

### Step 7 — Review the Error

Record the exact error message or error code.

For example:

```text
Installation failed.

Error Code:
0x80070005

Message:
Access is denied.