# My Licensing Philosophy

Different projects need different freedoms, and I choose based on what I think is best for the goals of the projects

---

## The Short Version

| Project Type | License | Why |
|--------------|---------|-----|
| **Code (default)** | [Blue Oak 1.0.0](https://blueoakcouncil.org/license/1.0.0) | Permissive, readable, patent-safe |
| **SaaS/Products** | [FSL](https://fsl.software) | Source-available now, Apache-2.0 after 2 years |
| **Major OSS Work** | [EUPL-1.2](https://interoperable-europe.ec.europa.eu/collection/eupl/eupl-text-eupl-12) | This is for anything I would normally use the AGPL for, SaaS/Products that I don't want Source available initially |
| **Collaborative Tools** | [MPL-2.0](https://www.mozilla.org/en-US/MPL/2.0/) | Weak copyleft; may relicense to permissive later |
| **Configs/Dotfiles** | [0BSD](https://opensource.org/licenses/0BSD) | Zero conditions, truly free |
| **Content/Assets** | [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | Creative work deserves attribution |

---

## Why Blue Oak?

- **Actually readable** — plain English, not 1990s legalese
- **Patent protection** — implicit grant + defensive termination
- **OSI-approved** — recognized by Open Source Initiative
- **Compatible** — works with everything

It's MIT/ISC but modernized. Same freedoms, better text.

---

## Why FSL for Products?

FSL lets you use/modify/learn immediately, but restricts **production use** for 2 years. After that, it becomes Apache-2.0 or MIT forever.

**Why?:** Prevent AWS-style "host and compete" during early development, then maximize freedom once stable.

**No Rug Pull** — I will never switch to this from an existing license, projects using this, will start with this.

---

## Why also EUPL?

EUPL gives me that AGPL style protection. It will be used for things that I want to be OSS from the get go, but be protected from the SaaS issue.

This is also my choice if I don't plan to permissively relicense.

Also a bonus of it coming in 22 different languages.

---

## Why MPL-2.0 → Relicense?

For projects where I want shared evolution initially. I am not a fan of GPL, so MPL is my preferred for a weaker copyleft.

**Intent stated upfront:** May relicense to Blue Oak once stable. Contributors agree to this by contributing.

No surprises. No bait-and-switch.

This is an alternative approach to the FSL one above, instread of Source Available to Open Source, its Open Source Copyleft to Open Source Permissive.

---

## Why Not Just MIT?

MIT and ISC are fine, but Blue Oak feels better,  it handles patents (MIT is silent), and is written for humans.

I am trying to use what I feel works best for me, not just use a license because its popular.

---

## What You Can Do

| License | Use | Modify | Distribute | Commercial | Attribution |
|---------|-----|--------|------------|------------|-------------|
| **Blue Oak** | ✅ | ✅ | ✅ | ✅ | Small notice |
| **FSL** | ✅* | ✅ | ✅ | ⚠️* | Yes |
| **MPL-2.0** | ✅ | ✅* | ✅ | ✅ | Yes |
| **EUPL-1.2** | ✅ | ✅* | ✅ | ✅ | Yes |
| **0BSD** | ✅ | ✅ | ✅ | ✅ | ❌ No |
| **CC-BY-SA** | ✅ | ✅ | ✅* | ✅ | Credit + share alike |

\* FSL: Non-production OK immediately; production restricted for 2 years  
\* MPL-2.0: Changes to my files must be shared  
\* EUPL-1.2: All changes must be shared back. Think AGPL 3.0
\* CC-BY-SA: Derivative content must be CC-BY-SA

---

## Contributing

By contributing, you agree to license your work under the project's current license. For MPL-2.0 projects, you agree it may be relicensed to a permissive license later.

Questions? Open an issue.

---

*This file was partially created with AI, then modified and cleaned up manually*

*Last updated: 2026-02-18*
