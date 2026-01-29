![Header Image](images/Ackee-Blockchain-Security--Audit-reports-cover.jpg)

# Ackee Blockchain Security — Public audit reports

This repository collects **public security audit reports** produced by **Ackee Blockchain Security** (Ackee Blockchain a.s.).

- **Get audited / contact**: [ackee.xyz/contact](https://ackee.xyz/contact)

## About Ackee Blockchain Security

Ackee is trusted by top-tier organizations in web3. Our mission is to contribute to a stronger blockchain ecosystem by providing **security services, tooling, and education**.

## What we do

- **Smart contract auditing**: comprehensive security audits for Solana, Ethereum, and EVM-based projects (manual reviews + extensive fuzz testing).
- **Security tooling development**: developer and auditor tooling for Solana, Ethereum, and EVM chains (including Wake and Trident).
- **Blockchain security education**: courses and training programs to onboard and upskill engineers and auditors.

## Trusted by the best

Teams we’ve worked with include **Lido**, **Safe**, **Aave**, **Axelar**, **1inch**, and more.

![Trusted by the best](images/Clients-of-Ackee-Blockchain-Security.jpg)

## Track record

Based on internal statistics referenced on our website:

- **Protecting $180B+ in TVL**
- **269 criticals and highs in 104 audits**
- **< 1 day to a finding** (on average, as of Dec 2025)

## Report contents

Each audit report typically includes:

- The **audit scope** and timeline
- A list of **findings** (with severity and remediation guidance)
- Notes on **methodology** and limitations

Reports are organized into folders within this repository (layout may vary over time).

## Notes & disclaimers

- Reports reflect the **state of the codebase at the time of the audit** and within the **agreed scope**.
- Security is not a one-time event—treat reports as one input into an ongoing security process.

## Repository contents

- Reports are stored by year (e.g. `2025/`, `2026/`)
- Each report PDF has a matching signature file: `.pdf.sig`

## Verifying report signatures

Reports have a signature that can be used to verify that the PDF has not been modified when downloaded from a source other than this repository.

- Download the [public.key](public.key) file from this repository.
- Import it with `gpg` and verify:

```bash
gpg --import public.key
gpg --verify <report>.pdf.sig <report>.pdf
```
