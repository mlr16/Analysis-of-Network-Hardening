<h2> Security Risk Assessment Report </h2>

## Part 1: Selected Hardening Tools and Methods
To mitigate the four identified vulnerabilities, I recommend implementing the following network hardening measures:

**Enforce Password Policies**

- Prevents employees from sharing passwords by enforcing unique credentials for each user.
- Requires strong, complex passwords with a minimum length, special characters, and non-reusability rules.
- Uses password hashing and salting to protect stored credentials from compromise.

**Firewall Maintenance and Rule Implementation**

- Establishes firewall rules to filter and monitor inbound and outbound traffic.
- Prevents unauthorized access attempts and malicious traffic from reaching internal systems.
- Blocks unnecessary open ports and restricts access based on IP addresses, geolocation, or known threat databases.

**Implement Multifactor Authentication (MFA)**

- Adds an extra layer of security to user and admin logins by requiring an additional authentication factor beyond a password.
- Reduces the risk of credential compromise due to password sharing or brute force attacks.
- Can use one-time passwords (OTP), biometrics, or authenticator apps to secure access to systems.

## Part 2: Explanation of Recommendations

**Enforce Password Policies**

**_Effectiveness:_**
- Prevents employees from sharing passwords and reduces the risk of unauthorized access due to weak or reused credentials.

**_Implementation Frequency:_**
- Immediate implementation with regular policy reviews and updates.
- Employees should be educated on password security best practices.

**Firewall Maintenance and Rule Implementation**

**_Effectiveness:_**
- Prevents unauthorized access and detects malicious traffic, significantly reducing the likelihood of network breaches.

**_Implementation Frequency:_**
- Initial configuration should be done immediately to define inbound and outbound rules.
- Regular audits and updates should be conducted monthly or after major security events.

**Implement Multifactor Authentication (MFA)**

**_Effectiveness:_**
- Prevents unauthorized access, even if a password is compromised, by requiring additional authentication.

**_Implementation Frequency:_**
- Immediate setup for all admin accounts.
- Company-wide enforcement within a set timeline to ensure all employees are protected.

**By enforcing password policies, firewall maintenance, and MFA, the organization can eliminate password-sharing risks, secure admin credentials, regulate network traffic, and prevent unauthorized access to critical systems.**
