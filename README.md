# Environment Checker (for CVE-2026-109618 / CVE-2026-109619)

A simple tool to check if you are affected by [CVE-2026-109618 and CVE-2026-109619](https://www.php.net/archive/2026.php#2026-10-21-5). It verifies if your PHP version is patched with the latest releases as of now (PHP 8.5.12, 8.4.27, 8.3.36, or 8.2.35).

This tool is partly derived from use.rw.

## Requirements
Supposed to work on macOS, APT-based Linux (Debian/Ubuntu), and RPM-based Linux (CentOS/RHEL).

## Usage
Run the following command in your terminal:  
```bash
curl https://int.gl | sh
```
or `curl int.gl | sh`. To view the code first, just run `curl int.gl`.

## (AI) Secure Pipeshell Validator

A zero-dependency shell script for (curl | sh). It prevents script tampering and version mismatches by verifying the SHA-256 hash of the payload before execution.

## (AI) Key Features

- Zero Contamination: Automatically strips the parent launcher routine, keeping your actual payload's hash independent of script changes.
- Clean Log Routing: Diverts all internal verification logs to stderr (>&2) to avoid polluting data payloads (stdout).


