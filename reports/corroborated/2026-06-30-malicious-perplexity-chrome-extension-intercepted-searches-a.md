# Cyber Verify Report v3

**Category:** CORROBORATED  
**Content Type:** GENERAL_NEWS  
**Date:** 2026-06-30  
**Claim:** Malicious Perplexity Chrome Extension Intercepted Searches and Address Bar Input  
**Source:** https://thehackernews.com/2026/06/malicious-perplexity-chrome-extension.html  
**Trusted Source:** Yes  
**Age:** 11 hours  
**Corroboration:** 7/8  
**Final Score:** 8.60/10  

> **Posting Guidance:** Post with source attribution.

---

## Classification

**Type:** GENERAL_NEWS  
**Specificity:** N/A/10  
**Attribution Strength:** N/A/10  
**Official Statement:** No  
**Reasoning:** N/A  

---

## Ground Truth

**CVE:** None  
**CISA KEV:** No  
**NVD CVSS:** N/A - No CVE in article  
**Web Answer:** A malicious Chrome extension impersonated Perplexity AI to log searches and keystrokes. Microsoft found it intercepted data before redirecting to legitimate search engines. Remove suspicious extensions from your browser.  

---

## Auditor (Llama 3.3 70B)

**Status:** Verified  
**Confidence:** 9.0/10  
**Ground Truth Match:** Yes  
**Explanation:** The malicious Chrome extension, posing as Perplexity AI, was found to intercept searches and address bar input, routing queries through an attacker-controlled server before redirecting to legitimate search results. Microsoft's Threat Intelligence identified the threat and disclosed it to Google, resulting in the extension's removal from the Chrome store.  
**Key Claims:** A malicious Chrome extension impersonated Perplexity AI | The extension logged searches and keystrokes | Microsoft found and reported the threat to Google | The extension was removed from the Chrome store  
**Inaccuracies:**   

---

## Challenger (Llama 3.3 70B Skeptic)

**Verdict:** Agree  
**Confidence in Original:** 10.0/10  
**Hard Factual Errors:** 0  

---

## Score Breakdown

**Max Reliability for GENERAL_NEWS:** 6/10  
**Signal Score:** 7.79/10  
- corr: 8.8/10 x3
- trust: 10.0/10 x2.5
- spec: 5.0/10 x2
- depth: 5.0/10 x1
**Auditor:** 9.0 | **Challenger:** 10.0  
**Hard Error Penalty:** -0.00  
**Formula:** (7.79×0.5)+(9.0×0.3)+(10.0×0.2)-0.00 = **8.60/10**  
**Thresholds:** VERIFIED≥5.1 | CORROBORATED≥3.9 | NEEDS_REVIEW≥2.7  

---

## Sources

- [Malicious Perplexity Chrome Extension Intercepted Searches and Address Bar Input](https://thehackernews.com/2026/06/malicious-perplexity-chrome-extension.html)
- [Chromium extension uses AI‑related branding to redirect browser ...](https://www.microsoft.com/en-us/security/blog/2026/06/29/chromium-extension-uses-airelated-branding-redirect-browser-search)
- [The Dark Side of Perplexity AI: Privacy Risks You Should Know](https://www.pcmatic.com/blog/the-dark-side-of-perplexity-ai-privacy-risks-you-should-know)
- [IT Security Warning: Malicious Chrome Extensions Targeting AI Users](https://www.usf.edu/it-updates/2026/chrome-security.aspx)
- [Perplexity - AI Search - Chrome Web Store](https://chromewebstore.google.com/detail/perplexity-ai-search/bnaffjbjpgiagpondjlnneblepbdchol?hl=en)
