# MPPRO Enterprise Growth & Feature Roadmap (14-Day Automated Plan)

This roadmap defines the 2-week transformation plan for **MPPRO (مدیریت جامع یکپارچه پروژه)** to achieve world-class enterprise positioning in the Construction & Industrial Project Management software market (benchmarked against Procore, Autodesk Construction Cloud, and Oracle Primavera Aconex).

---

## 📅 14-Day Execution Schedule

### **Week 1: Core Landing Page & Enterprise Conversion Architecture**

- **Day 1: Role & Industry Solutions Navigation (Mega-Menu)**
  - *Target*: `index.html`, `about.html`
  - *Goal*: Structured header menu for Owners, Contractors, Consultants, and Industry Sectors (Civil, Oil & Gas, Infrastructure).

- **Day 2: Hero Banner Modernization & Dual Call-to-Action (CTA)**
  - *Target*: `index.html`
  - *Goal*: High-impact headline, "رزرو دمو اختصاصی" & "تور تعاملی نرم‌افزار" CTAs, and live trust metrics bar.

- **Day 3: Enterprise Trust, Security & SLA Section**
  - *Target*: `index.html`
  - *Goal*: ISO 27001 badges, 99.9% Uptime SLA guarantee, AES-256 encryption, and Air-gapped On-Premise deployment option.

- **Day 4: Interactive ROI & Value Calculator Component**
  - *Target*: `index.html`, `js/theme.js`
  - *Goal*: Real-time range sliders for active projects and contract values with dynamic calculations for time and cost savings.

- **Day 5: Technical Office & Field Engineering Showcase (RFI / Submittals)**
  - *Target*: `index.html`
  - *Goal*: Visual breakdown of RFI approval cycles, versioned drawing registers, and daily field inspection logs.

- **Day 6: Earned Value Management (EVM) & Financial Control Showcase**
  - *Target*: `index.html`
  - *Goal*: WBS/CBS alignment, EVM metrics (SPI/CPI/EAC), and contractor progress billing workflows.

- **Day 7: Lead Conversion Demo Request Form Modal**
  - *Target*: `index.html`
  - *Goal*: Modal popup form capturing company size, project type, position, and deployment preferences.

---

### **Week 2: Persona Landing Pages, Security & Trust Assets**

- **Day 8: Dedicated Landing Page for Project Owners (`solutions/for-owners.html`)**
  - *Goal*: Macro portfolio visibility, budget variance protection, and audit-ready reporting for project employers.

- **Day 9: Dedicated Landing Page for General Contractors (`solutions/for-contractors.html`)**
  - *Goal*: Subcontractor management, daily site logs, submittal turnaround speed, and progress billing approvals.

- **Day 10: Dedicated Landing Page for Engineering Consultants (`solutions/for-consultants.html`)**
  - *Goal*: Drawing approvals, QA/QC non-conformance reports (NCR), and transmittal logs.

- **Day 11: Enterprise Security & Deployment Architecture Page (`security.html`)**
  - *Goal*: Local Iranian cloud vs private on-premise installation options, RBAC security, and ISO compliance.

- **Day 12: Case Studies & Client Success Stories Page (`case-studies.html`)**
  - *Goal*: Real-world project showcases highlighting schedule savings and RFI turnaround metrics.

- **Day 13: Project Management Knowledge Hub / Blog (`blog.html`)**
  - *Goal*: Educational articles on EVM implementation, delay claim mitigation, and digital archives.

- **Day 14: System Verification, Link Integrity & Mobile UX Optimization**
  - *Goal*: Cross-page navigation routing verification, mobile responsiveness optimization, and final performance check.

---

## 🤖 Automated AI Agent Scheduled Prompt

Use the following prompt when assigning daily tasks to an automated AI agent connected to this repository:

```text
You are an expert software engineer AI agent executing the scheduled roadmap for MPPRO.

TASK EXECUTION INSTRUCTIONS:
1. READ ROADMAP & IDENTIFY DAY:
   - Check git log (`git log --oneline -n 10`) and read `ROADMAP.md` and `AI_AGENT_INSTRUCTIONS.md`.
   - Identify the earliest uncompleted day in `ROADMAP.md` (Day 1 through Day 14).

2. IMPLEMENT TODAY'S MILESTONE:
   - Review target files specified for today's milestone in `ROADMAP.md`.
   - Apply edits adhering to RTL layout rules (`dir="rtl"`), IRANSans typography (`font-irsans`), Bootstrap 5 grid system, and theme styling conventions.

3. VERIFY WORK:
   - Read modified files to confirm HTML markup validity, closed tags, and correct relative links.
   - Run tests or syntax validation scripts via bash session.

4. COMMIT & RECORD:
   - Commit changes with message: `feat(day-X): brief summary of day's feature` (where X is the day number).
```
