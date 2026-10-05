## Project Context & Scenario

For this controlled red-team simulation, I used **BlackEye**, a publicly available phishing simulation tool, to demonstrate how easily an attacker can create a convincing imitation of a legitimate website and use social engineering to encourage an unsuspecting user to interact with it.

The simulation demonstrated the types of information that could potentially become visible to an attacker following user interaction, including **submitted credentials and connection/location-related information**.

To keep the project ethical and suitable for public viewing, I have **not included the actual phishing email, real credentials, or other sensitive/incriminating information** in this repository. Screenshots containing sensitive information have been appropriately redacted.

### Simulated Business Scenario

With permission from my friend **Francis Steyn**, I created a fictional small online business called **WWWebFlux** specifically for this simulation.

WWWebFlux does not represent a real operating business. It was created solely to demonstrate how a phishing attack could affect a small online business and its users.

The scenario was designed to answer questions such as:

* What could an attacker potentially see after a victim interacts with a phishing page?
* What information could potentially be exposed?
* How could a phishing incident affect a small online business?
* What should the business do immediately after discovering the incident?
* How can the business investigate what happened?
* How can compromised accounts and sessions be secured?
* What security controls could reduce the likelihood of the attack succeeding again?

### Business Impact

The simulation demonstrates that a phishing attack can have consequences beyond the individual user.

For a small online business, compromised credentials could potentially lead to:

* Unauthorized account access
* Exposure of business information
* Compromise of customer accounts
* Unauthorized changes to business systems
* Reputational damage
* Loss of customer trust
* Further attacks using compromised accounts

The purpose of this simulation was therefore to examine the attack from both the **attacker and business-defender perspectives**.

---

## Incident Response Playbook

As part of the project, I developed an **Incident Response Playbook** designed around the simulated phishing incident.

The playbook provides a practical response process that a small online business could follow if a similar incident occurred.

The response covers:

1. **Detection** — Identifying suspicious emails, links, authentication activity and other indicators.
2. **Identification** — Determining which users, accounts and systems may have been affected.
3. **Containment** — Resetting compromised credentials, revoking sessions and blocking malicious indicators.
4. **Investigation** — Reviewing available email, authentication and system logs to understand what occurred.
5. **Eradication** — Removing malicious artifacts and addressing the underlying security weaknesses.
6. **Recovery** — Restoring secure access and monitoring affected accounts.
7. **Lessons Learned** — Improving security controls and user awareness to reduce the likelihood of recurrence.

The goal of the playbook is not simply to respond after an attack, but to help a business understand **what happened, what may have been affected, how to contain the damage, and how to improve its security posture afterwards**.

---

## Ethical & Safety Considerations

This project was conducted as an **authorized security simulation** for educational purposes.

* The phishing simulation was performed against controlled/test targets.
* Permission was obtained from the owner of the simulated business scenario.
* WWWebFlux is a fictional business created specifically for this project.
* Real third-party accounts were not targeted.
* Sensitive credentials and identifying information have been redacted.
* The phishing email used during the simulation is intentionally not included in this public repository.
* The project focuses on understanding the attack lifecycle and developing appropriate defensive and incident-response measures.

