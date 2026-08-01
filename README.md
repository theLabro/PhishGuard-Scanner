<div align="center">

<img src="screenshots/banner.png" width="100%" alt="PhishGuard — Verify Before You Trust" />

<h2>PhishGuard "Verify Before You Trust"</h2>


<p>
A modern URL-security platform that helps users identify suspicious,
phishing, and malicious links before opening them.
</p>

<a href="https://phishguard.qzz.io">
  <img src="https://img.shields.io/badge/OPEN_LIVE_SITE-22C55E?style=for-the-badge&logo=googlechrome&logoColor=white" height="32" alt="Open the live PhishGuard website" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/HTML5-111820?style=flat-square&logo=html5&logoColor=22C55E" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-111820?style=flat-square&logo=css3&logoColor=22C55E" alt="CSS3" />
<img src="https://img.shields.io/badge/JavaScript-111820?style=flat-square&logo=javascript&logoColor=22C55E" alt="JavaScript" />
<img src="https://img.shields.io/badge/Firebase-111820?style=flat-square&logo=firebase&logoColor=22C55E" alt="Firebase" />
<img src="https://img.shields.io/badge/Netlify-111820?style=flat-square&logo=netlify&logoColor=22C55E" alt="Netlify" />
<img src="https://img.shields.io/badge/Python-111820?style=flat-square&logo=python&logoColor=22C55E" alt="Python" />
<img src="https://img.shields.io/badge/scikit--learn-111820?style=flat-square&logo=scikitlearn&logoColor=22C55E" alt="scikit-learn" />
<img src="https://img.shields.io/badge/Chrome_Extension-111820?style=flat-square&logo=googlechrome&logoColor=22C55E" alt="Chrome Extension" />

<br><br>

<img src="https://img.shields.io/badge/Status-Live%20%26%20Active-22C55E?style=flat-square&labelColor=0B0F12" />
<img src="https://img.shields.io/badge/Source%20Code-Private-ff4d4d?style=flat-square&labelColor=0B0F12" />
<img src="https://img.shields.io/badge/ML%20Dataset-450K%20URLs-8B5CF6?style=flat-square&labelColor=0B0F12" />
<img src="https://img.shields.io/badge/License-MIT-blue?style=flat-square&labelColor=0B0F12" />


</div>

<br/>

---

<br/>

## 🛡️ &nbsp; About

**PhishGuard** is a real-time cybersecurity web application designed to help users evaluate unfamiliar URLs before visiting them.

Submit a link to receive a clear security assessment containing a **safety score**, **risk classification**, **security indicators**, and relevant destination information.

The web scanner requires no installation or technical knowledge. Results are presented through four understandable verdicts:

<div align="center">

### 🟢 Safe &nbsp;·&nbsp; 🟡 Suspicious &nbsp;·&nbsp; 🟠 Phishing &nbsp;·&nbsp; 🔴 Malicious

</div>

> [!NOTE]
> This repository is a public showcase. The implementation source, model assets, datasets, private configuration, and internal system design are maintained separately.

<br/>

---

<br/>

## 🎯 &nbsp; Why PhishGuard?

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚠️ The Challenge</h3>
      <p>
        Unsafe links are becoming increasingly difficult to recognize through appearance alone.
        Lookalike domains, shortened URLs, misleading subdomains, and convincing brand names can
        make harmful destinations appear legitimate.
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ The Response</h3>
      <p>
        PhishGuard gives users a simple way to examine unfamiliar links before opening them.
        It translates complex security information into a clear verdict, risk level, and
        recommended action.
      </p>
    </td>
  </tr>
</table>

<br/>

PhishGuard is designed to make URL-safety information accessible to everyday users while still providing enough detail for informed decisions.

<br/>

---

<br/>

## ✨ &nbsp; What PhishGuard Offers

A focused collection of tools for examining unfamiliar links, understanding potential risks, and maintaining a private record of previous assessments.

<br/>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔍 URL Scanner</h3>
      <p>Examine unfamiliar links before deciding whether they should be trusted.</p>
      <ul>
        <li>Clear safety score and risk level</li>
        <li>Four clearly separated security verdicts</li>
        <li>Security indicators and redirect information</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>📊 Security Dashboard</h3>
      <p>Review personal scanning activity through a clean visual dashboard.</p>
      <ul>
        <li>Activity and threat-distribution charts</li>
        <li>Searchable private scan history</li>
        <li>Downloadable CSV reports</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧩 Browser Extension</h3>
      <p>Access URL-safety information directly while browsing the web.</p>
      <ul>
        <li>Compact dark-themed interface</li>
        <li>Color-coded safety indicators</li>
        <li>Support for Chromium-based browsers</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 Secure User Access</h3>
      <p>Sign in to access personalized features and privately saved information.</p>
      <ul>
        <li>Google and email authentication</li>
        <li>Private synchronized scan records</li>
        <li>Profile and session controls</li>
      </ul>
    </td>
  </tr>
</table>

<br/>

---

<br/>

## 📸 &nbsp; Preview

<br/>

<div align="center">

#### URL Scanner
<img src="screenshots/scanner.png" width="880" />

<br/><br/>

#### Scan Result
<img src="screenshots/scan-result.png" width="880" />

<br/><br/>

#### Dashboard
<img src="screenshots/dashboard.png" width="880" />

<br/><br/>

#### Sign In
<img src="screenshots/login.png" width="880" />

</div>

<br/>

---


## 🔄 &nbsp; How PhishGuard Works

PhishGuard transforms an unfamiliar URL into a clear, actionable security result through five user-facing stages.

```mermaid
%%{init: {"flowchart": {"nodeSpacing": 14, "rankSpacing": 22, "curve": "basis"}}}%%
flowchart LR
    A(["01 · Input<br/>Submit or Detect URL"])
    B(["02 · Validation<br/>Check and Prepare"])
    C(["03 · Assessment<br/>Protected Analysis"])
    D(["04 · Summary<br/>Score · Verdict · Indicators"])
    E(["05 · Result<br/>Display · Optional History"])

    A ==> B ==> C ==> D ==> E

    classDef entry fill:#0B0F12,stroke:#22C55E,color:#FFFFFF,stroke-width:2px;
    classDef validation fill:#111820,stroke:#64748B,color:#FFFFFF,stroke-width:2px;
    classDef protected fill:#163522,stroke:#4ADE80,color:#FFFFFF,stroke-width:3px;
    classDef summary fill:#111820,stroke:#22C55E,color:#FFFFFF,stroke-width:2px;
    classDef result fill:#0F2418,stroke:#4ADE80,color:#FFFFFF,stroke-width:2px;

    class A entry;
    class B validation;
    class C protected;
    class D summary;
    class E result;

    linkStyle default stroke:#22C55E,stroke-width:2.5px;
```

<div align="center">

<sub>
A URL is submitted manually or detected through the extension, checked for valid input, privately assessed, converted into an understandable security summary, and displayed to the user. Signed-in users may also save the result to their private scan history.
</sub>

</div>

<br/>

> [!NOTE]
> The **Protected Analysis** stage represents PhishGuard’s private security process. Its models, detection rules, feature engineering, thresholds, external services, and infrastructure are intentionally not disclosed.
<br/>

### Process Summary

1. A URL is submitted through the website or browser extension.
2. The input is checked and prepared for assessment.
3. PhishGuard performs its protected security analysis.
4. A safety score, verdict, security indicators, and destination details are generated.
5. The result is displayed using one of four clear classifications.
6. Signed-in users can privately save the assessment and review it through their dashboard.

> [!NOTE]
> The **Protected Security Assessment** represents PhishGuard’s private detection logic. Models, feature engineering, rules, thresholds, service providers, and infrastructure details are intentionally not disclosed.
<br/>

---

<br/>

## 🧭 &nbsp; How to Use

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>01 · Paste a URL</h3>
      <p>Copy an unfamiliar or suspicious link and paste it into the URL Scanner.</p>
    </td>
    <td width="50%" valign="top">
      <h3>02 · Start the Assessment</h3>
      <p>Select <strong>Scan URL</strong> to begin examining the submitted link.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>03 · Review the Result</h3>
      <p>Check the verdict, safety score, risk level, destination details, and displayed security indicators.</p>
    </td>
    <td width="50%" valign="top">
      <h3>04 · Decide Safely</h3>
      <p>Continue only when the result and destination are trustworthy. Signed-in users can review the scan later.</p>
    </td>
  </tr>
</table>

<br/>

---

<br/>

## 🔎 &nbsp; What a Scan Shows

Each assessment is designed to explain both the overall verdict and the most relevant information behind it.

<br/>

| Information | What It Communicates |
|:---|:---|
| **Safety Score** | A simple `0–100` representation of the assessed URL’s overall safety. |
| **Threat Verdict** | Whether the URL is classified as Safe, Suspicious, Phishing, or Malicious. |
| **Risk Level** | A plain-language indication of the level of caution required. |
| **Reputation** | Whether the destination has known or independently supported threat evidence. |
| **Certificate Status** | Whether the submitted destination provides a valid secure connection. |
| **Domain Information** | The destination domain associated with the submitted URL. |
| **Redirect Details** | Whether the submitted link leads through other destinations before reaching its final location. |
| **Security Indicators** | Important observations that may have influenced the displayed assessment. |

<br/>

---

<br/>

## 🚦 &nbsp; Understanding the Verdict

| Verdict | Meaning | Recommended Action |
|:---:|:---|:---|
| 🟢 **Safe** | No significant risk indicators were identified during the assessment. | Continue normally while confirming that the destination is expected. |
| 🟡 **Suspicious** | The URL contains unusual characteristics or incomplete trust signals. | Verify the domain and source before continuing. |
| 🟠 **Phishing** | The URL shows strong signs of impersonation, deception, or credential theft. | Do not enter personal information or account credentials. |
| 🔴 **Malicious** | The URL is associated with confirmed or independently supported threat evidence. | Avoid the destination and close the page immediately. |

<br/>

> [!WARNING]
> PhishGuard is a decision-support tool. No automated assessment can guarantee that a website is completely safe. Unexpected links, downloads, and requests for personal information should always be verified independently.

<br/>

---

<br/>

## 🗺️ &nbsp; Next Steps

Development may continue in the following areas:

- [ ] Email phishing assessment
- [ ] QR-code link inspection
- [ ] Expanded domain intelligence
- [ ] Improved reporting tools
- [ ] Enhanced mobile accessibility
- [ ] Additional threat-intelligence sources

<br/>

---

<br/>

## 👤 &nbsp; Author

<h3>Rishipratim Karmakar</h3>

PhishGuard was developed as an academic cybersecurity project focused on making URL-safety information understandable and accessible.

Feedback and discussions about the publicly available application are welcome.

<br/>

---

<br/>

<div align="center">

<h3>Ready to verify a link?</h3>

<p>Open PhishGuard and examine an unfamiliar URL before deciding whether to trust it.</p>

<a href="https://phishguard.qzz.io">
  <img src="https://img.shields.io/badge/OPEN_PHISHGUARD-phishguard.qzz.io-22C55E?style=for-the-badge&labelColor=0B0F12" height="36" alt="Open PhishGuard" />
</a>

<br/><br/>

<sub>⭐ If you find the project interesting, consider starring the repository.</sub>

</div>
