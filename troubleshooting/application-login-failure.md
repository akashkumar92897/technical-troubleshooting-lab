# Application Login Failure

## Scenario

A user reports that they cannot log in to an enterprise application.

The user enters their credentials but receives an error and cannot access the application.

The objective is to determine whether the problem is related to credentials, account status, authentication, authorization, network connectivity, VPN, or the application itself.

---

## Symptoms

Reported symptoms may include:

- Login credentials are rejected.
- The user receives an authentication error.
- The account may be locked.
- The password may have expired.
- Multi-factor authentication may fail.
- The user can authenticate but cannot access a specific feature.
- The application may be unavailable after authentication.
- Other users may or may not be experiencing the same problem.

---

## Information to Collect

Before troubleshooting, gather relevant information from the user.

### Basic Questions

- What application are you trying to access?
- What exact error message is displayed?
- When did the problem start?
- Was the user previously able to log in?
- Is this the first login attempt or a previously working account?
- Is the problem occurring on one device or multiple devices?
- Are other users able to log in?
- Is the user connected to the required network or VPN?
- Was the password recently changed?
- Is multi-factor authentication involved?
- Did anything change before the problem started?

### Scope

Determine whether the issue affects:

- One user
- Multiple users
- One device
- Multiple devices
- One application
- Multiple applications

The scope can help distinguish an individual account problem from a broader application or authentication problem.

---

## Authentication vs Authorization

Authentication and authorization are related but different concepts.

### Authentication

Authentication verifies the identity of a user.

In simple terms:

> **Authentication answers: "Who are you?"**

Examples include:

- Username and password
- Multi-factor authentication
- Single sign-on
- Authentication tokens

### Authorization

Authorization determines what an authenticated user is allowed to access.

In simple terms:

> **Authorization answers: "What are you allowed to access or do?"**

For example:

```text
User enters valid credentials
        ↓
Authentication succeeds
        ↓
User is identified
        ↓
User attempts to access a restricted feature
        ↓
Authorization check
        ↓
Access denied