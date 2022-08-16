# icebox
Portable GUI-driven password manager with support for vault file export and inheritor plans.


Goals:

1. Secure local storage for passwords and account credentials
  - No account requirement
  - No cloud integration
  - Local storage only
  - Strong encryption (LibreSSL's 256-bit AES implementation)
  - One master password
  - Vault contents encrypted at rest
  - Export vault as flat file, decipherable with OpenSSL/LibreSSL command-line utilities
  - Copy to clipboard w/o rendering cleartext
2. Convenience for daily users
  - Quick lookup by account name
  - Keyboard shortcuts for quick lookup and paste to clipboard
  - Secure password generation w/ flexible options*
  - Denote 2FA methods attached to accounts
  - Track last-changed date for passwords, 2FA options
  - Easy vault backup via Backblaze, Time Machine, OneDrive Backup, etc
3. Ease of use for non-technical inheritors and estate executors
  - GUI-driven
  - Cross-platform: Windows, MacOS, Linux
  - Generate separate inheritor key
  - Mark certain passwords as non-inherited