# Ethical Copyleft Public License (ECPL v1.2)

The **Ethical Copyleft Public License (ECPL)** is a source-available, strong-copyleft license designed for independent developers, non-profit organizations, educational institutions, worker cooperatives, and small teams.

It offers code transparency and collaborative freedom while establishing firm legal protection against corporate exploitation, network host bypasses, state violence, and patent aggression.

## Target Audience

The ECPL is designed for creators who want to share their source code openly with individuals and community-driven entities, but do not want large corporations or state entities to profit off their labor without contributing back or respecting ethical boundaries.

### Who is allowed to use ECPL software?

- **Individual creators** working for themselves.
- **Non-profit organizations & educational institutions**.
- **Worker cooperatives** (where all workers are owners with equal equity and voting power).
- **Small enterprises** with fewer than 5 workers and under $100,000 USD cumulative annual group revenue.

### Who is restricted?

- **Large corporations & enterprise groups** (exceeding the 5 worker or $100,000 USD thresholds).
- **Military, intelligence agencies, police force, and private security contractors**.
- **Entities engaging in human rights violations**, forced labor, or severe environmental destruction.

## Key Problems Solved by the ECPL

| Common Problem | How ECPL Solves It |
|---|---|
| **Corporate Exploitation** | Restricts usage by enterprises with over $100k gross revenue or 5+ workers across their entire parent/subsidiary group. |
| **SaaS / API Loophole** | Implements Network Copyleft (AGPL-style), forcing hosted or containerized cloud services interacting via APIs to share modified source code. |
| **Shell Company Trickery** | Calculates revenue and employee counts cumulatively across all parent companies, affiliates, and corporate group entities. |
| **Hardware Locking (Tivoization)** | Requires distributors of embedded hardware to provide installation keys so users can run modified builds on their physical devices. |
| **Patent Aggression** | Automatically revokes all patent licenses if a user files a patent lawsuit against the software or its contributors. |
| **Unenforceable Compliance** | Includes an Audit Right permitting authors to request certified revenue and headcount verifications upon reasonable notice. |

## How to Apply ECPL to Your Own Project

Adopting the ECPL for your software repository takes less than two minutes:

### Step 1: Add the License File

Copy the contents of [`LICENSE`](LICENSE) into a file named `LICENSE` or `LICENSE.txt` at the root of your project repository.

### Step 2: Fill Out Your Details

Edit the placeholders at the top and bottom of your license file:

- Replace `[Year]` with the current year.
- Replace `[Your Name or Organization]` with your copyright name.
- Replace `[Your Country/State]` and `[Your City/Region, Your Country]` with your jurisdiction (for example: *Germany*, *Switzerland*, *State of California, USA*).

### Step 3: Update Your Project's README.md

Add a section to your repository's main `README.md` file indicating the licensing status:

```markdown
## License

This project is licensed under the **Ethical Copyleft Public License (ECPL v1.2)**. 
It is free for individuals, non-profits, worker cooperatives, and small teams under $100k revenue.

See the [LICENSE](LICENSE) file for complete terms and restrictions.
```

## Frequently Asked Questions (FAQ)

### Is the ECPL an "Open Source" license?

**No.** According to the Open Source Initiative (OSI) definition, true "Open Source" licenses cannot discriminate against specific groups or commercial purposes. Because the ECPL restricts large corporations, law enforcement, and military usage, it is classified as a **Source-Available / Ethical Source License**.

### What happens if a company violates the license?

Under **Section 6 (Automatic Termination)**, any unauthorized usage or failure to comply immediately voids the license ipso facto. The offending entity loses all legal rights to use, host, or execute the software and becomes liable for copyright infringement.

### Can I copy or change the license text itself?

Everyone may copy and distribute verbatim copies of the ECPL text to license their own projects.
If you change the terms, please give your version a different name, so nobody confuses it with the ECPL.

## Versions

The current version is **ECPL v1.2**. Each version is published as a [release](../../releases), so you can always
link to the exact text you use. What changed between versions is in the [CHANGELOG](CHANGELOG.md).

## Questions and feedback

- Questions about the license, ideas and general discussion: [Discussions](../../discussions)
- Mistakes in the text or concrete suggestions for the next version: [Issues](../../issues/new/choose)

The ECPL is not legal advice. If you rely on it for important work, have it reviewed by a lawyer in your jurisdiction.
