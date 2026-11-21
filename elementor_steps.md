Here is a complete, step-by-step guide to building the **WExpls** website directly inside **Elementor on Hostinger** without writing any custom application code.

This setup allows you to visually edit every section, copy, button, and image in the drag-and-drop Elementor editor at any time.

---

## 🛠️ Step 1: Initialize WordPress & Theme on Hostinger

1. Log into your **Hostinger hPanel**.
2. Go to **Websites** ➔ Click **Auto Installer** ➔ Select **WordPress**.
3. Complete the quick setup form (Name: `WExpls`, domain, administrator username/password).
4. Once installed, click **Admin Panel** to log into your WordPress Dashboard.
5. Go to **Appearance ➔ Themes** ➔ Click **Add New**.
6. Search for **Hello Elementor** or **Astra** (both are lightweight, optimized, free themes built for Elementor). Click **Install** and **Activate**.

---

## 🔌 Step 2: Install Required Free Plugins

In your WordPress admin dashboard, go to **Plugins ➔ Add New** and install the following plugins:

1. **Elementor Header & Footer Builder** *(Free)*: Allows you to create dynamic Headers and Footers visually.
2. **Essential Addons for Elementor** or **Royal Elementor Addons** *(Free)*: Provides pre-built tabs, accordions, and pricing tables for your practice areas and pricing packages.
3. **Template Kit Import** or **Spexo Addons / Envato Elements** *(Free)*: For easily importing starter templates if desired.
4. **WPForms** or **Fluent Forms** *(Free)*: For your lead consultation forms.

---

## 🎨 Step 3: Set Global Brand Colors & Fonts in Elementor

To keep your website cohesive and premium across all 9 pages, configure your Global Settings once:

1. Create a new page under **Pages ➔ Add New** named **Home**, and click **Edit with Elementor**.
2. In the top-left menu (hamburger icon ☰), click **Site Settings**.
3. Navigate to **Global Colors** and set:
* **Primary:** `#0F172A` *(Deep Executive Navy)*
* **Secondary:** `#D97706` *(Warm Gold Accent)*
* **Text:** `#334155` *(Slate Gray)*
* **Accent / Background:** `#F8FAFC` *(Clean Off-White)*


4. Navigate to **Global Fonts** and set:
* **Primary / Headings:** `Plus Jakarta Sans` or `Montserrat` *(Semi-Bold / Bold)*
* **Body Text:** `Inter` or `Open Sans` *(Regular 16px)*


5. Click **Update**.

---

## 📐 Step 4: Build Header & Navigation Footer (Once for All Pages)

Using **Elementor Header & Footer Builder**:

1. Go to **Appearance ➔ Elementor Header & Footer Builder** ➔ Click **Add New**.
2. Select **Type of Template: Header** ➔ Set **Display On: Entire Website**. Click **Edit with Elementor**.
3. Drag a **3-Column Section**:
* **Column 1 (20%):** Drag an **Image Widget** for the **WExpls Logo**.
* **Column 2 (60%):** Drag a **Nav Menu Widget**. Add pages: *Home, Leadership Hiring, Sales Hiring, Career Advisory, Outplacement, Success Stories, Insights, About Us, Contact*.
* **Column 3 (20%):** Drag a **Button Widget** ➔ Text: `Schedule Consultation` ➔ Link to `/contact`.


4. Repeat the same step for the **Footer** template (Quick links, Contact information, LinkedIn social icons, Privacy Policy).

---

## 📑 Step 5: How to Build the Pages Using Standard Elementor Widgets

Here is the exact widget layout structure to assemble each page visually in the Elementor drag-and-drop editor:

### 1. Homepage (`/`)

* **Hero Section (Container / Section):**
* **Heading Widget:** `Building Leadership. Driving Growth. Shaping Careers.`
* **Text Editor Widget:** `WExpls is a premier talent and career advisory firm...`
* **Inner Section / 2 Buttons:**
* Button 1 (Primary Gold): `Discuss Your Hiring Needs`
* Button 2 (Outline Navy): `Book Advisory Consultation`




* **Trust Bar:**
* **Icon Box / Text Widget:** `Serving Organizations Across: Financial Services • Fintech • Manufacturing • Consumer • Retail • Consulting`


* **Who We Help (2 Columns):**
* Column 1 (Card Box): Heading: *For Organizations*, Text, Button: *Explore Talent Search*.
* Column 2 (Card Box): Heading: *For Professionals*, Text, Button: *Explore Career Advisory*.


* **Core Practices (Tabs / Icon Box Grid):**
* 4 Cards using **Icon Box Widgets** for *Leadership Hiring*, *Sales Hiring*, *Career Advisory*, and *Outplacement Support*.


* **Why Clients Choose WExpls (Grid 3x2):**
* **Icon Boxes** with titles: *Research-Led Search*, *Founder-Led Engagement*, *Quality Over Volume*, *Business Understanding*, *Relationship Driven*.


* **CTA Banner:** Dark Navy background, Heading, Subheading, and a `Schedule Consultation` button linking to `/contact`.

### 2. Leadership Hiring Page (`/leadership-hiring`)

* **Hero:** Title & Description.
* **Roles We Cover:** Use an **Icon Box Matrix** or **Icon List Widget** with 3 Columns:
* Column 1: *CEO, COO, CFO, CHRO, CTO*
* Column 2: *Business Head, General Manager, Managing Director*
* Column 3: *Operations Head, Plant Head, Supply Chain Director*


* **Our 7-Step Process:** Use the **Process / Timeline Widget** (from EA or Royal Addons) or 7 consecutive Icon Boxes representing: *Discovery → Market Mapping → Candidate Outreach → Assessment → Client Interviews → Offer Negotiation → Executive Onboarding*.

### 3. Sales Hiring Page (`/sales-hiring`)

* **Hero:** Title & Description.
* **Evaluation Framework:** Use a **4-Box Feature Grid** highlighting: *Quota Attainment*, *Deal Complexity*, *Territory Growth*, *Strategic Selling Capability*.
* **Roles Covered Accordion:** Use the **Accordion Widget** with tabs for *Individual Contributors*, *Mid-Level Managers*, and *Revenue Leadership (CRO/VP Sales)*.

### 4. Career Advisory Page (`/career-advisory`)

* **Hero:** Title & Description.
* **Services Grid:** 5 Card Sections (*Career Assessment, Resume Review, LinkedIn Optimization, Interview Preparation, Career Transition Planning*).
* **Tiered Pricing Table:** Use the **Pricing Table Widget** for the 4 tiers:
1. **Essential:** *Resume Review*
2. **Professional:** *Resume + LinkedIn Review*
3. **Executive:** *Career Strategy + Interview Coaching*
4. **Leadership:** *Executive Coaching & Personal Branding*



### 5. Outplacement Services Page (`/outplacement`)

* **Hero:** Title & Description.
* **Dual Column Card Layout:**
* Column 1 (*For Employers*): Outplacement Programs, Career Workshops, Resume Support.
* Column 2 (*For Employees*): Career Counseling, Job Search Strategy, LinkedIn Optimization.



### 6. Success Stories Page (`/success-stories`)

* **Layout:** Use **Toggle Widgets** or **Card Containers** structured into:
1. *Client Challenge*
2. *Search Strategy*
3. *Quantifiable Outcome* (e.g., "Filled in 42 Days | Exceeded Q1 target by 135%").



### 7. About Us Page (`/about-us`)

* **Story & Mission Container:** Text blocks and founder/advisory team photos.
* **Values Grid:** **Icon Box Widgets** for *Integrity*, *Partnership*, *Professionalism*, *Accountability*, and *Long-Term Relationships*.

### 8. Insights & Resources Page (`/insights`)

* **Blog Posts Layout:** Use the **Posts / Dynamic Grid Widget** to dynamically display your blog posts under categories like *Leadership Hiring*, *Sales Strategy*, and *Career Advice*.

### 9. Contact Page (`/contact`)

* **2-Column Container:**
* **Left Column:** Office location text, direct email, phone, LinkedIn button.
* **Right Column:** **WPForms Widget** with input fields for *Name*, *Company*, *Email*, *Phone*, *Requirement (Dropdown)*, and *Message*.



---

## 🔍 Step 6: Configure SEO Titles & Meta Descriptions (Rank Math / Yoast)

To ensure your search optimization is complete:

1. Install **Rank Math SEO** or **Yoast SEO** plugin *(Free)*.
2. Edit each page in WordPress, scroll to the SEO settings panel at the bottom, and copy/paste these optimized metadata snippet tags:

* **Homepage (`/`)**
* **Title:** `Leadership Hiring, Sales Hiring & Career Advisory Services | WExpls`
* **Meta Description:** `WExpls helps organisations hire exceptional leaders and sales talent while supporting professionals through pivotal career transitions and growth.`


* **Leadership Hiring (`/leadership-hiring`)**
* **Title:** `Leadership Hiring & Executive Search Services | WExpls`
* **Meta Description:** `Executive search and leadership hiring solutions for CXO, director and senior management positions across industries.`


* **Sales Hiring (`/sales-hiring`)**
* **Title:** `Sales Hiring Solutions | Revenue & Commercial Talent Recruitment`
* **Meta Description:** `Specialised sales hiring services covering sales leadership, enterprise sales, business development and commercial talent acquisition.`


* **Career Advisory (`/career-advisory`)**
* **Title:** `Career Counselling, Interview Coaching & Career Advisory | WExpls`
* **Meta Description:** `Career counselling, LinkedIn optimisation, interview preparation and leadership career coaching for professionals seeking growth.`



---

## 💡 Benefits of Building with Elementor on Hostinger

* **100% Visual Customization:** You can click any text, background, image, or button and change it instantly in real time.
* **No Code Dependencies:** Future updates, blog posts, and team additions can be completed in seconds without touching CSS or HTML files.
* **Easy Backups & Migration:** Hostinger handles automatic daily backups, SSL security, and performance caching natively through hPanel.
