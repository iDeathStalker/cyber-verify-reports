# Cyber Verify Report v2

**Date:** 2026-06-26  
**Claim:** New DirtyClone Linux Kernel Flaw Lets Local Users Gain Root via Cloned Packets  
**Source:** https://thehackernews.com/2026/06/new-dirtyclone-linux-kernel-flaw-lets.html  
**Source Trusted:** Yes  
**Article Age:** 1 hours  
**Corroborating Sources:** 7/8  
**Final Score:** 6.3/10  
**Verdict:** FLAGGED - DO NOT PUBLISH  

---

## Ground Truth Data

**CVE:** CVE-2026-43503  
**In CISA KEV (Actively Exploited):** No  
**NVD CVSS Score:** 8.8 (HIGH)  
**NVD Description:** In the Linux kernel, the following vulnerability has been resolved:

net: skbuff: propagate shared-frag marker through frag-transfer helpers

Two frag-transfer helpers (__pskb_copy_fclone() and skb_shift()) fail
to propagate the SKBFL_SHARED_FRAG bit in skb_shinfo()->flags when
moving frags from sou  
**Web Search Answer:** A new Linux kernel flaw, DirtyClone, allows local users to gain root access. It was patched on May 21, 2026. Ensure systems are updated.  

---

## Auditor Verdict (Groq / Llama 3.3 70B)

**Status:** Verified  
**Confidence:** 9.0/10  
**Ground Truth Match:** Yes  
**Explanation:** The claim is supported by a working exploit walkthrough published by JFrog Security Research and corroborated by multiple trusted sources. The vulnerability, tracked as CVE-2026-43503, is a high-severity Local Privilege Escalation (LPE) flaw that allows a local user to corrupt file-backed memory through a cloned network packet and gain root. The patch for this vulnerability has been merged into the Linux kernel.  

**Key Claims:**  
- New Linux kernel flaw, DirtyClone, allows local users to gain root access.
- The vulnerability is tracked as CVE-2026-43503 and has a CVSS score of 8.8.
- A working exploit walkthrough has been published by JFrog Security Research.

**Inaccuracies:**  
- The claim states that the patch landed, but it does not specify the exact date. However, according to the ground truth, the patch was merged on May 21, 2026.

**Assumptions:**  
- It is assumed that the CVE-2026-43503 is a valid and accurate identifier for the vulnerability.

---

## Challenger Verdict (Groq / Mixtral 8x7B)

**Verdict:** Disagree  
**Confidence in Original:** 2.0/10  

**Disagreements:**  
- The audit assumes CVE-2026-43503 is a valid identifier without verifying its authenticity or ensuring it hasn't been disputed or reassigned.
- The claim of a 'high-severity Local Privilege Escalation (LPE) flaw' is not quantitatively supported; severity should be assessed based on CVSS scores or similar metrics, not just qualitatively stated.
- The audit does not provide evidence that the exploit walkthrough published by JFrog Security Research has been peer-reviewed or replicated by other researchers.
- The number of corroborating sources is mentioned as 7, but their credibility and relevance are not evaluated.

**Logical Flaws:**  
- The audit cites a single source (JFrog Security Research) for the exploit walkthrough and does not consider potential biases or errors in the reporting.
- The ground truth match is marked as true but is based on unverified claims of CISA KEV match and trusted sources without providing concrete evidence.

**Missing Context:**  
- The exact date of the patch merge (May 21, 2026) is provided but not verified against official Linux kernel patch records or changelogs.
- The audit lacks discussion on potential mitigations or workarounds for systems that cannot immediately apply the patch.

---

## Score Breakdown

- Base (avg of both models): 5.5
- Bonus (CISA/source/corroboration): +3.0
- Penalty (disagreements/flaws): -2.2
- **Final: 6.3/10**

---

## Search Sources

- [Dissecting and Exploiting Linux LPE Variant: DirtyClone (CVE-2026-43503) - JFrog Security Research](https://research.jfrog.com/post/dissecting-and-exploiting-linux-lpe-variant-dirtyclone-cve-2026-43503)
- [JFrog Security on X: "🚨 Successful PoC for Linux Kernel CVE-2026-43503 (DirtyFrag variant) 🚨 JFrog researchers successfully developed a privilege escalation exploit for CVE-2026-43503, a newly discovered DirtyFrag variant we dubbed "DirtyClone". The vulnerability was patched and merged into https://t.co/LstlxUIvaj" / X](https://x.com/JFrogSecurity/status/2070144533648589079)
- [Linux Kernel Dirty Frag LPE Exploit Enables Root Access Across Major Distributions](https://thehackernews.com/2026/05/linux-kernel-dirty-frag-lpe-exploit.html)
- [Dirty Frag (CVE-2026-43284) Linux Privilege Escalation | Wiz Blog](https://www.wiz.io/blog/dirty-frag-linux-kernel-local-privilege-escalation-via-esp-and-rxrpc)
- [JFrog Security Research](https://research.jfrog.com)
