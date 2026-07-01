# Cyber Verify Report v3

**Category:** CORROBORATED  
**Content Type:** GENERAL_NEWS  
**Date:** 2026-07-01  
**Claim:** SEO-Poisoned Software Sites Abuse ScreenConnect to Deploy AsyncRAT  
**Source:** https://thehackernews.com/2026/07/seo-poisoned-software-sites-abuse.html  
**Trusted Source:** Yes  
**Age:** 1 hours  
**Corroboration:** 7/8  
**Final Score:** 8.40/10  

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
**Web Answer:** Unknown threat actors use ScreenConnect to deploy AsyncRAT, a remote access trojan. This malware allows attackers to control systems, steal data, and remain undetected. The campaign targets both individuals and organizations.  

---

## Auditor (Llama 3.3 70B)

**Status:** Verified  
**Confidence:** 9.0/10  
**Ground Truth Match:** Yes  
**Explanation:** The claim is supported by credible sources, including Kaspersky and eSentire, which have reported on the campaign. The use of ScreenConnect to deploy AsyncRAT is a known tactic, and the campaign's characteristics, such as the use of spoofed websites and malicious installer archives, are consistent with the reported activity.  
**Key Claims:** Unknown threat actors are using ScreenConnect to deploy AsyncRAT | The campaign is massive, multi-domain, and multi-language | Malicious installer archives are hosted on spoofed websites | The installers masquerade as popular software  
**Inaccuracies:**   

---

## Challenger (Llama 3.3 70B Skeptic)

**Verdict:** Agree  
**Confidence in Original:** 9.0/10  
**Hard Factual Errors:** 0  

---

## Score Breakdown

**Max Reliability for GENERAL_NEWS:** 6/10  
**Signal Score:** 7.79/10  
- corr: 8.8/10 x3
- trust: 10.0/10 x2.5
- spec: 5.0/10 x2
- depth: 5.0/10 x1
**Auditor:** 9.0 | **Challenger:** 9.0  
**Hard Error Penalty:** -0.00  
**Formula:** (7.79×0.5)+(9.0×0.3)+(9.0×0.2)-0.00 = **8.40/10**  
**Thresholds:** VERIFIED≥5.1 | CORROBORATED≥3.9 | NEEDS_REVIEW≥2.7  

---

## Sources

- [How a single ScreenConnect incident exposed a massive campaign | Securelist](https://securelist.com/tr/the-soc-files-screenconnect-campaign-with-asyncrat/120472)
- [Exploring the Infection Chain: ScreenConnect’s Link to AsyncRAT Deployment | eSentire](https://www.esentire.com/blog/exploring-the-infection-chain-screenconnects-link-to-asyncrat-deployment)
- [Kaspersky warns of a large-scale сampaign using fake free software to deploy a RAT via ScreenConnect](https://www.kaspersky.com/about/press-releases/kaspersky-warns-of-a-large-scale-sampaign-using-fake-free-software-to-deploy-a-rat-via-screenconnect)
- [Trojanized ScreenConnect installers evolve, dropping multiple RATs ...](https://www.acronis.com/en/tru/posts/trojanized-screenconnect-installers-evolve-dropping-multiple-rats-on-a-single-machine)
- [AsyncRAT deployed via trojanized ScreenConnect, warns researchers | Bob Carver posted on the topic | LinkedIn](https://www.linkedin.com/posts/bobcarver_cybersecurity-screenconnect-asyncrat-activity-7373326730666835968-gIr9)
