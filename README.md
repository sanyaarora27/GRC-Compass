# GRC-Compass

**Why I built this**

Back in India, I went through the process of registering a small business. That meant working through inter-state rules and jurisdiction issues, with so many laws involved that working out what actually applied was a challenge in itself.

I didn't have the idea for this tool then. But when I came to the UK for my MSc in Cybersecurity, I decided to build something that would have helped. Anyone starting a business, or planning to, needs to be clear on the laws and jurisdictions that apply to them. People without a legal or security background find that information hard to find, and harder to understand.

Most compliance guidance is written for organisations that already have legal and security teams. Founders, schools and charities usually don't, yet they handle personal data, often children's data, use AI tools every day, and work across borders. GRC Guide gives them a clear, approachable starting point.

**Who it's for**
Audience	What they usually don't know
People planning to start an organisation	What needs to be in place before launch
Startups and small businesses	What applies now and what can come later
Established businesses	Existing obligations, contracts and new exposure
Schools and education providers	How privacy, safeguarding and AI procurement fit together
Charities and non-profits	How to protect beneficiaries, donors, staff and volunteers proportionately
Walkthrough
Home

The landing page introduces the three regions and the three main tools, and explains the core pillars of GRC: governance, risk management and compliance.

Show Image

**Framework library**

A searchable library of 28 laws, frameworks, standards and guidance documents, filterable by category (Information Security, Privacy & Data Protection, Risk Management and more). Each card shows the category, a short description, the type and the relevant industry.

Show Image

**Region	Entries**
UK	UK GDPR + DPA 2018, PECR, ICO data protection fee, ICO Children's Code, KCSIE 2026, DfE generative AI product safety standards
EU	GDPR, EU representative, ePrivacy rules, NIS2, DORA, EU AI Act, Cyber Resilience Act
India	DPDP Act + Rules, India child-data school exemption, CERT-In Directions, RBI directions, SEBI CSCRF
International	ISO 27001, SOC 2, PCI-DSS, ISO 31000, ISO 22301, COSO ERM, NIST SP 800-61, CIS Controls, COBIT, ITIL
Filtered: Information Security	Filtered: Privacy & Data Protection
Show Image	Show Image

**Jurisdiction explorer**

A focused guide to the EU, UK and India covering privacy, cybersecurity, sector rules, children's data and AI. Each jurisdiction lists its key laws and a "What to check" section, where every item is labelled by type (Law, National law, Regulation, Statutory code, Safeguarding guidance, Procurement checklist, Narrow exemption) with a plain-English note on when it applies.

**Highlights:**

UK: KCSIE 2026 for schools and colleges in England (in force from 1 September 2026, covering AI-generated harms, filtering, monitoring and staff training) and the DfE generative AI product safety standards (published 19 January 2026)
EU: EU AI Act, including the prohibition on emotion recognition in education and the high-risk status of AI used for admissions, grading and exam proctoring
India: DPDP main obligations shown with their computed start date of 13 May 2027, and the narrow child-data exemption for schools

Show Image

**Applicability wizard**

A short profile that tailors the results:

Step	Question	Options
1. Audience	Who are you planning for?	Planning to start · Startup or small business · Established business · School or education provider · Charity or non-profit
2. Industry	What is your primary industry?	Technology/SaaS · Healthcare/HealthTech · Finance/FinTech · E-commerce/Retail · Professional Services · Other
3. Location	Where do you operate?	Physical operations and customers across EU · UK · India
4. Data	What data do you process?	Basic personal · Health/medical · Financial/payments · Children's · Sensitive/behavioural · B2B corporate
5. Size	Company size and stage	Early-stage · Small business · Mid-market · Enterprise
+ AI use	How do you use AI?	Shown only to schools, education providers, charities and non-profits
Audience	Location	Data
Show Image	Show Image	Show Image
Your GRC Roadmap

*Results are grouped by priority: Critical / Legally Required, Highly Recommended and Good to Have. Each item explains in one line why it matters and links to its full framework page.*

Show Image

**Glossary**

Plain-English definitions of compliance terms, searchable and indexed A–Z, with links to related frameworks.

Show Image

**Key decisions**

Three regions, not the world. The first version covered 20 frameworks and 15 jurisdictions. Narrowing to the UK, EU and India made it possible to get the content right.
Five audiences, not just founders. Schools and charities handle sensitive data with the fewest resources to get it right.
Typed obligations. A law, a statutory code, a contractual requirement and voluntary guidance are not the same thing, and the jurisdiction explorer labels each one.
Dates shown honestly. Where a start date is computed rather than officially confirmed, as with India's DPDP obligations, the site says so.
AI where the risk is highest. The AI step appears for schools and charities, where AI tools meet children and vulnerable people.

**Lessons Learnt:** 

1. Not every requirement is a legal requirement. Laws, statutory codes, contractual requirements (PCI DSS), attestations (SOC 2) and voluntary guidance are different things. Labelling each correctly stopped the results overstating what's legally required.
2. The law changes while you build. During development, the EU AI Act's high-risk deadline moved to December 2027, the UK changed its automated decision-making rules, and India introduced labelling rules for AI-generated content. Every entry needs a date and a regular review.
3. The audience shapes the questions. Startup language like "customers" and "Series A/B" excludes schools and charities. Asking what kind of organisation someone is before anything else changes what every later question needs to be.
4. Same data, different rules. The UK and EU now diverge on automated decisions and data transfers, and the age at which someone counts as a child differs across all three regions.
Recommending everything helps no one. A small organisation doesn't need enterprise frameworks like COSO or COBIT. Being useful means telling people what can safely wait.

**What I'd improve:**

1. India's main DPDP obligations are shown with a computed start date of 13 May 2027 and labelled as computed, not presented as confirmed.
2. Use the jurisdiction explorer's precise type labels (Law, Statutory code, Guidance) on library cards too, instead of "Standard / Legal Req.
3. "Why this applies to you." Each result should name the answer that triggered it, such as "Because you selected children's data." Without that, users can't tell whether to trust it.
4. What to do first. A headteacher can't act on "UK GDPR." They can act on "Appoint a Data Protection Officer." Turn each result into its first concrete step.
5. Official source and review date on every entry. This is the difference between a trustworthy resource and a list of claim/s.
6. The data transfer question. It's the most common blind spot: staff pasting data into US-hosted AI tools, or an Indian team accessing UK data.
7. Share or export results. School leaders report to governors, and founders share with co-founders. A PDF or shareable link makes the tool part of their workflow.

**Disclaimer**

The information on this website does not constitute legal advice. All information is for general informational purposes only. Always check requirements with the official source or a qualified professional.

**Author**

Sanya Arora, MSc Cybersecurity, University of Surrey GitHub · Blog
