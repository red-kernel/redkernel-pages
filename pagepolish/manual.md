---
layout: default
title: User Manual - PagePolish
---

# PagePolish User Manual

Welcome to the official user manual for **PagePolish**. This guide will help you install, configure, and use PagePolish to keep your Confluence pages clean and professional.

## 1. Introduction
PagePolish is a Confluence Cloud app designed to automatically fix common formatting issues that occur during copy-pasting or drafting content. With a single click, it removes extra whitespace, consolidates empty lines, and cleans up your document structure.

## 2. Installation
PagePolish is available directly from the Atlassian Marketplace.

1.  Log in to your Confluence Cloud instance.
2.  Go to **Apps > Find new apps**.
3.  Search for **"PagePolish"**.
4.  Click **Get app** > **Get it now**.

Once installed, PagePolish will be available in the content action menu (the "..." button) on any Confluence page.

## 3. How to Use

### Opening the App
1.  Navigate to the Confluence page you want to format.
2.  Click the **More actions (...)** menu in the top-right corner of the page.
3.  Select **PagePolish** from the menu.

### Configuration Options
Before cleaning your page, you can customize what PagePolish fixes:

*   **Remove all empty lines**: Consolidates multiple consecutive empty lines into a single empty line, or removes them entirely depending on context.
*   **Remove horizontal rules**: Deletes all horizontal separator lines (`---`) from the page.
*   **Fix detached bullet points**: Detects bullet points that have become separated from their lists and re-attaches them.

### Scanning and Cleaning
1.  **Scan Page**: Click the **Scan** button to analyze the page without making changes. PagePolish will report how many issues it found (e.g., "Found 12 empty lines").
2.  **Clean Page**: Click the **Clean** button to apply the fixes.
3.  **Refresh**: The page will automatically reload to show the polished result.

## 4. Troubleshooting

### "Something went wrong" error
If you see an error message, try the following:
*   Refresh your browser tab and try again.
*   Ensure you have **Edit** permission for the page you are trying to clean.

### Changes not visible
*   PagePolish modifies the page content directly. If you don't see changes immediately, try manually refreshing your browser.

## 5. Support
Need more help? Valid bugs or feature requests?
Visit our [Support Page]({{ "/pagepolish/support.html" | relative_url }}) or email us at [support@redkernel.de](mailto:support@redkernel.de).
