# Security Policy

**The Rose-Barrie Foundation**

We would rather hear about a problem from you than from someone who found it later. If you have found a security or safety issue in anything we publish, please tell us.

---

## Reporting

**Email: security@rosebarriefoundation.org**

Please do **not** open a public issue for a security report.

You may also use GitHub's private vulnerability reporting on any of our repositories — the **Report a vulnerability** button under the Security tab. Either route reaches us.

If you would prefer to encrypt your report, say so in a first message and we will arrange it.

### What helps

- Which repository, file, or design the issue is in, and which version or commit
- What an attacker could do with it
- How to reproduce it, including hardware if relevant
- Anything you think we might get wrong about its severity

Partial reports are welcome. Don't sit on something because it isn't fully worked out.

---

## What to expect

| | |
|---|---|
| **Acknowledgement** | Within 3 working days |
| **Initial assessment** | Within 10 working days |
| **Disclosure window** | 90 days from your report |
| **Credit** | Yours if you want it, none if you don't |

We aim to fix and publish within 90 days. If we cannot, we will tell you why and ask — not tell — whether you are willing to extend. Reasons that might come up: a fix requires a hardware change, a design has already been manufactured by someone else, or a device is subject to regulatory recertification. Those take longer than software, and we would rather explain the delay than go quiet.

You are free to disclose after 90 days whether or not we have fixed it. We will not ask you to stay silent indefinitely, and we will not threaten anyone for reporting a problem in good faith.

If a flaw is being actively exploited, or could physically harm someone, tell us immediately and we will publish a warning before a fix exists.

---

## Scope

The Foundation publishes research, hardware designs, firmware and documentation. **We do not operate a service and we do not hold user data.**

**In scope:**
- Flaws in published hardware designs, firmware or software
- Anything in a published design that could expose personal data
- Anything in a published design that could cause physical harm
- Supply-chain issues in our repositories — dependencies, build tooling, CI
- Problems with our signing keys or release integrity

**Not in scope:**
- Our website, if it is a static site with no accounts — report it anyway, but expect a shrug
- Findings in devices manufactured by other parties from our designs. We will help you reach the manufacturer, but the device is theirs and so is the obligation
- Automated scanner output with no demonstrated impact

---

## Devices built by others

We publish designs. Other people build from them, sometimes with modifications we never see.

If you find a problem in a physical device: tell us, and tell the manufacturer. If the flaw is in our published design, it is ours to fix and republish. If it was introduced downstream, we will say so publicly and point at where the design differs.

We will not defend a manufacturer's changes as though they were ours, and we will not accept blame for them either.

---

## Safe harbour

If you follow this policy, we will not pursue or support legal action against you.

Specifically, we consider the following authorised:
- Testing against your own devices and your own installations
- Reverse engineering our published designs and firmware
- Reporting what you find

We ask that you do not access, modify or exfiltrate other people's data, do not degrade a service anyone depends on, and do not test against hardware you do not own.

---

## Our own practice

- Published releases are tagged, and we do not rewrite the history of a release
- Where we sign firmware, the signing keys are held offline and rotation is documented
- Security fixes are published like everything else, under an open licence, with the issue described rather than hidden in a version bump

---

*Last reviewed: (date). This policy is reviewed annually by the Board.*
