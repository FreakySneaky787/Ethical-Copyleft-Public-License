# Changelog

All versions of the Ethical Copyleft Public License (ECPL). Each version is published as a
[release](../../releases); a project stays under the version it chose.

## v1.3 (2026-11-12)

The current version, git tag `v1.3`. Its text is in [LICENSE](LICENSE); the institutions named in Section 3(b) are in
[REFERENCE-LIST.md](REFERENCE-LIST.md).

Changes compared with v1.2:

- **New Section 0 – Definitions:** Software, Copyright Holder, Contributor, Work Based on the Software, User,
  Eligible User, Full-Time Equivalent Worker, Fiscal Year, Installation Information, Reference Bodies. Section numbers 1–13
  stay the same.
- **Section 2(a):** an individual must labor for themselves, not for, on behalf of or at the direction of anyone else
  (employee, contractor, freelancer).
- **Section 2(e):** a business that grows past the thresholds stays eligible for a **3-month transition period**, then it
  must stop or get a separate license from the copyright holder. Currency conversion, worker count and fiscal year are
  now defined.
- **Section 3:** 3(b) no longer rests on the licensor's judgment. A person or entity is restricted once a **Reference
  Body** has found it involved in the listed violations; the restriction runs from the date of the finding and ends if the
  finding is withdrawn or set aside. The Reference Bodies are fixed per release in `REFERENCE-LIST.md`. Section 3
  prevails over Section 2, including the transition period. 3(a) keeps its scope; "either" was replaced by "any of
  them" (wording fix).
- **Section 4:** every recipient receives a license **directly** from the copyright holder and every contributor.
- **Section 5:** the sentence that treated programs communicating via API, RPC, shared memory or network protocol as
  derivative works is **removed**. Such a program is not a work based on the software by that fact alone.
- **Section 6 – Suspension, cure & termination:** a violation now **suspends** the rights. Full compliance within
  **30 days** reinstates them; otherwise they end permanently and copies must be destroyed. Recipients' licenses stay
  unaffected.
- **Identifier:** `LicenseRef-ECPL-1.3` (SPDX).
- Unchanged: 1, 7, 9, 10, 11, 12, 13. Section 8 only capitalizes "Contributor".

Migration from v1.2:

- Projects stay under the version they chose. To switch, replace the `LICENSE` text, fill in the same placeholders
  (year, name, law, courts), change the version in your README and use the new identifier.
- Check whether a switch needs the consent of every copyright holder of your project.
- Section 3(b) now needs a published finding of a Reference Body. If you relied on your own judgment, that is
  no longer enough.
- Section 6: violations no longer end the license at once; the 30-day cure applies.

## v1.2

The text is in release v1.2. (Its release date is not recorded here yet.)

Changes compared with v1.0 (the text of v1.1 was not preserved, so its changes are included here):

- **New name:** "Ethical Copyleft Public License (ECPL)", before "Anti-Capitalist Software License with Copyleft &
  Protections".
- **Section 2 – Eligible users:**
  - new **2(e) small commercial enterprises**: fewer than 5 full-time equivalent workers **and** less than
    $100,000 USD gross annual revenue in the preceding fiscal year;
  - revenue and worker count are counted **cumulatively** across parent companies, subsidiaries, affiliates and the
    whole corporate group (no splitting into shell companies);
  - the worker-ownership rule now applies only to organisations under 2(d).
- **Section 3 – Restricted users & uses** (before: only organisations that are law enforcement, military or
  intelligence agencies):
  - now applies to **every** user, not only organisations;
  - adds **private security contractors** and anyone working for, contracting with or controlled by these entities;
  - adds entities and individuals involved in **human rights violations** (UN Universal Declaration of Human Rights),
    systematic labour exploitation, **forced labour** or **severe environmental destruction**.
- **New Section 5 – Network copyleft:** running the software for others over a network or API (servers, containers,
  VMs, cloud, microservices) requires offering them the complete source code (AGPL-style); software that depends on it
  via API, RPC, shared memory or a network protocol to form a combined service counts as a derivative work.
- **New Section 6 – Automatic termination:** any use outside the terms ends all rights immediately; all copies must be
  destroyed.
- **New Section 7 – Compliance & audit rights:** organisations must, on reasonable written notice, prove they are
  eligible (worker count and revenue, certified by an independent accountant or an authorised officer).
- **New Section 10 – Trademark protection:** no right to use the copyright holder's names or trademarks.
- **New Section 11 – Severability:** an invalid provision is enforced as far as possible; the rest stays in force.
- **New Section 12 – Governing law & jurisdiction:** placeholders for the licensor's country and courts.
- Unchanged in substance: attribution (1), copyleft (4), patent licence and termination (now 8), anti-tivoization
  (now 9), disclaimer of warranty and limitation of liability (now 13).
- Release fix: the formatting of the text (stray blank lines) and the last sentence of Section 13 ("…OTHER DEALINGS
  IN THE SOFTWARE.") were corrected; the terms did not change.

## v1.1

The text of this version was not preserved. Its changes are part of the list under v1.2.

## v1.0

First version, published as the "Anti-Capitalist Software License with Copyleft & Protections (v1.0)", based on the
[Anti-Capitalist Software License](https://anticapitalist.software/) v1.4: attribution,
eligible users (individuals, non-profits, educational institutions, worker-owned organisations), a ban on law
enforcement, military and intelligence agencies, copyleft, a patent licence with termination, anti-tivoization and a
disclaimer of warranty.
