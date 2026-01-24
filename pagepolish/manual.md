---
layout: page
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
After scanning, PagePolish presents 4 options to customize the cleanup. The default selection is recommended to give your content a structure similar to **ChatGPT output**.

*   **Reduce consecutive empty lines** *(Recommended)*: Consolidates multiple empty lines into a single one. This improves readability without making the page too dense.
*   **Fix Bold Headings** *(Recommended)*: Removes redundant bold formatting from headings and table headers often added by external tools.
*   **Merge Blockquotes** *(Recommended)*: Merges adjacent blockquotes into a single, cohesive block.
*   **Clean Lists** *(Recommended)*: Removes empty paragraphs inside list items to fix vertical spacing issues.
*   **Detached Bullets** *(Recommended)*: Fixes bullet points that have become separated from their lists.
*   **Remove all empty lines**: Aggressively removes *all* blank lines. Use this if you want a very compact document.
*   **Horizontal Rules**: Detects and removes separator lines (`---`).

> **Tip:** We recommend keeping the default selections (all recommended fixes) to achieve the cleanest, most professional look primarily designed to match **ChatGPT Canvas** output.

### Scanning and Cleaning
1.  **Scan Page**: Click the **Scan** button to analyze the page.
2.  **Review**: See how many issues were found for each category.
3.  **Clean Page**: Click **Clean** to apply the fixes. The page will reload automatically.

### Reverting Changes
PagePolish edits your page just like a user would. If you are not happy with the result:
1.  Go to the **Page History** in Confluence (click the clock icon or "Page History" in the menu).
2.  Select the previous version (before PagePolish ran).
3.  Click **Restore** to undo the changes.
### "Something went wrong" error
If you see an error message, try the following:
*   Refresh your browser tab and try again.
*   Ensure you have **Edit** permission for the page you are trying to clean.

### Changes not visible
*   PagePolish modifies the page content directly. If you don't see changes immediately, try manually refreshing your browser.

## 5. Support
Need more help? Valid bugs or feature requests?
Visit our [Support Page]({{ "/support.html" | relative_url }}) or email us at [support@redkernel.de](mailto:support@redkernel.de).
