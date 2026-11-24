# Portfolio Project Data — Prajagamer Website UIUX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/prajagamer_website_uiux_design/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image03.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "prajagamer-website-uiux-design",
  "code": "PRO-19 // UX-04",
  "title": "Prajagamer Website UIUX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2023",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/Prajagamer-Website-UIUX-Design",
  "license": "MIT License",
  "banner": "/images/projects/prajagamer_website_uiux_design/banner.webp",
  "summary": "High-fidelity UI/UX web design for Disdukcapil Semarang's Prajagamer internship portal, covering public discovery, applicant forms, and admin review.",
  "projectDescription": "Prajagamer Website UIUX Design presents a cohesive web portal interface in Figma for Disdukcapil Kota Semarang's Merdeka Internship program. Across 18 high-fidelity frames, it structures public onboarding, multi-step applicant submissions, status tracking, and an administrative review dashboard.",
  "architectureSummary": "Role-based three-zone web portal architecture spanning Before Login, After Login, and Dashboard Admin flows.",
  "techStack": [
    "Figma",
    "WebP"
  ],
  "telemetryMatrix": {
    "projectType": "Web Portal UI/UX Design",
    "targetPlatform": "Desktop Web Browser",
    "primaryDomain": "Civic & Internship Recruitment",
    "architecturePipeline": "3-Zone Role-Based Screen Flow",
    "testingAndAudit": "Design Flow Review Completed",
    "projectStatus": "Completed",
    "projectYear": "2023"
  },
  "uiUxProjectInfo": {
    "platformType": "Desktop Web Portal",
    "designRole": "UI/UX Designer",
    "targetIndustry": "Government & Public Sector Internship",
    "designYear": "2023",
    "designStatus": "Completed"
  },
  "uiUxBackground": "University students applying for internships at Disdukcapil Kota Semarang need clear eligibility guidance, transparent step-by-step registration workflows, and reliable application tracking. Meanwhile, agency staff require a centralized admin dashboard to filter applicants, verify documents, and manage decisions efficiently.",
  "uiUxUserResearch": {
    "keyFindings": [
      {
        "method": "Portal Workflow Structuring",
        "description": "Mapped public, applicant, and administrative requirements into dedicated role-based screen groups inside Figma (no formal user interviews archived).",
        "keyFinding": "Separating pre-login informational browsing from authenticated multi-step submission reduces form clutter for first-time visitors.",
        "badge": "Role Separation"
      },
      {
        "method": "Registration Step Breakdown",
        "description": "Evaluated multi-document internship intake requirements including CV, recommendation letters, transcripts, and placement consent.",
        "keyFinding": "Splitting application intake into a two-step wizard and providing a 6-step illustrated guide clarifies submission prerequisites.",
        "badge": "Guided Onboarding"
      },
      {
        "method": "Administrative Triage Mapping",
        "description": "Structured back-office review tasks around applicant counts, status filtering, spreadsheet export, and admin account provisioning.",
        "keyFinding": "Combining four top-level KPI counters with inline table actions (Lihat, Terima, Tolak) streamlines daily application triage.",
        "badge": "Admin Efficiency"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Prospective Student Intern",
      "role": "University or Vocational Internship Applicant",
      "demographics": "Undergraduate students seeking Merdeka internship placement in Semarang",
      "quote": "I want to know the required documents, which division fits my major, and whether my internship application was accepted.",
      "painPoints": [
        "Unclear internship division roles and registration prerequisites before signing up",
        "Overwhelming single-page forms requiring multiple academic and identity uploads"
      ],
      "goals": [
        "Review division profiles and step-by-step registration instructions quickly",
        "Submit supporting documents in a guided flow and track application status updates"
      ]
    },
    {
      "name": "Disdukcapil Admin Staff",
      "role": "Internship Program Coordinator & Superadmin",
      "demographics": "Agency personnel managing intake records and placement decisions",
      "quote": "I need a single dashboard to monitor applicant totals, review uploaded files, export data to Excel, and manage admin accounts.",
      "painPoints": [
        "Tracking pending, accepted, and rejected internship applications manually",
        "Exporting applicant cohorts and maintaining up-to-date portal announcements"
      ],
      "goals": [
        "Monitor real-time application counts and act on submissions directly from a table",
        "Export applicant rosters to Excel and provision secondary administrator accounts"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The architecture separates the platform into three role-based zones: a pre-login public portal for program discovery and account onboarding, an authenticated applicant workspace for profile updates and multi-step applications, and a sidebar-driven admin dashboard for applicant verification.",
    "nodes": [
      {
        "section": "Before Login (Public Portal)",
        "screens": [
          "Masuk Akun (Login)",
          "Registrasi Akun (Register)",
          "Beranda (Landing & 4-Step Alur)",
          "Info Pendaftaran (Announcement & 6-Step Guide)",
          "Info Magang (Profil, Bidang & Pelayanan TPDK)"
        ]
      },
      {
        "section": "After Login (Applicant Portal)",
        "screens": [
          "Beranda (Authenticated)",
          "Info Pendaftaran (Authenticated Guide)",
          "Profile (Personal, Education & Advisor Data)",
          "Form Pendaftaran Step 1/2 & Step 2/2",
          "Status Lamaran Magang (Notif)"
        ]
      },
      {
        "section": "Dashboard Admin (Staff Portal)",
        "screens": [
          "Beranda (KPI Cards & Data Pendaftar Table)",
          "Data Pelamar Magang (Full Table & Excel Export)",
          "Upload Foto (Information Publishing)",
          "Data Admin & Tambah Admin Modal"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "Prospective interns enter through the public landing page, review registration guidelines, create an account with academic documents, and authenticate into the applicant portal. From there, they complete a two-step application form, upload supporting files, and monitor real-time acceptance notifications.",
    "steps": [
      {
        "step": "01",
        "title": "Public Program Discovery",
        "description": "Visitors explore the Disdukcapil Kota Semarang overview, 4-step registration roadmap, division tabs, and 6-step guide.",
        "screenOrAction": "Before Login: Beranda & Info Magang"
      },
      {
        "step": "02",
        "title": "Account Registration & Sign-In",
        "description": "Applicants register with identity, university, photo, CV, and transcript uploads, then sign in via split-screen login.",
        "screenOrAction": "Registrasi Akun -> Masuk Akun"
      },
      {
        "step": "03",
        "title": "Profile & Multi-Step Application",
        "description": "Signed-in users verify profile details, confirm branch placement willingness (Step 1/2), and upload recommendation and CV files (Step 2/2).",
        "screenOrAction": "Profile -> Form Pendaftaran 1/2 & 2/2"
      },
      {
        "step": "04",
        "title": "Status Tracking & Admin Review",
        "description": "Admins review applicant tables, approve or reject entries, or export Excel reports while students check acceptance notifications.",
        "screenOrAction": "Dashboard Admin <-> Status Lamaran Magang"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Before Login — Public Portal, Institutional Tabs & Registration Flow",
      "imageUrl": "/images/projects/prajagamer_website_uiux_design/image01.webp"
    },
    {
      "title": "After Login — Applicant Profile, Two-Step Application Form & Status Notifications",
      "imageUrl": "/images/projects/prajagamer_website_uiux_design/image02.webp"
    },
    {
      "title": "Dashboard Admin — KPI Summary, Applicant Data Table, Media Upload & Admin Modal",
      "imageUrl": "/images/projects/prajagamer_website_uiux_design/image03.webp"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Disdukcapil Crimson",
        "hex": "#DC2626",
        "role": "Primary",
        "usage": "Admin sidebar background, primary CTA buttons, and active navigation highlights"
      },
      {
        "name": "Terracotta Banner Red",
        "hex": "#C84441",
        "role": "Brand Accent",
        "usage": "Public portal hero headers, footer callout banners, and promotional section dividers"
      },
      {
        "name": "Deep Maroon Accent",
        "hex": "#7D282E",
        "role": "Dark Accent",
        "usage": "Active sidebar states, overlay contrast layers, and secondary crimson emphasis"
      },
      {
        "name": "Pure Canvas White",
        "hex": "#FFFFFF",
        "role": "Surface",
        "usage": "Form containers, profile cards, data tables, and public landing page sections"
      },
      {
        "name": "Admin Cool Gray",
        "hex": "#F3F5F7",
        "role": "Background",
        "usage": "Dashboard Admin workspace backdrop separating white KPI cards and tables"
      },
      {
        "name": "Charcoal Ink",
        "hex": "#2A2A2A",
        "role": "Neutral Text",
        "usage": "Primary headings, form labels, and table cell typography"
      }
    ],
    "typography": [
      {
        "name": "Hero & Banner Display",
        "role": "Heading",
        "font": "Sans-Serif Display",
        "sizeWeight": "Bold",
        "usage": "Main portal hero titles and section headers across Beranda and Info Pendaftaran"
      },
      {
        "name": "Section & Card Title",
        "role": "Subheading",
        "font": "Sans-Serif UI",
        "sizeWeight": "SemiBold",
        "usage": "Card titles, form section dividers, and admin table headers"
      },
      {
        "name": "Body & Form Copy",
        "role": "Body",
        "font": "Sans-Serif UI",
        "sizeWeight": "Regular",
        "usage": "Institutional descriptions, step-by-step instructions, and input placeholders"
      },
      {
        "name": "Navigation & Action Label",
        "role": "Label",
        "font": "Sans-Serif UI",
        "sizeWeight": "Medium",
        "usage": "Top navbar links, sidebar items, tab triggers, and button text"
      }
    ],
    "componentStates": [
      {
        "component": "Primary Crimson Action Button",
        "states": [
          "Default",
          "Hover",
          "Active"
        ],
        "notes": "High-contrast white text on crimson fill used for Daftar Magang, Masuk, Selanjutnya, and Update Profile CTAs"
      },
      {
        "component": "Institutional Category Tabs",
        "states": [
          "Default",
          "Active"
        ],
        "notes": "Three-tab switcher (PROFIL, BIDANG, PELAYANAN TPDK) paired with a vertical division sidebar (PIAK, DAFDUK, SEKRETARIAT, PDIP)"
      },
      {
        "component": "Admin Sidebar & Modal Overlay",
        "states": [
          "Default",
          "Active",
          "Modal Open"
        ],
        "notes": "Fixed crimson sidebar navigation and dimmed backdrop overlay for the Tambah Admin creation dialog"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "susScore": "Not Formally Measured",
    "taskSuccessRate": "Not Formally Measured",
    "timeOnTask": "Not Formally Measured",
    "iterations": [
      {
        "usabilityIssue": "Long single-page registration and application inputs risked overwhelming student applicants.",
        "iterationSolution": "Structured post-login application submission into a two-step form (1/2 personal & placement consent, 2/2 document uploads) with a clear progress label.",
        "impact": "Improves visual scanning and separates identity confirmation from file attachment tasks."
      },
      {
        "usabilityIssue": "First-time visitors needed clearer guidance on Disdukcapil divisions and registration flow before creating an account.",
        "iterationSolution": "Added an illustrated 4-step roadmap on Beranda, a 6-step guide on Info Pendaftaran, and tabbed BIDANG/PELAYANAN TPDK views.",
        "impact": "Provides transparent pre-login expectations and reduces ambiguity around internship placement divisions."
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "Exported High-Fidelity Figma Showcase Archive",
    "totalFrames": 18,
    "componentsCount": 24,
    "handoffSpecs": "18 desktop high-fidelity frames organized across Before Login (7), After Login (7), and Dashboard Admin (4) rows in Figma, exported as WebP boards."
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "Role Based Desktop Grid",
    "designTokens": "Crimson White Color Tokens",
    "typography": "Clean Sans Serif Hierarchy",
    "prototypeFidelity": "High Fidelity Static Screens"
  }
}
```
