# ACM Code of Ethics and Professional Conduct[^1]

## Preamble

Computing professionals' actions change the world. To act responsibly, they should reflect upon the wider impacts of their work, consistently supporting the public good. The ACM Code of Ethics and Professional Conduct ("the Code") expresses the conscience of the profession.

The Code is designed to inspire and guide the ethical conduct of all computing professionals, including current and aspiring practitioners, instructors, students, influencers, and anyone who uses computing technology in an impactful way. Additionally, the Code serves as a basis for remediation when violations occur. The Code includes principles formulated as statements of responsibility, based on the understanding that the public good is always the primary consideration. Each principle is supplemented by guidelines, which provide explanations to assist computing professionals in understanding and applying the principle.

Section 1 outlines **fundamental ethical principles that form the basis for the remainder of the Code**. Section 2 **addresses additional, more specific considerations of professional responsibility**. Section 3 **guides individuals who have a leadership role, whether in the workplace or in a volunteer professional capacity**. Commitment to ethical conduct is required of every ACM member, ACM SIG member, ACM award recipient, and ACM SIG award recipient. **Principles involving compliance with the Code** are given in Section 4.

The Code as a whole is concerned with how fundamental ethical principles apply to a computing professional's conduct. The Code is not an algorithm for solving ethical problems; rather it serves as a basis for ethical decision-making. When thinking through a particular issue, a computing professional may find that multiple principles should be taken into account, and that different principles will have different relevance to the issue. Questions related to these kinds of issues can best be answered by thoughtful consideration of the fundamental ethical principles, understanding that the public good is the paramount consideration. The entire computing profession benefits when the ethical decision-making process is accountable to and transparent to all stakeholders. Open discussions about ethical issues promote this accountability and transparency.

---

## I. General Ethics Principles

*A computing professional should...*

### I.I Contribute to society and to human well-being, acknowledging that all people are stakeholders in computing.

This principle, which concerns the quality of life of all people, affirms an obligation of computing professionals, both individually and collectively, to use their skills for the benefit of society, its members, and the environment surrounding them. This obligation includes promoting fundamental human rights and protecting each individual's right to autonomy. An essential aim of computing professionals is to [minimize negative consequences of computing, including threats to health, safety, personal security, and privacy](). When the interests of multiple groups conflict, the needs of those less advantaged should be given increased attention and priority.

Computing professionals should consider whether the results of their efforts will respect diversity, will be used in socially responsible ways, will meet social needs, and will be broadly accessible. They are encouraged to actively contribute to society by engaging in pro bono or volunteer work that benefits the public good.

In addition to a safe social environment, human well-being requires a safe natural environment. Therefore, computing professionals should promote environmental sustainability both locally and globally.

<details>
  <summary>Example: Mitigating Algorithmic Bias in Recruitment AI</summary>
  
  #### The Scenario: 
  
  A tech company builds a machine learning model to automatically screen resumes. They notice the AI is disproportionately rejecting qualified female applicants because it was trained on 10 years of historical hiring data from a male-dominated engineering department.

  #### Ethical Action:

  The data science team actively intervenes to audit and retrain the model. They scrub the biased historical weights and intentionally prioritize fairness metrics over raw optimization. By doing this, they uphold the directive that "when the interests of multiple groups conflict, the needs of those less advantaged should be given increased attention and priority."

</details>

### I.II Avoid Harm.

In this document, "harm" means negative consequences, especially when those consequences are significant and unjust. Examples of harm include unjustified physical or mental injury, unjustified destruction or disclosure of information, and unjustified damage to property, reputation, and the environment. This list is not exhaustive.

Well-intended actions, including those that accomplish assigned duties, may lead to harm. When that harm is unintended, those responsible are obliged to undo or mitigate the harm as much as possible. Avoiding harm begins with careful consideration of potential impacts on all those affected by decisions. When harm is an intentional part of the system, those responsible are obligated to ensure that the harm is ethically justified. In either case, ensure that all harm is minimized.

To minimize the possibility of indirectly or unintentionally harming others, computing professionals should follow generally accepted best practices unless there is a compelling ethical reason to do otherwise. Additionally, the consequences of data aggregation and emergent properties of systems should be carefully analyzed. Those involved with pervasive or infrastructure systems should also consider Principle 3.7.

A computing professional has an additional obligation to report any signs of system risks that might result in harm. If leaders do not act to curtail or mitigate such risks, it may be necessary to "blow the whistle" to reduce potential harm. However, capricious or misguided reporting of risks can itself be harmful. Before reporting risks, a computing professional should carefully assess relevant aspects of the situation.

<details>
  <summary>Example: Stopping the Deployment of an Unsafe Medical System</summary>

  #### The Scenario:

  A data engineer designs a recommendation algorithm to maximize user engagement on a video platform. Within months, internal data reveals an unintended consequence: the algorithm is aggressively pushing highly radicalizing, conspiratorial, or self-harm content to vulnerable teenagers because that content triggers high watch times.

  #### Ethical Action:

  Recognizing this as systemic mental and social harm, the engineering team actively reworks the system. They implement hard guardrails, reduce the algorithmic weight of sensationalized content, and build safe default settings. Section 1.2 explicitly notes that well-intended actions can lead to unintended harm, and engineers are obligated to mitigate those impacts once discovered.

</details>

### I.III Be Honest and Trustworthy

Honesty is an essential component of trustworthiness. A computing professional should be transparent and provide full disclosure of all pertinent system capabilities, limitations, and potential problems to the appropriate parties. Making deliberately false or misleading claims, fabricating or falsifying data, offering or accepting bribes, and other dishonest conduct are violations of the Code.

Computing professionals should be honest about their qualifications, and about any limitations in their competence to complete a task. Computing professionals should be forthright about any circumstances that might lead to either real or perceived conflicts of interest or otherwise tend to undermine the independence of their judgment. Furthermore, commitments should be honored.

Computing professionals should not misrepresent an organization's policies or procedures, and should not speak on behalf of an organization unless authorized to do so.

<details>
  <summary>Example: Declaring a Conflict of Interest in Vendor Selection</summary>

  #### The Scenario:

  An enterprise IT director is tasked with choosing a new cloud storage vendor for their corporation's global data migration. The two finalists are Amazon Web Services (AWS) and a smaller boutique cloud provider. Coincidentally, the IT director's spouse is a majority shareholder and executive at the boutique firm.

  #### Ethical Action:

  Before reviewing any proposals, the director submits a formal conflict of interest disclosure to the company's ethics board and recuses themselves from the final voting panel. By being "forthright about any circumstances that might lead to either real or perceived conflicts of interest," they preserve the integrity of the company's decision-making process.

</details>

### I.IV Be fair and take action not to discriminate

The values of equality, tolerance, respect for others, and justice govern this principle. Fairness requires that even careful decision processes provide some avenue for redress of grievances.

Computing professionals should foster fair participation of all people, including those of underrepresented groups. Prejudicial discrimination on the basis of age, color, disability, ethnicity, family status, gender identity, labor union membership, military status, nationality, race, religion or belief, sex, sexual orientation, or any other inappropriate factor is an explicit violation of the Code. Harassment, including sexual harassment, bullying, and other abuses of power and authority, is a form of discrimination that, amongst other harms, limits fair access to the virtual and physical spaces where such harassment takes place.

The use of information and technology may cause new, or enhance existing, inequities. Technologies and practices should be as inclusive and accessible as possible and computing professionals should take action to avoid creating systems or technologies that disenfranchise or oppress people. Failure to design for inclusiveness and accessibility may constitute unfair discrimination.

<details>
  <summary>Example: Overhauling "Geofencing" Filters in Delivery Apps</summary>

  #### The Scenario:

  A food-delivery startup uses an automated routing algorithm that automatically "geofences" (excludes) certain low-income ZIP codes from their delivery map, labeling them as "low-profit zones." This inadvertently cuts off entire minority communities from using the service.

  #### Ethical Action:

  The data analysts and product managers flag this issue as a systemic bias. They rewrite the logic of the routing algorithm to evaluate delivery safety and distance objectively per merchant, rather than relying on blanket socioeconomic or geographic boundaries that result in prejudicial exclusion.

</details>

### I.V Respect the work required to produce new ideas, inventions, creative works, and computing artifacts

Developing new ideas, inventions, creative works, and computing artifacts creates value for society, and those who expend this effort should expect to gain value from their work. Computing professionals should therefore credit the creators of ideas, inventions, work, and artifacts, and respect copyrights, patents, trade secrets, license agreements, and other methods of protecting authors' works.

Both custom and the law recognize that some exceptions to a creator's control of a work are necessary for the public good. Computing professionals should not unduly oppose reasonable uses of their intellectual works. Efforts to help others by contributing time and energy to projects that help society illustrate a positive aspect of this principle. Such efforts include free and open source software and work put into the public domain. Computing professionals should not claim private ownership of work that they or others have shared as public resources.

<details>
  <summary>Example: Honoring Former Employers' Trade Secrets</summary>

  #### The Scenario:

  A senior backend developer leaves Company A to take a high-paying role at rival Company B. Company B is struggling to scale its database infrastructure—a problem the developer personally solved at Company A by writing a highly specialized, proprietary database-sharding algorithm. Company B's management explicitly hints that the developer should just copy-paste that proprietary code from memory to fix their system quickly.

  #### Ethical Action:

  The developer refuses to replicate or reuse Company A's proprietary code. They recognize that the code is a protected asset owned by their former employer. Instead, the developer uses their generalized expertise to design a brand-new, distinct architecture from scratch for Company B, respecting trade secrets and copyright law.

</details>

### I.VI Respect privacy

The responsibility of respecting privacy applies to computing professionals in a particularly profound way. Technology enables the collection, monitoring, and exchange of personal information quickly, inexpensively, and often without the knowledge of the people affected. Therefore, a computing professional should become conversant in the various definitions and forms of privacy and should understand the rights and responsibilities associated with the collection and use of personal information.

Computing professionals should only use personal information for legitimate ends and without violating the rights of individuals and groups. This requires taking precautions to prevent re-identification of anonymized data or unauthorized data collection, ensuring the accuracy of data, understanding the provenance of the data, and protecting it from unauthorized access and accidental disclosure. Computing professionals should establish transparent policies and procedures that allow individuals to understand what data is being collected and how it is being used, to give informed consent for automatic data collection, and to review, obtain, correct inaccuracies in, and delete their personal data.

Only the minimum amount of personal information necessary should be collected in a system. The retention and disposal periods for that information should be clearly defined, enforced, and communicated to data subjects. Personal information gathered for a specific purpose should not be used for other purposes without the person's consent. Merged data collections can compromise privacy features present in the original collections. Therefore, computing professionals should take special care for privacy when merging data collections.

<details>
  <summary>Example: Enforcing "Data Minimization" in App Development</summary>

  #### The Scenario:

  A development team is building a smartphone flashlight and utility app. The marketing department requests that the app track and collect the user's precise GPS location, contacts list, and call history so they can sell the data to third-party advertisers.

  #### Ethical Action:

  The software engineers refuse to integrate those tracking SDKs. They cite the data minimization rule under Section 1.6, which states that "only the minimum amount of personal information necessary should be collected in a system." Since a flashlight app does not require a user's location or contacts to function, collecting it would be an ethical violation.

</details>

### I.VII Honor confidentiality

Computing professionals are often entrusted with confidential information such as trade secrets, client data, nonpublic business strategies, financial information, research data, pre-publication scholarly articles, and patent applications. Computing professionals should protect confidentiality except in cases where there is evidence of a violation of law, of organizational regulations, or of the Code. In these cases, the nature or contents of that information should not be disclosed except to appropriate authorities. A computing professional should consider thoughtfully whether such disclosures are consistent with the Code.

<details>
  <summary>Example: Breaking Confidentiality for the Public Good (The Exception Clause)</summary>

  #### The Scenario:

  A data engineer at a micro-lending fintech company is working with a highly confidential database mapping user repayment rates. While optimizing the database, they uncover a hidden, hardcoded sub-routine designed to intentionally skim fractions of a cent from low-income borrowers who are late on payments, funneling millions into an off-shore executive account.

  #### Ethical Action:

  While the engineer signed a strict Non-Disclosure Agreement (NDA), Section 1.7 explicitly states that confidentiality should be protected "except in cases where there is evidence of a violation of law, of organizational regulations, or of the Code." Because this routine constitutes illegal fraud and inflicts systemic harm, the engineer compiles the evidence and securely reports it to regulatory financial authorities and the company's internal legal compliance board.


</details>

---

## II. Professional Responsibilities

*A computing professional should...*

### II.I Strive to achieve high quality in both the processes and products of professional work.

Computing professionals should insist on and support high quality work from themselves and from colleagues. The dignity of employers, employees, colleagues, clients, users, and anyone else affected either directly or indirectly by the work should be respected throughout the process. Computing professionals should respect the right of those involved to transparent communication about the project. Professionals should be cognizant of any serious negative consequences affecting any stakeholder that may result from poor quality work and should resist inducements to neglect this responsibility.

<details>
  <summary>Example: Maintaining Transparent Communication with Clients Regarding Project Delays</summary>

  #### The Scenario:

  A development agency is building a custom e-commerce platform for a small business. Three weeks before the launch, the lead architect realizes that a critical third-party payment gateway integration is fundamentally incompatible with the client's legacy database, pushing the timeline back by a month.

  #### Ethical Action:

  Rather than hiding the issue, ghosting the client, or rushing out a brittle, insecure workaround to meet the date, the team schedules an immediate meeting. They transparently explain the technical hurdle, present the viable alternatives, and collaborate on a revised timeline. This honors the stakeholder's "right to transparent communication about the project."

</details>

### II.II Maintain high standards of professional competence, conduct and ethical practice

High quality computing depends on individuals and teams who take personal and group responsibility for acquiring and maintaining professional competence. Professional competence starts with technical knowledge and with awareness of the social context in which their work may be deployed. Professional competence also requires skill in communication, in reflective analysis, and in recognizing and navigating ethical challenges. Upgrading skills should be an ongoing process and might include independent study, attending conferences or seminars, and other informal or formal education. Professional organizations and employers should encourage and facilitate these activities.

<details>
  <summary>Example: Navigating Ethical Dilemmas through Structured Frameworks</summary>

  #### The Scenario:

  A junior developer is asked by a manager to implement a subtle "dark pattern"—a deceptive user interface trick designed to trick users into subscribing to a recurring paid newsletter when they buy a product.

  #### Ethical Action:

  Maintaining high standards of ethical practice means knowing how to handle workplace pressure. Instead of quietly complying or shouting at their manager, the developer uses the ethical decision-making frameworks they studied. They document how the feature violates consumer trust, present a compliant alternative design that still encourages sign-ups, and elevate the discussion professionally. This demonstrates "skill in communication, in reflective analysis, and in recognizing and navigating ethical challenges."

</details>

### II.III Know and respect existing rules pertaining to professional work

"Rules" here include local, regional, national, and international laws and regulations, as well as any policies and procedures of the organizations to which the professional belongs. Computing professionals must abide by these rules unless there is a compelling ethical justification to do otherwise. Rules that are judged unethical should be challenged. A rule may be unethical when it has an inadequate moral basis or causes recognizable harm. A computing professional should consider challenging the rule through existing channels before violating the rule. A computing professional who decides to violate a rule because it is unethical, or for any other reason, must consider potential consequences and accept responsibility for that action.

<details>
  <summary>Example: Overriding a Rule Due to Compelling Ethical Justification</summary>

  #### The Scenario:

  During a severe regional flood, a database administrator for a local municipal government finds that emergency rescue teams cannot access a critical mapping database because of a strict, bureaucratic IT access policy that requires a multi-day sign-off from an offline director. People are actively stranded, and delay could result in loss of life.

  #### Ethical Action:

  Section 2.3 allows exception if there is a "compelling ethical justification"—specifically to prevent severe harm. The administrator temporarily bypasses the standard access control rule to grant the rescue teams immediate read-access to the maps. Afterward, they immediately document their actions, report the bypass to leadership, and accept full responsibility for violating the protocol, successfully prioritizing human life over a rigid administrative rule.

</details>

### II.IV Accept and provide appropriate professional review

High quality professional work in computing depends on professional review at all stages. Whenever appropriate, computing professionals should seek and utilize peer and stakeholder review. Computing professionals should also provide constructive, critical reviews of others' work.

<details>
  <summary>Example: Fostering a Constructive Pull Request (PR) Culture</summary>

  #### The Scenario:

  A senior developer is assigned to review a large Pull Request submitted by a junior engineer. The junior developer used an outdated, inefficient loop structure to sort a database query, which could cause latency issues in production.

  #### Ethical Action:

  Instead of leaving a dismissive comment like "This is completely wrong, rewrite it," or silently fixing it themselves to save time, the senior developer provides a constructive, educational review. They point out the bottleneck, link to the team's modern design patterns, and suggest a more optimal built-in function. They fulfill their responsibility to provide constructive, critical reviews of others' work while maintaining professional respect.

</details>

### II.V Give comprehensive and thorough evaluations of computer systems and their impacts, including analysis of possible risks

Computing professionals are in a position of trust, and therefore have a special responsibility to provide objective, credible evaluations and testimony to employers, employees, clients, users, and the public. Computing professionals should strive to be perceptive, thorough, and objective when evaluating, recommending, and presenting system descriptions and alternatives. Extraordinary care should be taken to identify and mitigate potential risks in machine learning systems. A system for which future risks cannot be reliably predicted requires frequent reassessment of risk as the system evolves in use, or it should not be deployed. Any issues that might result in major risk must be reported to appropriate parties.

<details>
  <summary>Example: Flagging Predictable Biases in AI-Driven Credit Scoring</summary>

  #### The Scenario:

  Flagging Predictable Biases in AI-Driven Credit Scoring

  #### Ethical Action:

  Instead of rubber-stamping the vendor's impressive accuracy metrics to please executives, the data scientists deliver a comprehensive, objective evaluation. They explicitly document the systemic risk, map out the potential legal and societal impacts on marginalized applicants, and state that the system is unsafe for deployment without a total overhaul of its training constraints.

</details>

### II.VI Perform work only in areas of competence

A computing professional is responsible for evaluating potential work assignments. This includes evaluating the work's feasibility and advisability, and making a judgment about whether the work assignment is within the professional's areas of competence. If at any time before or during the work assignment the professional identifies a lack of a necessary expertise, they must disclose this to the employer or client. The client or employer may decide to pursue the assignment with the professional after additional time to acquire the necessary competencies, to pursue the assignment with someone else who has the required expertise, or to forgo the assignment. A computing professional's ethical judgment should be the final guide in deciding whether to work on the assignment.

<details>
  <summary>Example: Turning Down an Unfeasible or Ill-Advised Project</summary>

  #### The Scenario:

  An AI startup approaches a machine learning engineer to build a predictive model that claims it can determine whether a criminal defendant will reoffend based entirely on a 10-second video of their face.

  #### Ethical Action:

  Part of Section 2.6 includes evaluating a project's feasibility and advisability. The engineer knows from scientific literature that "physiognomy" (predicting character from facial features) is pseudoscientific, highly biased, and technically unfeasible. The engineer uses their ethical judgment as the final guide and formally declines the assignment, explaining to the client that the goal cannot be achieved competently or scientifically.


</details>

### II.VII Foster public awareness and understanding of computing, related technologies, and their consequences

As appropriate to the context and one's abilities, computing professionals should share technical knowledge with the public, foster awareness of computing, and encourage understanding of computing. These communications with the public should be clear, respectful, and welcoming. Important issues include the impacts of computer systems, their limitations, their vulnerabilities, and the opportunities that they present. Additionally, a computing professional should respectfully address inaccurate or misleading information related to computing.

<details>
  <summary>Example: Conducting Public Cybersecurity Awareness Workshops</summary>

  #### The Scenario:

  A senior systems administrator notices that senior citizens in their local community are frequently falling victim to sophisticated ransomware and phishing scams because they don't understand basic web vulnerabilities.

  #### Ethical Action:

  The administrator volunteers at a local public library to host a monthly "Digital Safety" workshop. They teach attendees how to identify suspicious URLs, explain the importance of multi-factor authentication (MFA), and demystify how data tracking works. They ensure their communication is welcoming and free of elitist tech jargon, honoring the directive to share technical knowledge and encourage understanding.

</details>

### II.VIII Access computing and communication resources only when authorized or when compelled by the public good

Individuals and organizations have the right to restrict access to their systems and data so long as the restrictions are consistent with other principles in the Code. Consequently, computing professionals should not access another's computer system, software, or data without a reasonable belief that such an action would be authorized or a compelling belief that it is consistent with the public good. A system being publicly accessible is not sufficient grounds on its own to imply authorization. Under exceptional circumstances a computing professional may use unauthorized access to disrupt or inhibit the functioning of malicious systems; extraordinary precautions must be taken in these instances to avoid harm to others.

<details>
  <summary>Example: Refusing to Snoop on an Ex-Partner’s Account</summary>

  #### The Scenario:

  A database engineer works at a major cellular network provider. They have high-level admin credentials that technically allow them to look up the call logs, text history, and real-time GPS locations of any phone number on the network. Out of personal curiosity or a messy breakup, they consider looking up their ex-partner's data.

  #### Ethical Action:

  The engineer refuses to run the query. Even though they possess the physical keys (the admin credentials) and no one is actively watching over their shoulder, they recognize they lack explicit authorization for that specific lookup. Accessing private data for personal reasons is a direct breach of professional boundaries.

</details>

### II.IX Design and implement systems that are robustly and usably secure

Breaches of computer security cause harm. Robust security should be a primary consideration when designing and implementing systems. Computing professionals should perform due diligence to ensure the system functions as intended, and take appropriate action to secure resources against accidental and intentional misuse, modification, and denial of service. As threats can arise and change after a system is deployed, computing professionals should integrate mitigation techniques and policies, such as monitoring, patching, and vulnerability reporting. Computing professionals should also take steps to ensure parties affected by data breaches are notified in a timely and clear manner, providing appropriate guidance and remediation.

To ensure the system achieves its intended purpose, security features should be designed to be as intuitive and easy to use as possible. Computing professionals should discourage security precautions that are too confusing, are situationally inappropriate, or otherwise inhibit legitimate use.

In cases where misuse or harm are predictable or unavoidable, the best option may be to not implement the system.

<details>
  <summary>Example: Striking the Right Balance with Usable Security (MFA)</summary>

  #### The Scenario:

  A product team at an enterprise HR company wants to secure employee portal logins. The security team initially proposes a rule requiring users to type a 20-character password, change it every 30 days, and solve three complex CAPTCHAs every time they log in.

  #### Ethical Action:

  The UX and software engineers push back, pointing out that this excessive barrier will cause users to write passwords on sticky notes attached to their monitors—actually lowering real-world security. Instead, they implement a usable security model: a standard, strong password paired with an intuitive, one-tap push notification via a mobile authenticator app. They fulfill the directive to avoid precautions that are "too confusing, are situationally inappropriate, or otherwise inhibit legitimate use."

</details>

---

## III. Professional Leadership Principles

Leadership may either be a formal designation or arise informally from influence over others. In this section, "leader" means any member of an organization or group who has influence, educational responsibilities, or managerial responsibilities. While these principles apply to all computing professionals, leaders bear a heightened responsibility to uphold and promote them, both within and through their organizations.

*A computing professional, especially one acting as a leader, should...*

### III.I Ensure that the public good is the central concern during all professional computing work

People—including users, customers, colleagues, and others affected directly or indirectly—should always be the central concern in computing. The public good should always be an explicit consideration when evaluating tasks associated with research, requirements analysis, design, implementation, testing, validation, deployment, maintenance, retirement, and disposal. Computing professionals should keep this focus no matter which methodologies or techniques they use in their practice.

<details>
  <summary>Example: Prioritizing Safe Data Disposal Over Cost-Cutting</summary>

  #### The Scenario:

  A chief technology officer (CTO) is overseeing the migration of an aging municipal database system to a modern cloud setup. The old on-premise magnetic hard drives contain decades of unencrypted social security numbers, tax forms, and medical records. A budget constraint pressures the CTO to simply throw the old server hardware into a standard electronic waste recycling bin to save money.

  #### Ethical Leadership Action:

  The CTO rejects the shortcut. They point out that proper tech lifecycle stewardship extends to the disposal phase. They allocate a portion of the emergency budget to hire a certified data-destruction firm to physically shred the drives and degauss the hardware, preventing a catastrophic post-retirement data leak that would harm the local community.

</details>

### III.II Articulate, encourage acceptance of, and evaluate fulfillment of social responsibilities by members of the organization or group

Technical organizations and groups affect broader society, and their leaders should accept the associated responsibilities. Organizations—through procedures and attitudes oriented toward quality, transparency, and the welfare of society—reduce harm to the public and raise awareness of the influence of technology in our lives. Therefore, leaders should encourage full participation of computing professionals in meeting relevant social responsibilities and discourage tendencies to do otherwise.

<details>
  <summary>Example: Rewarding Developers Who Flag Quality and Security Flaws</summary>

  #### The Scenario:

  A QA director works at a fast-paced startup where an unstated "crunch culture" pressures employees to look the other way when minor security bugs appear, just to avoid delaying product launches.

  #### Ethical Leadership Action:

  The director steps in to explicitly shift the group's attitude toward quality and transparency. They introduce a monthly "Spotlight Award" that publicly commends and financially rewards engineers who flag critical system risks—even when those flags delay a release. By shifting corporate incentives, the leader ensures the team is encouraged to reduce harm to the public.

</details>

### III.III Manage personnel and resources to enhance the quality of working life

Leaders should ensure that they enhance, not degrade, the quality of working life. Leaders should consider the personal and professional development, accessibility requirements, physical safety, psychological well-being, and human dignity of all workers. Appropriate human-computer ergonomic standards should be used in the workplace.

<details>
  <summary>Example: Defending a Employee's Human Dignity Against Client Abuse</summary>

  #### The Scenario:

  A software consulting firm is building a custom data pipeline for a high-profile, demanding corporate client. During a technical synchronization meeting, the client's representative publicly berates, insults, and humiliates a mid-level data engineer for a minor configuration delay.

  #### Ethical Leadership Action:

  The consulting firm's director steps in immediately. They halt the meeting and later formally inform the client that abusive behavior toward their engineers will not be tolerated. The director reassigns a senior manager to interface with that specific client representative to shield the engineer from further hostility. By taking a stand, the leader fulfills the mandate to respect and defend the human dignity of all workers.

</details>

### III.IV Articulate, apply, and support policies and processes that reflect the principles of the Code

Leaders should pursue clearly defined organizational policies that are consistent with the Code and effectively communicate them to relevant stakeholders. In addition, leaders should encourage and reward compliance with those policies, and take appropriate action when policies are violated. Designing or implementing processes that deliberately or negligently violate, or tend to enable the violation of, the Code's principles is ethically unacceptable.

<details>
  <summary>Example: Structuring Financial Rewards for Finding Critical Safety Vulnerabilities</summary>

  #### The Scenario:

  An engineering director wants to ensure their cybersecurity and development teams actively prioritize public safety over rushed feature delivery, but the existing corporate bonus structures only reward speed and output volume.

  #### Ethical Leadership Action:

  To support and reward compliance with the Code, the director completely overhauls the engineering department's quarterly bonus structure. They introduce a "Security and Integrity Metric" where teams are financially rewarded for proactively finding, reporting, and patching severe systemic vulnerabilities before they ever hit production.

</details>

### III.V Create opportunities for members of the organization or group to grow as professionals

Educational opportunities are essential for all organization and group members. Leaders should ensure that opportunities are available to computing professionals to help them improve their knowledge and skills in professionalism, in the practice of ethics, and in their technical specialties. These opportunities should include experiences that familiarize computing professionals with the consequences and limitations of particular types of systems. Computing professionals should be fully aware of the dangers of oversimplified approaches, the improbability of anticipating every possible operating condition, the inevitability of software errors, the interactions of systems and their contexts, and other issues related to the complexity of their profession—and thus be confident in taking on responsibilities for the work that they do.

<details>
  <summary>Example: Sponsoring Certifications and Open Research Sabbaticals</summary>

  #### The Scenario:

  An infrastructure manager at a cloud hosting provider notices that a senior system administrator is burning out on routine maintenance tickets, leaving them no time to keep up with shifting global security frameworks or advanced virtualization research.

  #### Ethical Leadership Action:

  The manager restructures the administrator's schedule to dedicate 15% of their weekly hours strictly to professional growth. The company pays for advanced cloud security certification courses and sponsors their attendance at an international computing conference. The leader ensures the employee has the time and space to master the complex, emerging layers of their tech specialty rather than letting their skills plateau.

</details>

### III.VI Use care when modifying or retiring systems

Interface changes, the removal of features, and even software updates have an impact on the productivity of users and the quality of their work. Leaders should take care when changing or discontinuing support for system features on which people still depend. Leaders should thoroughly investigate viable alternatives to removing support for a legacy system. If these alternatives are unacceptably risky or impractical, the developer should assist stakeholders' graceful migration from the system to an alternative. Users should be notified of the risks of continued use of the unsupported system long before support ends. Computing professionals should assist system users in monitoring the operational viability of their computing systems, and help them understand that timely replacement of inappropriate or outdated features or entire systems may be needed.

<details>
  <summary>Example: Minimizing Disruption During Aggressive API Interface Changes</summary>

  #### The Scenario:

  A tech lead at a major financial gateway needs to deploy a massive structural update to their public API to comply with new banking regulations. The update will fundamentally change how third-party developers call the transaction endpoints, meaning existing code will break instantly if it isn't updated.

  #### Ethical Leadership Action:

  Recognizing that "interface changes and software updates have an impact on the productivity of users," the tech lead implements strict API versioning. They deploy the new code as v2 while keeping the legacy v1 endpoint fully operational for an overlapping 6-month period. They publish comprehensive migration guides, host live Q&A webinars for the developer community, and provide code snippets showing exactly how to rewrite requests from v1 to v2.

</details>

### III.VII Recognize and take special care of systems that become integrated into the infrastructure of society

Even the simplest computer systems have the potential to impact all aspects of society when integrated with everyday activities such as commerce, travel, government, healthcare, and education. When organizations and groups develop systems that become an important part of the infrastructure of society, their leaders have an added responsibility to be good stewards of these systems. Part of that stewardship requires establishing policies for fair system access, including for those who may have been excluded. That stewardship also requires that computing professionals monitor the level of integration of their systems into the infrastructure of society. As the level of adoption changes, the ethical responsibilities of the organization or group are likely to change as well. Continual monitoring of how society is using a system will allow the organization or group to remain consistent with their ethical obligations outlined in the Code. When appropriate standards of care do not exist, computing professionals have a duty to ensure they are developed.

<details>
  <summary>Example: Establishing Fair and Equitable Access Protocols for a Dominant Cloud Platform</summary>

  #### The Scenario:

   A tech company operates a cloud infrastructure platform that has grown to host over 40% of the world's public transit routing systems and local government emergency alert services. Because of its massive market share, a sudden price hike or a blanket policy change could accidentally bankrupt small, underfunded municipalities, cutting off citizens from essential public services.

  #### Ethical Leadership Action:

  The VP of Infrastructure recognizes that the platform is now integrated into societal infrastructure. They establish a dedicated "Public Sector & Infrastructure Care" division. This group drafts policies that freeze hosting rates for public utilities, guarantees high-priority uptime SLAs for municipal services, and creates a grant program to offer subsidized, fair access to historically excluded or low-income regions.

</details>

---

## IV. Compliance with the code

*A computing professional should...*

### IV.I Uphold, promote, and respect the principles of the Code

The future of computing depends on both technical and ethical excellence. Computing professionals should adhere to the principles of the Code and contribute to improving them. Computing professionals who recognize breaches of the Code should take actions to resolve the ethical issues they recognize, including, when reasonable, expressing their concern to the person or persons thought to be violating the Code.

### IV.II Treat violations of the Code as inconsistent with membership in the ACM

Each ACM member should encourage and support adherence by all computing professionals regardless of ACM membership. ACM members who recognize a breach of the Code should consider reporting the violation to the ACM, which may result in remedial action as specified in the ACM's Code of Ethics and Professional Conduct Enforcement Policy.

---

[^1]: https://www.acm.org/code-of-ethics
