# Cyber Verify Report v2

**Category:** 🔍 NEEDS REVIEW  
**Date:** 2026-06-28  
**Claim:** Ukraine Says Russian Intelligence Used Fake Support Texts to Steal Messaging Credentials  
**Source:** https://thehackernews.com/2026/06/ukraine-says-russian-intelligence-used.html  
**Source Trusted:** Yes  
**Article Age:** 17 hours  
**Corroborating Sources:** 8/8  
**Final Score:** 6.8/10  

> **Posting Guidance:** Quick human check needed. Conflicting signals detected. Do not post without reviewing.

---

## Ground Truth Data

**CVE:** None mentioned  
**In CISA KEV (Actively Exploited):** No  
**NVD CVSS Score:** 10 (HIGH)  
**NVD Description:** The debug command in Sendmail is enabled, allowing attackers to execute commands as root.  
**Web Search Answer:** Russian intelligence services used fake support texts to steal messaging credentials from officials, military personnel, and activists in Ukraine, Europe, and the US, according to Ukraine and the FBI. The campaign aimed to access sensitive information and personal data. The methods included social engineering and phishing techniques.  

---

## Auditor Verdict (Groq / Llama 3.3 70B)

**Status:** Verified  
**Confidence:** 9.0/10  
**Ground Truth Match:** No  
**Explanation:** The claim is supported by multiple trusted cybersecurity sources, including the Security Service of Ukraine (SSU) and the U.S. Federal Bureau of Investigation (FBI), which reported a campaign by Russian intelligence services to steal messaging credentials using fake support texts. The campaign targeted government officials, military personnel, politicians, and activists in Ukraine, Europe, and the U.S. The methods used included social engineering tactics, such as fake support SMS, to breach prominent messaging accounts and steal sensitive information.  

**Key Claims:**  
- Russian intelligence services used fake support texts to steal messaging credentials
- The campaign targeted government officials, military personnel, politicians, and activists in Ukraine, Europe, and the U.S.
- The goal was to steal credentials and sensitive information

**Inaccuracies:**  


**Assumptions:**  
- The sources are trustworthy and the information is accurate

---

## Challenger Verdict (Groq / Llama 4 Scout)

**Verdict:** Disagree  
**Confidence in Original:** 2.0/10  
**Hard Factual Disagreements:** 0  
**Philosophical Objections:** 3  

**All Disagreements:**  
- The audit assumes that the sources are trustworthy and the information is accurate, but does not provide evidence to support this assumption.
- The audit does not provide specific details about the technical methods used to verify the claims, such as IP addresses, domain names, or network logs.
- The audit mentions that the campaign targeted government officials, military personnel, politicians, and activists in Ukraine, Europe, and the U.S., but does not provide concrete evidence of the scope and scale of the campaign.

**Logical Flaws:**  
- The audit relies on second-hand information from trusted sources, but does not consider alternative explanations or contradictory evidence.
- The audit does not account for potential biases or agendas of the sources, which could impact the accuracy of the information.

**Missing Context:**  
- The audit does not provide information about the specific messaging platforms targeted, or the technical vulnerabilities exploited.
- The audit does not discuss potential mitigation strategies or recommendations for preventing similar attacks in the future.
- The audit does not provide a timeline of the campaign, including the dates and duration of the attacks.

---

## Score Breakdown

- Base (avg of both models): 5.5
- Bonus (CISA/source/corroboration/NVD): +2.5
- Penalty (hard factual errors only): -1.2
- Strong Ground Truth: No
- **Final: 6.8/10**

---

## Search Sources

- [Ukraine Says Russian Intelligence Used Fake Support Texts to Steal ...](https://thehackernews.com/2026/06/ukraine-says-russian-intelligence-used.html)
- [Russia used social engineering to breach prominent messaging accounts, Ukraine says | The Record from Recorded Future News](https://therecord.media/russia-ukraine-social-engineering-messaging-accounts)
- [The Hacker News on X: "🛑 A fake support SMS was the entry point. Ukraine’s SSU and the FBI say Russian intelligence services targeted messaging accounts used by officials, military personnel, politicians, and activists. The goal: steal credentials and sensitive information. How the campaign worked: https://t.co/hbnQgjo4e5" / X](https://x.com/TheHackersNews/status/2070922214816481528)
- [SBU, FBI Uncover Russian Cyber Campaign Targeting Officials](https://www.kyivpost.com/post/78951)
- [Russian Intelligence Services Continue to Target Commercial ...](https://www.ic3.gov/PSA/2026/PSA260626)
