# ◊ FallClinicOnboard

**Sovereign UK healthcare clinic patient registration.** NHS number, medical history, allergies, consent (GDPR Art.9 / Gillick / MCA 2005), safeguarding. Single HTML file. Data never leaves the device. Prime 929.

Part of the **clinic bundle**: [fallclinic](https://github.com/sjgant80-hub/fallclinic) (919) · **fallcliniconboard** (929) · [fallclinicpaper](https://github.com/sjgant80-hub/fallclinicpaper) (937) · [fallclinicpractice](https://github.com/sjgant80-hub/fallclinicpractice) (941).

Live: <https://sjgant80-hub.github.io/fallcliniconboard/>

---

## For the end user

Register patients with a 6-step wizard capturing demographics, medical history, allergies, consent, safeguarding, and documents. Designed for UK healthcare clinics operating under CQC registration.

### Wizard steps

| Step | What it captures |
|---|---|
| Demographics | Name, DOB, sex, NHS number, address, NOK, interpreter needs, GP |
| Medical History | Conditions, surgeries, family history, smoking/alcohol/substance, disabilities |
| Allergies & Meds | Structured allergy register (allergen/reaction/severity), current medications |
| Consent & GDPR | Art.9 special category, treatment consent, Gillick, MCA 2005, LPA |
| Safeguarding | 10 categories inc. FGM, Prevent, MARAC, child/adult protection plans |
| Documents | Upload with SHA-256 hashing |

### Key rules

- **GDPR Art.9**: health data is special category — Art.9(2)(h) healthcare basis
- **Caldicott Principles**: 8 principles governing patient data handling
- **MCA 2005**: capacity assessment — decision-specific, 2-stage test
- **Gillick**: under-16 competence assessment
- **Safeguarding**: Children Act 1989/2004, Care Act 2014 s.42, mandatory FGM reporting

---

## Licence

MIT · Simon Gant · prime 929 · ◊·κ=1.
