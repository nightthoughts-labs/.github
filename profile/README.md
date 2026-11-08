# Night Thoughts Labs

**Applied AI, tested for real.**

Night Thoughts Labs turns the experiments behind [nightthoughts.me](https://nightthoughts.me) into private, production-minded tools. Every product starts as a measured experiment: real data, held-out evaluation, documented failure modes, and a human in the loop where it matters.

## Products

### Dyolis

**Clinical AI, designed for medical control.**

Dyolis is a clinical AI platform designed to keep clinicians in control. It combines two independent AI readings, built-in safeguards and a mandatory clinician sign-off, and is designed to run entirely on the hospital's own infrastructure.

- **Clinicians in command.** Every result is a draft until a clinician reviews and signs it. When the two AI readings disagree, the disagreement is shown to the clinician.
- **Safeguards by design.** An intake check declines cases outside the supported scope; a second model from a different family reviews the first model's draft.
- **Designed for data sovereignty.** Designed to be installed on the hospital's own servers. In this configuration, patient data is processed on site and is not sent to external AI services.
- **Traceable.** Every step is logged: which case, which model and version, which reviewer, which decision.

First use: chest X-ray reporting. Planned modules cover other examinations (ECG, mammography, ultrasound, MRI, dermatology) and full case records.

*Dyolis is under development. It is not a CE-marked medical device and is not available for clinical use.*

### More coming
New tools graduate here when their experiment proves itself. Follow the [blog](https://nightthoughts.me) to see what is being tested next.

## Licensing and collaboration

Products are private and available under commercial licence. To discuss licensing, a pilot or a research collaboration, reach out on [LinkedIn](https://www.linkedin.com/in/haythemslimi).

## Open work

Published experiments, with code and reproduction steps, live in [hslimi/night-thoughts](https://github.com/hslimi/night-thoughts).
