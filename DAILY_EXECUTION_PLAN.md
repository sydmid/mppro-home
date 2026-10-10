# MPPRO 14-Day Automated AI Agent Execution Plan

This document outlines a structured, 14-day execution plan designed specifically for an AI agent running scheduled daily tasks. Each day focuses on implementing powerful, enterprise-grade features and content for MPPRO based on global industry benchmarks (Procore, Autodesk, Oracle Primavera).

---

## Plan Overview & Architecture

- **Week 1 (Days 1–7): Enterprise Landing Page & Core Landing Page Enhancements**
- **Week 2 (Days 8–14): Specialized Landing Pages, Security, Case Studies & Lead Generation**

---

## WEEK 1: Core Website Infrastructure & Landing Page Features

### **Day 1: Solutions Navigation & Persona Mega-Menu Structure**
- **Target File**: `index.html`, `about.html`
- **Objective**: Expand top navigation bar into an enterprise mega-menu categorized by **Role/Stakeholder** (Owners, General Contractors, Consultants, Executives) and **Industry** (Civil, Infrastructure, Oil & Gas, Industrial).
- **Deliverables**:
  - Update `#navbarNav` dropdown in `index.html` and `about.html` with tabs/columns for Roles & Industries.
  - Ensure mobile responsive layout works seamlessly.
- **AI Agent Prompt for Day 1**:
  > "Read index.html and update the header navigation mega-menu. Add organized columns for 'راهکارها بر اساس نقش' (For Owners, General Contractors, Consultants, PMO) and 'راهکارها بر اساس صنعت' (Civil, Infrastructure, Oil & Gas, Industrial). Verify html syntax after editing."

---

### **Day 2: Hero Section & Dual Call-To-Action (CTA)**
- **Target File**: `index.html`
- **Objective**: Modernize the homepage Hero section with enterprise messaging and dual CTA buttons.
- **Deliverables**:
  - Update primary headline: "سامانه جامع مدیریت و کنترل یکپارچه پروژه‌های عمرانی و صنعتی".
  - Add primary CTA: "درخواست دمو اختصاصی" (Request Custom Demo).
  - Add secondary CTA: "تور تعاملی نرم‌افزار" (Interactive Product Tour).
  - Add quick stats bar beneath hero (e.g., "+۱۰۰ هزار میلیارد تومان ارزش پروژه‌ها", "+۵۰ شرکت برتر").
- **AI Agent Prompt for Day 2**:
  > "Update hero-banner-seven in index.html with dual CTA buttons ('رزرو دمو اختصاصی' leading to demo form and 'تور تعاملی نرم‌افزار') and an immediate trust stats bar showing key platform metrics."

---

### **Day 3: Enterprise Trust & Security Badges Section**
- **Target File**: `index.html`
- **Objective**: Add a dedicated Security, Compliance & SLA section to reassure enterprise decision-makers.
- **Deliverables**:
  - Add new section `#enterprise-security` to `index.html`.
  - Feature badges/cards for: ISO 27001 (Information Security), SOC 2 Compliance Ready, 99.9% Uptime SLA, AES-256 Data Encryption, and Private On-Premise Installation option.
- **AI Agent Prompt for Day 3**:
  > "Add a new feature section in index.html titled 'امنیت و پایداری در سطح سازمانی'. Include cards for ISO 27001 certification, 99.9% SLA uptime guarantee, AES-256 data encryption, and local air-gapped deployment option."

---

### **Day 4: Interactive ROI & Value Calculator Component**
- **Target File**: `index.html`, `js/theme.js`
- **Objective**: Build an interactive ROI calculator widget on the homepage.
- **Deliverables**:
  - Add `#roi-calculator` section in `index.html` with input sliders for: Number of Active Projects, Total Contract Value (Billion IRR), and Team Size.
  - Implement real-time JavaScript calculation in `js/theme.js` showing estimated monthly hours saved in submittals/RFIs, schedule delay reduction percentage, and budget variance savings.
- **AI Agent Prompt for Day 4**:
  > "Add an interactive ROI Calculator component in index.html with range sliders for contract value and project count. Write JS logic in js/theme.js to calculate and dynamically display time and cost savings."

---

### **Day 5: Module Showcase 1 - Technical Office & Field Engineering (RFI / Submittals)**
- **Target File**: `index.html`, `images/`
- **Objective**: Highlight advanced Technical Office features (RFI, Submittals, Transmittals, Drawing Control) on the main page.
- **Deliverables**:
  - Create a dedicated feature section `#technical-office-showcase` in `index.html`.
  - Add visual breakdown of RFI approval workflows, version-controlled drawing registers, and daily field logs.
- **AI Agent Prompt for Day 5**:
  > "Add a feature showcase section in index.html for 'دفتر فنی و مهندسی کارگاهی' detailing RFI workflows, Submittals, Drawing revision history, and Daily Site Inspection Logs."

---

### **Day 6: Module Showcase 2 - Earned Value Management (EVM) & Financial Control**
- **Target File**: `index.html`
- **Objective**: Showcase enterprise financial and project control capabilities.
- **Deliverables**:
  - Add `#financial-evm-showcase` section in `index.html`.
  - Detail WBS/CBS alignment, Earned Value metrics (SPI, CPI, EAC), contractor progress billing, and real-time cash flow forecasting.
- **AI Agent Prompt for Day 6**:
  > "Add a feature section in index.html for 'کنترل پروژه و مدیریت مالی (EVM)' highlighting Earned Value Management (SPI/CPI), WBS/CBS hierarchy, and progress billing workflows."

---

### **Day 7: Demo Request & Contact Modal Enhancement**
- **Target File**: `index.html`
- **Objective**: Convert website visitors into enterprise leads with a structured demo booking form.
- **Deliverables**:
  - Add a popup Bootstrap modal or dedicated landing section `#demo-request-modal`.
  - Fields: Full Name, Company/Organization Name, Role/Position, Project Type (Civil, Oil & Gas, Infrastructure), Phone Number, Work Email, Preferred Deployment (Cloud or On-Premise).
- **AI Agent Prompt for Day 7**:
  > "Add a high-converting 'درخواست دمو اختصاصی' modal form in index.html with fields for company name, project type, position, phone number, and cloud/on-premise deployment preference."

---

## WEEK 2: Dedicated Landing Pages, Security, Case Studies & Content Expansion

### **Day 8: Solutions Page for Project Owners & Investors (`solutions/for-owners.html`)**
- **Target File**: `solutions/for-owners.html`
- **Objective**: Create a specialized landing page tailored for Project Owners / Clients (کارفرمایان).
- **Deliverables**:
  - Create `solutions/for-owners.html` emphasizing macro portfolio visibility, budget overrun prevention, real-time executive dashboards, and audit-ready reporting.
- **AI Agent Prompt for Day 8**:
  > "Create solutions/for-owners.html based on index.html layout. Focus messaging on portfolio control, financial risk mitigation, and executive decision-making dashboards for project employers."

---

### **Day 9: Solutions Page for General Contractors & EPCs (`solutions/for-contractors.html`)**
- **Target File**: `solutions/for-contractors.html`
- **Objective**: Create a landing page targeting General Contractors and EPC firms.
- **Deliverables**:
  - Create `solutions/for-contractors.html` highlighting field productivity, submittal turnarounds, subcontractor management, daily logs, and cash flow tracking.
- **AI Agent Prompt for Day 9**:
  > "Create solutions/for-contractors.html emphasizing site daily logs, submittal/RFI speed, subcontractor management, and progress billing approvals."

---

### **Day 10: Solutions Page for Engineering Consultants (`solutions/for-consultants.html`)**
- **Target File**: `solutions/for-consultants.html`
- **Objective**: Create a landing page targeting Consulting Engineers and Supervision Teams (مهندسان مشاور و نظارت).
- **Deliverables**:
  - Create `solutions/for-consultants.html` highlighting document control, drawing approvals, quality assurance, safety non-conformance reports (NCRs), and meeting minutes tracking.
- **AI Agent Prompt for Day 10**:
  > "Create solutions/for-consultants.html focusing on engineering document review, QA/QC inspections, NCR logging, and transmittal management."

---

### **Day 11: Enterprise Security & Deployment Landing Page (`security.html`)**
- **Target File**: `security.html`
- **Objective**: Create a dedicated enterprise security and deployment architecture page.
- **Deliverables**:
  - Create `security.html` detailing cloud infrastructure (Iranian local cloud & international backup options), private air-gapped on-premise installation, role-based access control (RBAC), and ISO 27001 data governance.
- **AI Agent Prompt for Day 11**:
  > "Create security.html highlighting data protection standards, AES-256 encryption, air-gapped on-premise server deployment for sensitive infrastructure, and ISO compliance."

---

### **Day 12: Case Studies & Project Success Stories (`case-studies.html`)**
- **Target File**: `case-studies.html`
- **Objective**: Build social proof with real-world case study templates and metrics.
- **Deliverables**:
  - Create `case-studies.html` showcasing 3 enterprise project case studies (e.g. Commercial Megaproject, Dam/Infrastructure Project, Industrial Refinery).
  - Include key outcome metrics: "35% faster RFI responses", "Zero budget overrun", "100% digital document archive".
- **AI Agent Prompt for Day 12**:
  > "Create case-studies.html showcasing 3 detailed enterprise construction success stories with metrics on schedule savings, RFI turnaround improvements, and budget control."

---

### **Day 13: Specialized Project Management Knowledge Center / Blog (`blog.html`)**
- **Target File**: `blog.html`
- **Objective**: Establish domain authority with educational content on construction management standards.
- **Deliverables**:
  - Create `blog.html` featuring initial expert articles:
    1. "پیاده‌سازی مدیریت ارزش حاصله (EVM) در پروژه‌های عمرانی کشور"
    2. "راهکار‌های کاهش ادعا (Claim) و مدیریت تاخیرات با آرشیو دیجیتال"
    3. "مقایسه استقرار نرم‌افزار مدیریت پروژه بر روی سرور اختصاصی در برابر ابر"
- **AI Agent Prompt for Day 13**:
  > "Create blog.html with structured articles on EVM implementation in Iranian civil projects, claim mitigation through digital archives, and cloud vs on-premise PM software deployment."

---

### **Day 14: Final System Verification, Link Integrity & Mobile UX Optimization**
- **Target File**: All HTML files (`index.html`, `about.html`, `solutions/*.html`, `security.html`, `case-studies.html`, `blog.html`)
- **Objective**: Ensure seamless link routing, mobile responsiveness, smooth animations, and fast load times across the entire site.
- **Deliverables**:
  - Verify all relative links across headers, footers, and buttons.
  - Optimize mobile navigation toggle and drawer layouts.
  - Perform full site validation.
- **AI Agent Prompt for Day 14**:
  > "Inspect all site pages for link integrity, check header/footer consistency across all subpages, verify mobile menu toggle functionality, and ensure smooth scroll triggers."
