# Portfolio Project Data — Prajagamer Website UIUX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/prajagamer_website_uiux_design/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image03.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "prajagamer-website-uiux-design",
  "code": "PRO-41 // UX-04",
  "title": "Prajagamer Website UIUX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2024",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/Prajagamer-Website-UIUX-Design",
  "license": "MIT License",
  "banner": "/images/projects/prajagamer_website_uiux_design/banner.webp",
  "summary": "High-fidelity Figma web portal and admin dashboard UI/UX design for Disdukcapil Kota Semarang's Prajagamer internship program.",
  "projectDescription": "Prajagamer Website UIUX Design defines a role-based web portal and administrative dashboard in Figma for Disdukcapil Kota Semarang's Magang Merdeka program, organizing 18 high-fidelity screens across public onboarding, two-step student application, status tracking, and staff management.",
  "architectureSummary": "Role-based three-tier Figma architecture separating Before Login public onboarding, After Login applicant workflows, and Dashboard Admin management.",
  "techStack": [
    "Figma",
    "WebP",
    "PNG",
    "Markdown",
    "Git"
  ],
  "telemetryMatrix": {
    "projectType": "Web & Dashboard UI/UX Design",
    "targetPlatform": "Responsive Web Portal",
    "primaryDomain": "Civic Internship & Public Sector",
    "architecturePipeline": "Pre-Auth -> Applicant -> Admin Console",
    "testingAndAudit": "Design Review",
    "projectStatus": "Completed",
    "projectYear": "2024"
  },
  "uiUxProjectInfo": {
    "platformType": "Web Portal & Admin Dashboard",
    "designRole": "UI/UX Designer",
    "targetIndustry": "Public Administration & Civic Education",
    "designYear": "2024",
    "designStatus": "Completed"
  },
  "uiUxBackground": "Prospective Magang Merdeka interns at Disdukcapil Kota Semarang often face fragmented registration instructions and opaque review statuses. Prajagamer addresses this by uniting public agency information, structured multi-step applications, and an internal admin review console under one cohesive crimson-and-white visual system.",
  "uiUxUserResearch": {
    "keyFindings": [
      {
        "method": "Workflow & Role Mapping",
        "description": "Mapped public visitor, authenticated applicant, and superadmin responsibilities across the Disdukcapil internship lifecycle.",
        "keyFinding": "Separating Before Login discovery from After Login submission prevents unauthenticated visitors from encountering premature form complexity.",
        "badge": "Role Segmentation"
      },
      {
        "method": "Form Complexity Audit",
        "description": "Reviewed required applicant attributes including NIM, NIK, university, supervisor contacts, CV, transcript, and recommendation letter uploads.",
        "keyFinding": "Splitting registration biodata and document submission into a progressive 1/2 and 2/2 form reduces single-screen form fatigue.",
        "badge": "Progressive Disclosure"
      },
      {
        "method": "Administrative Operations Review",
        "description": "Evaluated staff tasks required to screen applicants, export records, update portal media, and provision new admin accounts.",
        "keyFinding": "Pairing top-level status KPI cards with direct row actions and an Export to Excel trigger streamlines daily applicant screening.",
        "badge": "Admin Efficiency"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "University Intern Applicant",
      "role": "Prospective Magang Merdeka Student",
      "demographics": "Undergraduate students preparing academic internship documents",
      "quote": "I need clear division details, exact document requirements, and a simple way to track whether my internship application was accepted.",
      "painPoints": [
        "Unclear registration sequence before creating an account",
        "Long single-page forms combining personal biodata with multiple PDF uploads",
        "Lack of visibility into application review progress after submission"
      ],
      "goals": [
        "Verify Disdukcapil divisions and registration steps quickly on Beranda and Info Magang",
        "Complete profile details and upload CV, transcript, and recommendation files cleanly",
        "Check real-time application decisions via Status Lamaran Magang notifications"
      ]
    },
    {
      "name": "Disdukcapil Superadmin",
      "role": "Agency Internship Coordinator",
      "demographics": "Public sector administrative staff managing seasonal intern intakes",
      "quote": "I need an immediate overview of incoming applications so our team can approve candidates, export spreadsheets, and manage admin access.",
      "painPoints": [
        "Manual tracking across scattered applicant spreadsheets and document folders",
        "Time-consuming status updates without centralized summary metrics",
        "Lack of self-service controls for updating gallery photos and adding staff admins"
      ],
      "goals": [
        "Monitor pending, accepted, and rejected counts from the Dashboard Admin overview",
        "Approve or reject submissions inline and export applicant tables to Excel",
        "Manage portal photos and create new administrator accounts via a dedicated modal"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The information architecture partitions the Figma workspace into three distinct navigation scopes: a public top bar for Before Login discovery, an authenticated applicant header with profile and notification triggers, and a fixed crimson left sidebar for Dashboard Admin operations.",
    "nodes": [
      {
        "section": "Before Login (Public Portal)",
        "screens": [
          "Login (Masuk Akun)",
          "Register (Registrasi Akun)",
          "Beranda (Overview & Alur Pendaftaran)",
          "Info Pendaftaran (Overview & 6-Step Guide)",
          "Info Magang (Profil, Bidang, Pelayanan TPDK)"
        ]
      },
      {
        "section": "After Login (Applicant Portal)",
        "screens": [
          "Beranda (Authenticated Landing)",
          "Info Pendaftaran (Guide & Apply CTA)",
          "Profile (Biodata, Education & Supervisor)",
          "Form Pendaftaran (Step 1/2 Applicant Data)",
          "Daftar ke Lowongan (Step 2/2 Document Uploads)",
          "Notif (Status Lamaran Magang)"
        ]
      },
      {
        "section": "Dashboard Admin (Staff Console)",
        "screens": [
          "Beranda (KPI Counters & Data Pendaftar)",
          "Data Pelamar Magang (Table & Export to Excel)",
          "Upload Foto (Portal Media Upload)",
          "Data Admin (Account List & Tambah Admin Modal)"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "Prospective interns move sequentially from public discovery on Beranda and Info Magang into account registration, authentication, profile verification, a two-step internship application wizard, and status notification tracking while administrators review and decide outcomes.",
    "steps": [
      {
        "step": "01",
        "title": "Explore Program & Divisions",
        "description": "Visitors review Disdukcapil Kota Semarang overview, 4-step registration roadmap, and Info Magang division tabs before signing up.",
        "screenOrAction": "Before Login -> Beranda & Info Magang"
      },
      {
        "step": "02",
        "title": "Register Applicant Account",
        "description": "Students enter identity and university metadata while attaching initial photo, CV, and transcript files on the Register screen.",
        "screenOrAction": "Register -> Submit Account Form"
      },
      {
        "step": "03",
        "title": "Authenticate & Review Profile",
        "description": "Applicants sign in via Masuk Akun and verify personal data, academic history, and supervisor contacts in Profile.",
        "screenOrAction": "Login -> Profile (Update Profile)"
      },
      {
        "step": "04",
        "title": "Complete Application Step 1/2",
        "description": "Authenticated users confirm personal details, education, and branch placement availability before advancing.",
        "screenOrAction": "Form Pendaftaran 1/2 -> Selanjutnya"
      },
      {
        "step": "05",
        "title": "Upload Supporting Files Step 2/2",
        "description": "Applicants upload their recommendation letter, CV, optional portfolio URL, and accept terms to submit.",
        "screenOrAction": "Daftar ke Lowongan 2/2 -> Submit"
      },
      {
        "step": "06",
        "title": "Admin Screening & Status Notice",
        "description": "Superadmins review submissions in Dashboard Admin using Terima or Tolak actions, updating the applicant's Notif card.",
        "screenOrAction": "Dashboard Admin -> Notif (Status Lamaran Magang)"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Before Login — Public Portal, Authentication & Info Magang Flows",
      "imageUrl": "/images/projects/prajagamer_website_uiux_design/image01.webp"
    },
    {
      "title": "After Login — Applicant Profile, Two-Step Form & Status Notifications",
      "imageUrl": "/images/projects/prajagamer_website_uiux_design/image02.webp"
    },
    {
      "title": "Dashboard Admin — KPI Metrics, Applicant Table, Media Upload & Admin Modal",
      "imageUrl": "/images/projects/prajagamer_website_uiux_design/image03.webp"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Civic Crimson",
        "hex": "#C14440",
        "role": "Primary",
        "usage": "Public portal hero banners, section headers, primary CTA buttons, and footer panels"
      },
      {
        "name": "Admin Sidebar Red",
        "hex": "#DC2626",
        "role": "Primary Navigation",
        "usage": "Fixed left sidebar background and active navigation framing inside Dashboard Admin"
      },
      {
        "name": "Action Blue",
        "hex": "#4785F0",
        "role": "Accent",
        "usage": "Administrative utility buttons including Export to Excel, Unggah, and Simpan modal actions"
      },
      {
        "name": "Pure White",
        "hex": "#FFFFFF",
        "role": "Surface",
        "usage": "Form cards, navigation bars, KPI tiles, and data table containers"
      },
      {
        "name": "Soft Cool Gray",
        "hex": "#F3F5F7",
        "role": "Background",
        "usage": "Admin dashboard workspace canvas separating cards and tables"
      },
      {
        "name": "Charcoal Dark",
        "hex": "#1E1E1E",
        "role": "Text / Canvas",
        "usage": "High-contrast typography and Figma presentation canvas backdrop"
      }
    ],
    "typography": [
      {
        "name": "Hero Display Title",
        "role": "Heading",
        "font": "Sans-Serif",
        "sizeWeight": "Bold Display",
        "usage": "Main banner headlines on Beranda, Info Pendaftaran, and Info Magang"
      },
      {
        "name": "Section & Card Heading",
        "role": "Heading",
        "font": "Sans-Serif",
        "sizeWeight": "SemiBold",
        "usage": "Page section titles, step roadmap headings, and admin table headers"
      },
      {
        "name": "Body & Table Copy",
        "role": "Body",
        "font": "Sans-Serif",
        "sizeWeight": "Regular",
        "usage": "Disdukcapil descriptions, form field inputs, and applicant data rows"
      },
      {
        "name": "Navigation & Button Label",
        "role": "Label",
        "font": "Sans-Serif",
        "sizeWeight": "Medium",
        "usage": "Top navbar links, division tabs, sidebar items, and action triggers"
      }
    ],
    "componentStates": [
      {
        "component": "Primary & Action Buttons",
        "states": ["Default", "Hover", "Active"],
        "notes": "High-contrast crimson CTAs on public portal forms and blue utility buttons in admin views"
      },
      {
        "component": "Form Inputs & File Uploaders",
        "states": ["Default", "Focus", "Filled"],
        "notes": "Outlined text fields and native file selector controls across Register, Profile, and Form 1/2-2/2"
      },
      {
        "component": "Division & Sidebar Navigation",
        "states": ["Default", "Active"],
        "notes": "Filled crimson pill tabs on Info Magang and highlighted sidebar links on Dashboard Admin"
      },
      {
        "component": "Tambah Admin Modal Dialog",
        "states": ["Default", "Overlay"],
        "notes": "Centered modal with dimmed backdrop and paired Cancel/Simpan action buttons"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "susScore": "Design Review Only",
    "taskSuccessRate": "Not Empirically Tested",
    "timeOnTask": "Not Empirically Tested",
    "iterations": [
      {
        "usabilityIssue": "Dense registration requirements combining personal metadata with multiple document uploads on one screen",
        "iterationSolution": "Structured authenticated submission into a two-step flow (Form Pendaftaran 1/2 and Daftar ke Lowongan 2/2)",
        "impact": "Clarified progress between biodata confirmation and PDF/portfolio file uploads"
      },
      {
        "usabilityIssue": "First-time visitors needing quick clarity on internship eligibility and Disdukcapil placement divisions",
        "iterationSolution": "Added an illustrated 4-step Alur Pendaftaran roadmap on Beranda and tabbed Info Magang sections",
        "impact": "Improved scannability of division profiles, TPDK services, and registration steps prior to login"
      },
      {
        "usabilityIssue": "Administrative teams needing both high-level intake metrics and bulk spreadsheet reporting",
        "iterationSolution": "Combined four KPI summary cards on Dashboard Admin with an Export to Excel button and Tambah Admin modal",
        "impact": "Streamlined applicant review and staff account creation within a single sidebar workspace"
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "Completed Figma Design Archive",
    "totalFrames": 18,
    "componentsCount": 16,
    "handoffSpecs": "18 desktop high-fidelity frames organized across Before Login, After Login, and Dashboard Admin on Figma Page 1 with WebP showcase exports"
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "12-Column Web Layout",
    "designTokens": "Civic Crimson Palette",
    "typography": "Clean Sans-Serif Hierarchy",
    "prototypeFidelity": "High-Fidelity Visual Mockups"
  }
}
```
