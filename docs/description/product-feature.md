# Product Features

The main features of the Voucher Module include:

- **Specific LLM Model Vouchers:** Superadmins can create LLM Token vouchers that are exclusive to certain LLM models (e.g., meta/llama-32-90b-instruct), preventing their use with other models. Once configured, the associated LLM model cannot be changed.

- **GPU Credit and LLM Token Vouchers:** The module allows Superadmins to generate vouchers for either a specified amount of GPU Credit (in IDR) or a defined quantity of LLM Tokens (LLM Coins).

- **Flexible Voucher Code Types:** Superadmins can choose between two code generation types:
  - **Single-User Voucher (Multi-Code):** Generates a unique voucher code for each individual voucher, meant to be redeemed once by one user.
  - **Multi-User Voucher (Single-Code):** Generates a single, common voucher code that can be redeemed by multiple users, up to a specified maximum limit.

- **Campaign Naming:** Vouchers can be associated with an optional campaign name (e.g., "linkedin June 2025", "Instagram August 2025") for better organization and tracking.

- **Voucher Management and Download:** Superadmins have comprehensive management capabilities, including viewing a list of all created vouchers with their details (code, type, quota, model, status, campaign name, expiry dates). Superadmins can also download lists of all generated voucher codes in CSV format, with the download containing every generated voucher and its individual code for a given voucher name.

- **Voucher Status and History Tracking:** The module provides functionalities for Superadmins to monitor voucher claim status, showing how many have been used, remaining balance, and details of users who redeemed them (name, email, datetime, expired claim date, expired usage date). A detailed history of voucher usage is also available.

- **User Redemption Process:** Users can log in to the Service Portal, navigate to the “Voucher” page, choose between Voucher LLM or Voucher Credit GPU, input a voucher code, and claim it. The system validates the voucher before adding the corresponding tokens or credits if valid.

- **Strict Access Control:** Only Superadmins are authorized to create, manage, download, and monitor vouchers.
