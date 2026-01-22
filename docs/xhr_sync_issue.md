# XHR Sync Issue

If you’re seeing this message, you’ve encountered a very rare problem while loading the ModLoader. Congratulations—you’re one of the few.

### Quick Fix
If you just want a fast solution, try the following:
1. Disable your browser extensions one by one.
2. Refresh the page after each change.
3. Stop once the ModLoader starts working again.

If the issue persists, please report it so we can investigate further. Providing details about your browser and installed extensions is especially helpful.

---

### Why This Happens
This error occurs when a specific piece of code (`XMLHttpRequest`) behaves asynchronously when it is expected to run synchronously.

Under normal circumstances, this should never happen. However, browser extensions can sometimes interfere with webpage behavior. In the past, certain security or antivirus extensions have been known to disrupt synchronous XHR requests—not just for ModLoader, but for many websites.

---

### Other Possible Solutions
- Try using a different browser if disabling extensions does not resolve the issue.
- Ensure your browser is fully up to date.

While browser-specific quirks causing this behavior are extremely rare, switching browsers can help rule them out.
