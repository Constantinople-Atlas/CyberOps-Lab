# Week 1 — Day 1 — Lesson 1
# Understanding Cybersecurity

**Learning path:** Beginner Cybersecurity Curriculum  
**Portfolio:** CyberOps-Lab  
**Suggested repository folder:** `01-Cybersecurity-Fundamentals`  
**Lesson status:** Completed  
**Document purpose:** A detailed revision guide and durable record of the concepts, examples, assessment, and practical exercise covered in this lesson.

---

## How to use this document

This document is designed to help you remember the lesson long after completing it.

1. Read one section at a time rather than trying to memorize everything at once.
2. Pay attention to the **meaning**, **why it matters**, and **example** for each concept.
3. Try to explain each concept aloud in your own words before reading the explanation again.
4. Use the quick-recall tables and memory aids for revision.
5. Answer the review questions without looking at the answers. Then check your work.
6. Revisit the practical scenario and explain why each answer is correct.

A useful learning habit is to return to this document after a day, after a week, and again after a few weeks. Short revision sessions help you retrieve information from memory.

---

# 1. What is cybersecurity?

## 1.1 Definition

**Cybersecurity** is the practice of protecting computers, networks, applications, and digital information from unauthorized access, misuse, damage, disruption, or theft.

In simple terms, cybersecurity is about keeping digital systems and the information they contain safe.

Think of a company office. It may have:
- Doors and locks to control who enters.
- Staff identification cards to confirm identity.
- Cabinets to protect confidential documents.
- Security staff to monitor unusual activity.

A digital environment needs similar protection. Instead of only protecting rooms and paper documents, cybersecurity helps protect computers, accounts, networks, applications, and electronic information.

## 1.2 Why cybersecurity matters

People and organizations depend on digital systems for activities such as:
- Communicating through email and messaging platforms.
- Storing employee and customer records.
- Managing payments and business operations.
- Delivering services through websites and applications.
- Sharing and processing important information.

If these systems are not properly protected, information may be exposed, changed, stolen, or made unavailable. Cybersecurity helps reduce these risks and supports trust in digital services.

## 1.3 What are we protecting?

| Term | Meaning | Example |
|---|---|---|
| Computer | An electronic device that processes and stores information | Desktop, laptop, server |
| Network | Connected devices that communicate and share resources | A company's office network |
| Application | Software designed to perform a task | Email app, payroll system |
| Digital information | Data stored or processed electronically | Employee records, documents, account details |

**Remember:** Cybersecurity does not protect only computers. It protects the wider digital environment and the information moving through it.

---

# 2. Assets: what needs protection?

An **asset** is anything valuable to a person or organization that needs protection.

Cybersecurity assets can include:
- Computers, laptops, and servers.
- Networks and network equipment.
- User accounts and login credentials.
- Applications and business systems.
- Customer information.
- Employee information.
- Financial records and business documents.

### Example

BluePeak Technologies stores employee information on its computer systems.

The employee information is an asset because:
1. The company needs it for legitimate business purposes.
2. It may contain private or confidential details.
3. Unauthorized access, exposure, or alteration could harm employees or the company.

The computers and systems storing the information are also assets.

**Memory aid:** An asset is the thing you want to protect.

---

# 3. The CIA Triad: three core security goals

The **CIA Triad** is a foundational information-security model. Its three parts describe important goals for protecting information.

CIA stands for:

- **C — Confidentiality**
- **I — Integrity**
- **A — Availability**

## 3.1 Confidentiality

**Meaning:** Confidentiality means keeping information private and preventing people who are not authorized from seeing it.

**Why it matters:** Some information should only be available to approved people. If private information is exposed to someone who has no permission to see it, confidentiality has been compromised.

**Example:** An employee's personal information should only be accessible to staff who have a legitimate reason and permission to use it.

**Memory cue:** Confidentiality = keeping information secret or private from unauthorized people.

## 3.2 Integrity

**Meaning:** Integrity means keeping information accurate, complete, and trustworthy. It helps ensure information is not changed improperly.

**Why it matters:** People and organizations make decisions based on stored information. If records are changed without permission or become inaccurate, decisions may be wrong.

**Example:** If an employee's official salary record is changed without authorization, the integrity of that record has been affected.

**Memory cue:** Integrity = information remains correct and trustworthy.

## 3.3 Availability

**Meaning:** Availability means ensuring that authorized users can access systems and information when they need them.

**Why it matters:** Information can be private and accurate but still be useless if legitimate users cannot access it when required.

**Example:** Employees need access to the company's payroll system when processing salaries. If the system is unavailable, the business task may be delayed.

**Memory cue:** Availability = systems and information are accessible when needed by authorized users.

## 3.4 Compare the three

| Principle | Main question | Main concern |
|---|---|---|
| Confidentiality | Who can see the information? | Unauthorized disclosure |
| Integrity | Is the information correct and trustworthy? | Unauthorized or improper changes |
| Availability | Can authorized users access it when needed? | Disruption or loss of access |

### Quick memory aid

- **Confidentiality:** Keep it private.
- **Integrity:** Keep it correct.
- **Availability:** Keep it accessible.

### Applying the CIA Triad

Consider these examples:

1. Someone without permission views confidential employee records.  
   **Principle affected:** Confidentiality.

2. A record is changed without authorization and now contains incorrect information.  
   **Principle affected:** Integrity.

3. A system outage prevents authorized employees from using a business application.  
   **Principle affected:** Availability.

A single incident can affect more than one principle. For example, an incident could expose information and also disrupt access to a system.

---

# 4. Threats, vulnerabilities, risks, and threat actors

These terms are related, but they do not mean the same thing. Being able to distinguish them is important when describing a security problem.

## 4.1 Vulnerability

A **vulnerability** is a weakness in a system, application, process, or security arrangement that could be misused or exploited.

Examples:
- A system that has not received important security updates.
- A weak password policy.
- Sensitive information that is accessible to people who do not need it.
- Employees who have not been taught how to recognize common deceptive messages.

**Memory cue:** Vulnerability = the weakness.

## 4.2 Threat

A **threat** is a potential source of harm or an event that could negatively affect an asset.

Examples:
- A malicious email campaign.
- Malware.
- An unauthorized person attempting to access an account.
- A system failure that could interrupt a service.

A threat does not mean harm has definitely happened. It means there is a possibility of something harmful occurring.

**Memory cue:** Threat = the potential danger.

## 4.3 Threat actor

A **threat actor** is a person or group that carries out, supports, or attempts an activity that could harm a system or its information.

In a fictional phishing scenario, a person pretending to be an organization's IT department in order to obtain employee login details is the threat actor.

**Memory cue:** Threat actor = who is behind the attempted harmful activity.

## 4.4 Risk

**Risk** is the possibility of harm or loss when a threat could take advantage of a vulnerability and affect an asset.

A simple way to think about it:

- There is an **asset** worth protecting.
- A **vulnerability** is a weakness affecting that asset.
- A **threat** could take advantage of the weakness.
- The resulting possibility of harm is the **risk**.

### Simple example

Imagine a company account that is protected by a weak password.

- **Asset:** The company account and the information it can access.
- **Vulnerability:** The weak password.
- **Threat:** Someone attempting unauthorized access.
- **Risk:** The account or its information could be accessed without permission.

This is a learning example, not a complete method for calculating risk. In professional work, risk assessments consider factors such as likelihood, impact, existing controls, and the value of the affected asset.

## 4.5 Compare the terms

| Term | The question it answers | Short meaning |
|---|---|---|
| Asset | What are we protecting? | Something valuable |
| Vulnerability | What weakness exists? | A weakness |
| Threat | What could cause harm? | Potential danger |
| Threat actor | Who is attempting the harmful activity? | Person or group |
| Risk | What could happen because of the threat and weakness? | Possibility of harm |

**Important distinction:** A threat is not the same as a vulnerability. A threat is a potential source of harm; a vulnerability is a weakness that may make harm more likely or possible.

---

# 5. Common cybersecurity threats and deceptive techniques

## 5.1 Malware

**Malware** means malicious software: software designed to perform harmful or unauthorized actions.

The term covers different kinds of harmful software. The key point for this lesson is that malware is software, not simply a person or a suspicious message.

## 5.2 Phishing

**Phishing** is a deceptive attempt to trick someone into revealing sensitive information, clicking an unsafe link, opening an unsafe attachment, or taking another action that could compromise security.

Phishing commonly uses messages that pretend to come from a trusted organization or person.

Example: An email claims to come from a company's IT department and asks an employee to provide their password.

Phishing is a technique. The email is the message or delivery method used in the scenario.

## 5.3 Ransomware

**Ransomware** is a type of malware that can make data or systems inaccessible, commonly by encrypting files, and demands payment in exchange for a claimed way to restore access.

For this lesson, remember:
- Ransomware is a type of malware.
- It can affect the availability of information.
- Depending on the incident, it may also affect confidentiality or integrity.

## 5.4 Social engineering

**Social engineering** is the use of deception or psychological manipulation to persuade people to reveal information or take actions that weaken security.

Examples include:
- Pretending to be a trusted employee.
- Claiming to be from IT support.
- Creating false urgency to pressure someone into acting quickly.

Phishing is one type of social-engineering technique. Social engineering is the broader concept.

### Compare the terms

| Term | What it means |
|---|---|
| Malware | Harmful software |
| Phishing | Deceptive technique often delivered through messages |
| Ransomware | A type of malware that can deny access and demand payment |
| Social engineering | Manipulating people into unsafe security decisions |

---

# 6. Attack vectors

An **attack vector** is the route, method, or path used in an attempt to compromise a system, account, network, or information.

Examples at a high level:
- A deceptive email.
- A compromised account.
- An exposed service.
- An unsafe attachment.
- A vulnerable application.

### A useful distinction

| Concept | Question | Example in the BluePeak scenario |
|---|---|---|
| Threat actor | Who is attempting the harmful activity? | The person pretending to be IT |
| Attack vector | Through what route or method? | The deceptive email |
| Phishing | What deceptive technique is being used? | The email attempts to trick the employee into revealing login details |
| Vulnerability | What weakness could make success more likely? | An employee may not recognize the deceptive message |
| Asset | What needs protection? | Employee information and the systems storing it |

An attack vector is not necessarily the threat actor. The actor is the “who”; the vector is the “how” or “through what route.”

---

# 7. Information-security principles beyond the CIA Triad

The CIA Triad describes three major security goals. This lesson also introduced three important principles that help organizations manage access and responsibility.

## 7.1 Authentication

**Authentication** is the process of verifying a user's identity.

It answers:

**“Who are you?”**

Example: A user signs in and the system checks the credentials or other approved identity evidence to verify that the user is who they claim to be.

Authentication is about establishing identity. It does not, by itself, decide every action that user is allowed to perform.

## 7.2 Authorization

**Authorization** determines what an authenticated user is permitted to access or do.

It answers:

**“What are you allowed to access or do?”**

Example: An employee may be allowed to view their own work records but not to access confidential records belonging to every other employee.

A person can be authenticated successfully and still not have authorization to access a particular file or system.

## 7.3 Accountability

**Accountability** means that actions can be attributed to the appropriate user or process and reviewed when necessary.

Organizations support accountability through suitable records, such as security logs and audit trails.

Example: If an employee accesses a protected business record, an appropriate system log may record the account involved and the time of access.

Logs must be protected and handled responsibly. A log entry is useful evidence, but it should be interpreted in context rather than automatically treated as proof of a person's intent.

## 7.4 Authentication vs authorization vs accountability

| Principle | Main question | Simple example |
|---|---|---|
| Authentication | Who are you? | Sign-in identity verification |
| Authorization | What may you do? | Permission to view a particular record |
| Accountability | Can actions be traced and reviewed? | Appropriate access logs |

### Memory aid

- **Authentication:** Identify.
- **Authorization:** Permit.
- **Accountability:** Trace and review.

## 7.5 How these relate to the CIA Triad

The CIA Triad and these principles are connected, but they are not interchangeable.

For example:
- Authentication can help protect confidentiality by checking who is signing in.
- Authorization can help protect confidentiality and integrity by limiting what users may access or change.
- Accountability can help organizations investigate activity and review whether access rules are being followed.

**Important correction from the practical exercise:** Authentication is a security mechanism or principle, but it is not one of the three CIA Triad components. In the BluePeak email scenario, confidentiality is the main CIA principle at risk because stolen login details could allow unauthorized access to private employee information.

---

# 8. Recognizing suspicious emails

The BluePeak practical exercise introduced a common workplace security situation: a deceptive email pretending to come from the company's IT department.

Employees should learn to recognize warning signs, sometimes called **phishing indicators**.

## 8.1 Common warning signs

| Warning sign | What to look for |
|---|---|
| Unusual sender address | The sender's address does not match the organization's known official address |
| Urgent or threatening language | The message pressures the reader to act immediately |
| Requests for passwords | The sender asks the employee to disclose a password |
| Unexpected links | The message asks the reader to visit an unfamiliar or unexpected destination |
| Unexpected attachments | The message includes a file the employee was not expecting |
| Unusual spelling or wording | The message contains odd wording, errors, or an unusual tone |

A familiar display name or company logo does not, by itself, prove that an email is genuine.

**One warning sign does not always prove that an email is fraudulent.** Employees should treat suspicious messages cautiously and use their organization's approved process to report and verify them.

## 8.2 Fictional example

**From:** BluePeak IT Support  
**Subject:** URGENT! Your account will be disabled!

**Message:**

> Dear Employee,
>
> Your account will be disabled today. Reply to this email with your username and password immediately to prevent account suspension.
>
> Thank you,  
> IT Support Team

### What makes this message suspicious?

1. **Urgency:** It pressures the employee by threatening account suspension.
2. **Password request:** It asks the employee to disclose a password.
3. **Unverified identity:** The employee should not assume that the sender is genuine just because the message claims to be from IT.

## 8.3 What should an employee do?

A sensible defensive response is:

1. Do not reply with login details.
2. Do not click suspicious links or open unexpected attachments.
3. Report the message using the organization's approved reporting process.
4. Verify the request through a known, official contact method, not by relying on the contact details in the suspicious message.

Employees should follow their organization's actual security procedures. Different workplaces may have different reporting buttons, addresses, or escalation processes.

---

# 9. Practical exercise: BluePeak Technologies

## 9.1 Scenario

A fictional company called **BluePeak Technologies** stores employee information on its computer systems.

An employee receives a deceptive email pretending to come from the company's IT department. The email attempts to trick the employee into revealing their login details.

## 9.2 Questions and reviewed answers

### Question 1: What asset needs protection?

**Answer:** The employee information stored on the company's computer systems.

**Why:** Employee information is valuable and may be private. The systems and accounts used to store and access it are also assets.

### Question 2: What is the threat?

**Answer:** The person attempting to deceive the employee and obtain login details is the threat actor. The phishing attempt is the threat activity.

**Why:** The person is pretending to be IT in order to obtain information that could be used for unauthorized access.

**Terminology note:** A threat actor is the person or group. The threat is the potential harmful activity or source of harm. Keeping these terms distinct makes incident descriptions clearer.

### Question 3: What is the attack vector?

**Answer:** The deceptive email.

**Why:** The email is the route through which the attempt reaches the employee.

### Question 4: Which security principle could be affected?

**Answer:** Confidentiality is the main CIA Triad principle at risk.

**Why:** If login details are obtained and misused, someone may gain unauthorized access to private employee information.

**Related concept:** Authentication is also relevant because the organization needs reliable ways to verify users' identities. However, authentication is not itself one of the CIA Triad components.

### Question 5: Give one recommendation.

**Answer:** Employees should verify suspicious emails and report them to the IT department rather than sharing their login details.

**Why this helps:**
- Verification helps employees avoid trusting an unconfirmed sender.
- Reporting allows the IT or security team to investigate the message.
- Refusing to disclose passwords helps prevent account compromise.

Other suitable defensive controls include:
- Employee awareness training.
- Multi-factor authentication (MFA), which requires an additional verification step during sign-in.
- Email security controls that help detect or filter suspicious messages.

## 9.3 The learner's phishing-indicator check

**Question:** An email claims to be from the company's IT department and says:

> Your account will be suspended unless you send us your password immediately.

**Identify two warning signs.**

**Reviewed answer:**
1. It creates urgency by threatening account suspension.
2. It requests a password.

**Why both matter:** Urgent pressure can make someone act without checking, while a request for a password is a serious warning sign. The employee should not provide the password and should report the message through the approved process.

---

# 10. A simple method for analyzing a security scenario

When presented with a basic security scenario, use this sequence:

1. **Identify the asset:** What information, account, system, or device needs protection?
2. **Identify the threat:** What harmful activity or potential source of harm is involved?
3. **Identify the threat actor:** Who is attempting or causing the harmful activity, if known?
4. **Identify the vulnerability:** What weakness could make the incident possible or more likely?
5. **Identify the attack vector:** Through what route or method is the attempt being made?
6. **Identify the security impact:** Which of confidentiality, integrity, or availability could be affected?
7. **Recommend a control:** What reasonable defensive measure could reduce the risk?

Do not assume every detail is known. If the scenario does not tell you the vulnerability or the actor's identity, say that it is unknown rather than inventing an answer.

---

# 11. Quick-recall revision sheet

Use this section for a fast refresher.

| Concept | Remember it as |
|---|---|
| Cybersecurity | Protecting digital systems and information |
| Asset | What needs protection |
| Confidentiality | Keep information private |
| Integrity | Keep information correct and trustworthy |
| Availability | Keep information and systems accessible to authorized users |
| Vulnerability | A weakness |
| Threat | A potential source of harm |
| Threat actor | Who is behind an attempted harmful activity |
| Risk | The possibility of harm |
| Malware | Malicious software |
| Phishing | Deception intended to trick someone into unsafe action |
| Ransomware | Malware that can deny access and demand payment |
| Social engineering | Manipulating people into weakening security |
| Attack vector | The route or method used in an attempted compromise |
| Authentication | Verify identity — “Who are you?” |
| Authorization | Determine permissions — “What may you do?” |
| Accountability | Make actions traceable and reviewable |

## Three especially useful distinctions

**1. Threat vs vulnerability**
- Threat = potential danger.
- Vulnerability = weakness.

**2. Threat actor vs attack vector**
- Threat actor = who.
- Attack vector = how or through what route.

**3. Authentication vs authorization**
- Authentication = verify identity.
- Authorization = decide permitted access.

---

# 12. Review questions

Try answering these without looking at the earlier sections. The answer key follows the questions.

## Part A — Multiple choice

**1. What is cybersecurity primarily concerned with?**

A. Making computers faster  
B. Protecting digital systems and information  
C. Designing websites  
D. Replacing computer hardware

**2. Which CIA Triad principle protects information from unauthorized viewing?**

A. Availability  
B. Integrity  
C. Confidentiality  
D. Accountability

**3. Which CIA Triad principle focuses on keeping information accurate and trustworthy?**

A. Integrity  
B. Authentication  
C. Availability  
D. Phishing

**4. Which CIA Triad principle ensures authorized users can access systems when needed?**

A. Confidentiality  
B. Availability  
C. Authorization  
D. Social engineering

**5. What is a vulnerability?**

A. A valuable asset  
B. A weakness that could be misused  
C. A verified user  
D. A security report

**6. What is an attack vector?**

A. The route or method used in an attempted compromise  
B. The value of a computer  
C. A person's job title  
D. A type of audit report

**7. What does authentication verify?**

A. What a user may access  
B. A user's identity  
C. Whether a computer is available  
D. Whether a file is accurate

**8. What does authorization determine?**

A. A user's permitted access and actions  
B. The identity of every threat actor  
C. Whether an email is urgent  
D. The age of a computer

**9. Which term describes malicious software?**

A. Availability  
B. Malware  
C. Authorization  
D. Accountability

**10. Which is a warning sign of a possible phishing email?**

A. A routine message from a verified internal system  
B. A request to disclose a password under urgent pressure  
C. A normal calendar reminder  
D. A message with no request or unusual content

## Part B — Short answer

**11. Explain the difference between a threat and a vulnerability.**

**12. Explain the difference between authentication and authorization.**

**13. What is an attack vector? Give one simple example.**

**14. Explain the difference between a threat actor and an attack vector.**

**15. Name the three CIA Triad principles and explain each briefly.**

## Answer key

1. B — Protecting digital systems and information.
2. C — Confidentiality.
3. A — Integrity.
4. B — Availability.
5. B — A weakness that could be misused.
6. A — The route or method used in an attempted compromise.
7. B — A user's identity.
8. A — A user's permitted access and actions.
9. B — Malware.
10. B — A request to disclose a password under urgent pressure.

**11.** A threat is a potential source of harm; a vulnerability is a weakness that could be misused.

**12.** Authentication verifies who a user is. Authorization determines what that verified user is permitted to access or do.

**13.** An attack vector is the route or method used in an attempted compromise. A deceptive email is one example.

**14.** A threat actor is the person or group attempting the harmful activity. An attack vector is the route or method used.

**15.**
- Confidentiality: keeping information private from unauthorized people.
- Integrity: keeping information accurate and trustworthy.
- Availability: ensuring authorized users can access systems and information when needed.

---

# 13. Lesson completion record

The following topics were covered and reviewed in this lesson:

- [x] Meaning and purpose of cybersecurity
- [x] Computers, networks, applications, and digital information
- [x] Assets and why they need protection
- [x] Confidentiality, Integrity, and Availability (CIA Triad)
- [x] Threats, vulnerabilities, risks, and threat actors
- [x] Malware, phishing, ransomware, and social engineering
- [x] Attack vectors
- [x] Authentication, authorization, and accountability
- [x] Warning signs of suspicious emails
- [x] Defensive response to a suspicious email
- [x] BluePeak Technologies practical scenario
- [x] Knowledge assessment and practical exercise

**Status:** Completed.

## Personal revision notes

Use this space to add your own explanations, examples, or questions when revising.

- A concept I can explain confidently:
- A concept I want to revise again:
- A real-world example I noticed:
- A question to ask in the next lesson:

---

# 14. Glossary

| Term | Definition |
|---|---|
| Application | Software designed to perform a task |
| Asset | Something valuable that needs protection |
| Attack vector | The route or method used in an attempted compromise |
| Authentication | Verifying a user's identity |
| Authorization | Determining what an authenticated user is permitted to access or do |
| Availability | Ensuring authorized access to systems and information when needed |
| Accountability | Making actions attributable, traceable, and reviewable |
| Confidentiality | Preventing unauthorized people from viewing information |
| Cybersecurity | Protecting digital systems and information from unauthorized access, misuse, damage, disruption, or theft |
| Digital information | Data stored or processed electronically |
| Integrity | Maintaining the accuracy and trustworthiness of information |
| Malware | Malicious software |
| Phishing | Deception intended to trick someone into revealing information or taking an unsafe action |
| Ransomware | Malware that can deny access to data or systems and demand payment |
| Risk | The possibility of harm or loss |
| Social engineering | Manipulating people into revealing information or taking unsafe actions |
| Threat | A potential source of harm |
| Threat actor | A person or group that carries out or attempts harmful activity |
| Vulnerability | A weakness that could be misused |

---

## Final takeaway

Cybersecurity begins with understanding **what must be protected, what could harm it, which weaknesses may be involved, and what controls can reduce the risk**.

When analyzing a situation, remember this sequence:

**Asset → Threat → Vulnerability → Risk → Attack vector → Security impact → Defensive recommendation**

This sequence is a study aid, not a mandatory order for every professional investigation. Real incidents may require analysts to revisit earlier assumptions as new evidence becomes available.

**End of Week 1 — Day 1 — Lesson 1.**
