# Musa Scott — Cybersecurity Portfolio

This repository powers [ms16001.github.io](https://ms16001.github.io), a personal professional portfolio focused on technical security work and operational experience.

## Website

- **Home:** career summary, selected projects, professional experience, education, and certifications.
- **TCP security case study:** four original SEED Labs experiments, documented with packet-capture evidence and defensive analysis.
- **Technology:** plain semantic HTML, CSS, and JavaScript, deployed through GitHub Pages.

## Technical case study

The featured project covers TCP SYN flooding, SYN cookie behavior, manual and automated TCP reset spoofing, session hijacking, and reverse-shell behavior in an authorized isolated Docker environment.

Screenshots in `assets/` are original lab evidence. New, individually annotated replacements will be added once their image files have been uploaded. Do not confuse reconstructed illustrations with authentic packet captures.

## Local preview

Open `index.html` in a browser, or run a local static server from the repository root:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

This repository is named `ms16001.github.io`. GitHub Pages should deploy from the `main` branch, repository root.

## Lab attribution

The SEED Labs experiments follow the [SEED Labs TCP Attacks guide](https://seedsecuritylabs.org/Labs_20.04/Files/TCP_Attacks/TCP_Attacks.pdf). All tests were performed in a controlled educational environment. The session-hijacking submission had a documented missing packet-capture frame, and the portfolio does not claim otherwise.
