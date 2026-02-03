# Scope

This section describes the boundaries of the Voucher Module project, clearly stating what functionalities are included.

**In-Scope:**

- Creation and management of vouchers for LLM (Large Language Model) tokens and GPU (Graphics Processing Unit) credit on superadmin role.
- Ability to select specific LLM models when creating LLM vouchers.
- Option to generate vouchers as single-use or multi-use with a common code for multiple users.
- Input fields for campaign names (e.g., LinkedIn, Instagram, University campaigns) during voucher creation.
- Configuration of a maximum redemption limit for multi-use vouchers.
- Management features for Superadmins, including downloading lists of voucher codes in CSV format, viewing claim status (used, remaining, user details, redeem date, expiry dates), and viewing usage history.
- Validation mechanisms during voucher redemption by users, checking for voucher activity, prior claims, redemption quota (for multi-use), and LLM model compatibility.
- Specific roles and access controls for Superadmins (full access to generate, manage, download, and monitor vouchers) and regular users (redeem vouchers only).

**Out-of-Scope:**

- Deka LLM dashboard is out of scope
