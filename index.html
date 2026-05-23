import { useState } from "react";

// ─── DATA ────────────────────────────────────────────────────────────────────

const MODULES = [
  {
    id: "money", icon: "💵", label: "Build Income",
    title: "$0 → $10,000", sub: "In 2 Months",
    grad: ["#00C896", "#00A878"],
    steps: [
      {
        title: "Stack Your First $500",
        phase: "Week 1–2 · Foundation",
        items: [
          "Sign up for TaskRabbit, Thumbtack, and Craigslist gigs — no background check required for most.",
          "Offer same-day labor: moving help, yard work, junk removal, cleaning. Charge $15–$25/hr cash.",
          "Flip free items from the Craigslist FREE section on Facebook Marketplace or OfferUp same day.",
          "Sell plasma at BioLife or CSL Plasma (up to $400/month). Bring ID and proof of address.",
          "Download Roadie or GoShare for same-day delivery gigs.",
          "Daily goal: $50–$100/day. Track every dollar in your notes app.",
        ],
      },
      {
        title: "Stop Trading Time, Start Building Income",
        phase: "Week 3–4 · Scale to $2,000",
        items: [
          "Open a Cash App or Chime account to collect digital payments — this builds a financial record.",
          "Offer package deals: 'Full yard cleanup + haul away' for $150–$200. Post on Nextdoor.",
          "Start reselling: buy underpriced electronics on Facebook Marketplace, resell on eBay for 30–50% profit.",
          "Recruit one friend — coordinate jobs, split profit 60/40 (you keep 60 for coordinating).",
          "List skills: painting, cooking, auto detailing, childcare — these pay $20–$40/hr cash.",
          "Target: $500/week by end of Week 4.",
        ],
      },
      {
        title: "Build a Micro-Business",
        phase: "Month 2 · Push to $10,000",
        items: [
          "Register a sole proprietorship or LLC (many states allow felons — costs $50–$150).",
          "Offer recurring services: weekly lawn care, bi-weekly cleaning, monthly junk removal.",
          "Use $2,000 as seed capital: buy supplies in bulk (cleaning products, lawn equipment at pawn shops).",
          "Get on Angi (formerly Angie's List) as a service provider.",
          "Hire 1–2 helpers on TaskRabbit, manage and invoice clients at a markup.",
          "Invoice clients via Wave (free) — looks professional and tracks income for future banking.",
          "Milestone: 10 recurring clients at $200/month = $2,000 recurring + active hustle = $10K by Day 60.",
        ],
      },
      {
        title: "Keep What You Earn",
        phase: "Ongoing · Protection & Mindset",
        items: [
          "Never carry large amounts of cash. Deposit into Chime or Cash App daily.",
          "Track every expense. Dave Ramsey's 'Baby Steps' framework works well here.",
          "Avoid lifestyle creep — when you hit $5K, do not upgrade your lifestyle yet.",
          "Save 20% of every dollar earned in a separate account. This becomes your credit-building fund.",
          "Surround yourself with earners. Leave negativity behind — your circle determines your ceiling.",
        ],
      },
    ],
  },
  {
    id: "credit", icon: "📈", label: "Build Credit",
    title: "500 → 800", sub: "In 5 Months",
    grad: ["#4F8EF7", "#2563EB"],
    steps: [
      {
        title: "Get in the Game",
        phase: "Month 1 · Foundation",
        items: [
          "Pull your free credit report at AnnualCreditReport.com — know every negative item.",
          "Open a Chime or Current account (no ChexSystems check required).",
          "Apply for the OpenSky Visa secured card ($200 deposit, no credit check, no bank account required).",
          "Apply for a Credit Builder Loan at Self.inc ($25/month — reports to all 3 bureaus).",
          "Dispute any errors on your report via Experian, Equifax, and TransUnion online portals.",
          "Goal: 2 active accounts reporting by end of Month 1.",
        ],
      },
      {
        title: "Stack Positive History",
        phase: "Months 2–3 · Build Momentum",
        items: [
          "Pay every bill on time — payment history is 35% of your score. Set autopay.",
          "Keep your OpenSky card utilization under 10% (spend $20, pay full balance monthly).",
          "Ask a trusted person to add you as an Authorized User on their good-standing card.",
          "Apply for the Discover it Secured card (converts to unsecured after 7 months).",
          "Use Experian Boost — connects utility and streaming payments to your credit file (free).",
          "Monitor your score weekly on Credit Karma (free).",
        ],
      },
      {
        title: "Hit 700, Then 800",
        phase: "Months 4–5 · Accelerate",
        items: [
          "By Month 4, your Self.inc loan balance reports positively — score jumps 40–60 points.",
          "Apply for a credit union secured loan — local credit unions are felon-friendly.",
          "Request a credit limit increase on your OpenSky card (keeps utilization low, boosts score).",
          "Dispute remaining collections using the '609 dispute letter' method (search for a free template).",
          "Open a second credit builder account at Digital Federal Credit Union (DCU).",
          "Paying 2 cards + 1 loan on time for 5 months puts most people in the 780–820 range.",
        ],
      },
    ],
  },
  {
    id: "housing", icon: "🏠", label: "Find Housing",
    title: "Homeless → Renting", sub: "In 3 Months",
    grad: ["#FF8C42", "#F97316"],
    steps: [
      {
        title: "Get Safe and Stable",
        phase: "Week 1–2 · Immediate Shelter",
        items: [
          "Call 211 immediately — this connects you to all local housing resources, shelters, and assistance.",
          "Apply to reentry-specific housing: Volunteers of America, Salvation Army, and Catholic Charities accept felons.",
          "Search 'reentry housing [your city]' — most cities have dedicated transitional housing programs.",
          "Apply for emergency housing vouchers through your local Housing Authority.",
          "Contact your parole or probation officer — they often have housing referrals and are required to assist.",
          "Apply for SNAP (food stamps) and Medicaid immediately — this frees up cash for housing deposits.",
        ],
      },
      {
        title: "Build Your Rental Profile",
        phase: "Months 1–2 · Become an Attractive Tenant",
        items: [
          "Get your state ID or driver's license — this is critical for renting.",
          "Open a Chime bank account (no check required). Deposit income here to show financial history.",
          "Save $1,000–$1,500 for first and last month's rent plus a security deposit.",
          "Get a letter of recommendation from an employer, parole officer, pastor, or mentor.",
          "Be honest on applications — dishonesty is more disqualifying than the felony itself.",
          "Focus on private landlords rather than property management companies — they have more flexibility.",
        ],
      },
      {
        title: "Sign Your Lease",
        phase: "Month 3 · Find Felon-Friendly Rentals",
        items: [
          "Search FelonFriendlyApartments.com and FelonFriendly.com.",
          "Post in Facebook Housing Groups in your city: 'Looking for rental, have income, references available.'",
          "Contact local Section 8 housing — not all programs disqualify for felonies (depends on crime type).",
          "Try room rentals on SpareRoom.com or Roomies.com — lower barrier than full apartments.",
          "Offer 2 months upfront if the landlord is hesitant. Skin in the game builds trust.",
          "Once approved, protect that lease. Pay on time. This is your new foundation.",
        ],
      },
    ],
  },
  {
    id: "homeown", icon: "🏡", label: "Own a Home",
    title: "Own Your First Home", sub: "In 1 Year",
    grad: ["#A855F7", "#7C3AED"],
    steps: [
      {
        title: "Build the Foundation",
        phase: "Months 1–3 · Prepare",
        items: [
          "Get your credit score to 620+ minimum (580 qualifies for FHA loans). Follow the credit module.",
          "Save 3.5% for an FHA down payment (on a $150K home that is $5,250).",
          "Maintain steady income — lenders want 2 years of employment history or strong self-employment records.",
          "Felons CAN get FHA loans. There is no blanket ban. Only certain drug-related crimes involving federal housing may restrict eligibility.",
          "Connect with a HUD-approved housing counselor (free at HUD.gov/housingcounseling).",
        ],
      },
      {
        title: "Get Mortgage-Ready",
        phase: "Months 4–8 · Qualify",
        items: [
          "Apply at local credit unions — they underwrite manually and are more felon-friendly than big banks.",
          "Look into USDA loans (rural areas, 0% down, felon-eligible).",
          "Get pre-approved: a pre-approval letter shows sellers you are serious and gives you negotiating power.",
          "Keep your debt-to-income ratio under 43% (total monthly debts divided by gross income).",
          "Do not open new credit cards or loans during this process.",
        ],
      },
      {
        title: "Close on Your Home",
        phase: "Months 9–12 · Buy",
        items: [
          "Work with a buyer's agent — their service is free for buyers, the seller pays their commission.",
          "Look at HUD homes (foreclosures sold below market value, felon-eligible).",
          "Check Habitat for Humanity — they actively work with people who are rebuilding their lives.",
          "Negotiate closing costs into the loan or ask the seller to cover them.",
          "Once closed: you are a homeowner. This is generational wealth. Protect it.",
        ],
      },
    ],
  },
  {
    id: "jobs", icon: "💼", label: "Get a Job",
    title: "Jobs Hiring Today", sub: "Felon-Friendly Employers",
    grad: ["#06B6D4", "#0284C7"],
    steps: [
      {
        title: "Day Labor & Temp Agencies",
        phase: "Start Today · No Experience Required",
        items: [
          "Labor Finders — day labor and temp staffing, felon-friendly, same-day pay. Find locations at LaborFinders.com.",
          "Robert Half — temp and contract work in office, finance, and tech. Known for working with diverse backgrounds.",
          "Labor Ready (TrueBlue) — industrial, construction, and warehouse day labor. Walk in same day at TrueBlue.com.",
          "Staffmark — light industrial, warehouse, and manufacturing temp work. Background check is flexible.",
          "Manpower — temp-to-hire in multiple industries. Offices in most cities. Felon-friendly intake process.",
          "Adecco — one of the largest staffing firms. Office, warehouse, and industrial placements. Case-by-case review.",
          "Kelly Services — administrative, industrial, and science temp work. Known for inclusive hiring policies.",
          "Express Employment Professionals — local franchise offices, strong felon-friendly reputation.",
        ],
      },
      {
        title: "Major Employers Hiring Now",
        phase: "Ban the Box · Fair Chance Companies",
        items: [
          "McDonald's, Burger King, and Wendy's — food service, immediate hire, flexible hours.",
          "Amazon Warehouses — case-by-case review, thousands of openings daily at Amazon.jobs.",
          "Walmart and Sam's Club — distribution centers and retail, felon-friendly policy.",
          "Chipotle and Domino's — food service chains with inclusive hiring programs.",
          "Uber and Lyft — check your state. Many allow felons depending on crime type and age of conviction.",
          "DoorDash and Instacart — delivery gigs with some background check flexibility.",
          "Home Depot and Lowe's — retail and distribution, strong fair-chance hiring programs.",
        ],
      },
      {
        title: "Where to Search Right Now",
        phase: "Job Boards · Online Platforms",
        items: [
          "70MillionJobs.com — the only job board built exclusively for people with criminal records.",
          "Honest Jobs at honestjobs.com — felon-specific job board with verified employers.",
          "Indeed.com — search 'felon friendly' or 'fair chance' in your city.",
          "ReentryNet.org and Relaunch Pad — reentry-focused employment resources.",
          "GoodwillIndustries.org — career centers that actively serve returning citizens.",
          "CareerOneStop.org — your local American Job Center provides free job placement services.",
        ],
      },
      {
        title: "High-Paying Trade Certifications",
        phase: "6–12 Months · Career-Level Income",
        items: [
          "CDL (Commercial Driver's License) — most states allow felons. Earns $55K–$90K/year. Pell Grant covers classes.",
          "HVAC Certification — $50K–$80K/year. Many community colleges accept felons and offer financial aid.",
          "Electrical Apprenticeship — IBEW locals accept felons on a case-by-case basis. Earn while you learn.",
          "Welding Certification — $45K–$70K/year, high demand, and very felon-friendly field.",
          "Plumbing Apprenticeship — UA union accepts returning citizens in many states.",
          "Roofing and Construction — high demand, immediate hire, strong felon-friendly culture.",
        ],
      },
    ],
  },
  {
    id: "classes", icon: "🎓", label: "Free Training",
    title: "Local Classes & Skills", sub: "Career Training Near You",
    grad: ["#10B981", "#059669"],
    steps: [
      {
        title: "IT & Technology Courses",
        phase: "Free & Low-Cost · Remote or In-Person",
        items: [
          "Google Career Certificates (grow.google/certificates) — IT Support, Data Analytics, Cybersecurity. Free via Coursera with financial aid.",
          "CompTIA A+, Network+, Security+ certifications — industry standard, $100–$350 exam fee. Use free Professsor Messer study guides.",
          "Per Scholas (perscholas.org) — free IT training for underserved adults including returning citizens. Locations in 20+ cities.",
          "NPower (npower.org) — free technology training and job placement for people facing barriers. Multiple US cities.",
          "Goodwill Digital Career Accelerator — free online tech skills courses through Goodwill Industries.",
          "Microsoft LEAP — paid apprenticeship program that accepts people with nontraditional backgrounds.",
          "Search '[your city] free IT training reentry' — many cities fund tech programs specifically for returning citizens.",
        ],
      },
      {
        title: "Culinary & Food Service",
        phase: "Hands-On Training · Quick Employment",
        items: [
          "Café Momentum (cafemomentum.org) — culinary training program for justice-involved youth and young adults.",
          "Homeboy Industries (homeboyindustries.org) — culinary training and social enterprise in Los Angeles, with national programs.",
          "Local community college culinary programs — most have felon-friendly admissions. Costs covered by Pell Grant.",
          "ServSafe Food Handler Certification — required for most food jobs. $15 online course at ServSafe.com.",
          "Search 'culinary workforce training [your city]' — workforce boards fund these programs in most cities.",
          "Restaurant associate training programs — McDonald's, Yum Brands (Taco Bell, KFC), and Darden all offer paid training.",
        ],
      },
      {
        title: "Construction & Skilled Trades",
        phase: "Union & Non-Union · Apprenticeships",
        items: [
          "Job Corps (jobcorps.gov) — free residential training program including construction trades. Accepts felons on a case-by-case basis.",
          "Helmets to Hardhats (helmetstohardhats.org) — construction apprenticeship placement. Open to civilians with workforce barriers.",
          "SkillsUSA and local union halls — many carpenters, electricians, and plumbers unions accept people with records.",
          "Home Builders Institute (HBI) — construction pre-apprenticeship training. Partners with reentry programs.",
          "YouthBuild (youthbuild.org) — construction training and GED for young adults. Locations nationwide.",
          "Search 'pre-apprenticeship construction [your city]' — most cities have DOL-funded programs.",
        ],
      },
      {
        title: "Other Career Pathways",
        phase: "Healthcare · Business · Creative",
        items: [
          "CNA (Certified Nursing Assistant) — many states allow felons. 4–6 week course, $500–$1,500, earns $30K–$45K/year.",
          "Barbering and Cosmetology — most states license returning citizens. 1,000–1,500 hours of state-accredited school.",
          "WIOA-Funded Training (careeronestop.org) — federal workforce funding covers tuition for approved programs. No income required.",
          "Microsoft Office and Google Suite certifications — free online via Microsoft Learn and Google Skillshop. Boosts any resume.",
          "Trucking schools (CDL) — 3–8 week programs, often $3,000–$7,000 covered by WIOA or Pell Grant.",
          "Real estate licensing — most states allow felons to get licensed. 63–150 hours of coursework.",
        ],
      },
    ],
  },
  {
    id: "financial", icon: "🆘", label: "Emergency Help",
    title: "Same-Day Assistance", sub: "No Bank, No Job, No Credit",
    grad: ["#F59E0B", "#D97706"],
    steps: [
      {
        title: "Get Money Today",
        phase: "Immediate · Cash Assistance",
        items: [
          "Call 211 — connects you to every emergency financial assistance program in your county. Available 24/7.",
          "Salvation Army emergency assistance — food, utilities, and rent. Walk in or call your local chapter.",
          "Catholic Charities — assists anyone regardless of faith. No background check for emergency help.",
          "Community Action Agencies — federally funded, serve low-income individuals, no credit check required.",
          "LIHEAP — federally funded utility assistance. No credit, no job, and no bank account required.",
          "Local churches and food banks — many also provide gas cards, clothing, and small cash grants.",
        ],
      },
      {
        title: "Emergency Loans Without Credit",
        phase: "Same Day · Borrow Without a Bank",
        items: [
          "Credit Union Payday Alternative Loans (PAL) — up to $1,000, low interest, available to members.",
          "Oportun.com — personal loans for individuals with no credit. No Social Security number required in some states.",
          "OppLoans (OppFi) — accepts bad credit and no credit, with same-day funding available.",
          "NetCredit.com — considers more than just your credit score. Felon-friendly in most states.",
          "Pawn shops — immediate cash using electronics or jewelry as collateral.",
          "Cash App Borrow — small loans from $20–$200 with no credit check, available inside the Cash App.",
        ],
      },
      {
        title: "Government Benefits You Qualify For",
        phase: "Apply Now · Claim What Is Yours",
        items: [
          "SNAP (Food Stamps) — drug felonies no longer disqualify in most states. Apply at Benefits.gov.",
          "Medicaid — healthcare coverage available immediately after release in most expansion states.",
          "SSI and SSDI — if you have a disability, apply at SSA.gov. Prior incarceration does not disqualify you.",
          "Pell Grant — federal education grant. Drug convictions no longer disqualify as of 2021.",
          "TANF (Temporary Assistance for Needy Families) — cash assistance for parents with children.",
          "Second Chance Pell — college education grants specifically for incarcerated and recently released individuals.",
        ],
      },
    ],
  },
  {
    id: "college", icon: "🏛️", label: "Go to College",
    title: "Get Into College", sub: "As a Felon",
    grad: ["#3B82F6", "#1D4ED8"],
    steps: [
      {
        title: "Know Your Options",
        phase: "Step 1 · Eligibility & Research",
        items: [
          "Most colleges can accept felons — it is not automatic disqualification. Each school decides independently.",
          "Community colleges have the most open admissions policies. Start there as your anchor.",
          "File your FAFSA at StudentAid.gov — drug convictions no longer disqualify you for Pell Grants (2021 law).",
          "Look for reentry-specific college programs: College and Community Fellowship, Bard Prison Initiative alumni networks.",
          "HBCUs and community colleges tend to be the most welcoming to returning citizens.",
        ],
      },
      {
        title: "How to Present Your Record",
        phase: "Step 2 · The Application",
        items: [
          "Be honest — dishonesty is more disqualifying than the felony in most admissions offices.",
          "Write a personal statement addressing your conviction: show growth, accountability, and a clear vision for your future.",
          "Get 2 letters of recommendation from a pastor, mentor, employer, parole officer, or community leader.",
          "Apply to 3–5 schools. Start with community college as your anchor institution.",
          "Contact admissions offices directly and ask about their policy before you apply.",
          "Mention any programs, education, or positive changes that occurred during your incarceration.",
        ],
      },
      {
        title: "Fund Your Education",
        phase: "Step 3 · College for Free or Near-Free",
        items: [
          "Pell Grant covers up to $7,395 per year — apply at FAFSA.gov.",
          "Second Chance Pell (expanded in 2023) — for people who are incarcerated or recently released.",
          "Scholarships for returning citizens: the Center for Law and Social Policy, Dave's Killer Bread Foundation.",
          "AmeriCorps education award — volunteer 10–12 months and earn a $7,000+ education voucher.",
          "GI Bill — if you served, education benefits are not stripped by a felony conviction.",
          "WIOA funding (careeronestop.org) — covers tuition for approved programs including college courses.",
        ],
      },
    ],
  },
  {
    id: "rights", icon: "⚖️", label: "Know Your Rights",
    title: "Rights & Sovereignty", sub: "Know Your Power",
    grad: ["#EF4444", "#DC2626"],
    steps: [
      {
        title: "Get Your Rights Back Legally",
        phase: "Restoration · Official Channels",
        items: [
          "Apply for a Presidential Pardon or Governor's Pardon — restores federal and state rights respectively.",
          "Many states allow expungement or record sealing after a waiting period. Search '[your state] expungement eligibility'.",
          "Voting rights: 37 states automatically restore voting rights after release. Some require a formal application.",
          "Second Amendment rights can be restored via pardon, expungement, or state-specific petitions.",
          "Apply for a Certificate of Relief or Certificate of Good Conduct in your state — reduces employment and housing barriers.",
        ],
      },
      {
        title: "You Still Have Rights",
        phase: "Constitutional · Know the Law",
        items: [
          "4th Amendment: You cannot be searched without a warrant or probable cause — even on probation, there are limits.",
          "5th Amendment: You do not have to incriminate yourself. Remain silent. Always.",
          "14th Amendment: Equal protection under the law applies to you.",
          "You can submit FOIA requests to obtain your own criminal records from any federal agency.",
          "File complaints about rights violations with the ACLU or the National Legal Aid and Defender Association.",
        ],
      },
      {
        title: "Own Your Economic Identity",
        phase: "Financial Sovereignty · Build Your Foundation",
        items: [
          "Form an LLC — separates your personal and business finances. Most states allow felons to form one.",
          "Get an EIN (Employer Identification Number) from IRS.gov — free, instant, no background check.",
          "Open a business bank account in your LLC name. Mercury Bank and Relay Bank are felon-friendly.",
          "Learn about living trusts — they allow you to hold assets outside your personal name.",
          "Study the Uniform Commercial Code (UCC) — understanding contract law gives you real power in commerce.",
          "Important: 'Sovereign Citizen' legal theories are not recognized by courts and can result in serious legal trouble. Focus only on lawful strategies.",
        ],
      },
    ],
  },
  {
    id: "social", icon: "🤝", label: "Build Your Circle",
    title: "Make New Friends", sub: "Build Your Circle",
    grad: ["#8B5CF6", "#7C3AED"],
    steps: [
      {
        title: "Best Places to Meet Quality People",
        phase: "Where to Go · Real Environments",
        items: [
          "Church and faith communities — non-judgmental, community-oriented, and often have dedicated reentry ministries.",
          "Gym and fitness centers — shared discipline creates natural conversations with goal-oriented people.",
          "AA and NA meetings — even if you are not struggling with addiction, these are communities of people actively rebuilding.",
          "Volunteer events — Habitat for Humanity, food banks, and park cleanups attract quality-minded people.",
          "Community college classes — diverse, ambitious, and open-minded people in a structured environment.",
          "Co-working spaces — entrepreneurs and motivated professionals who respect hustle.",
          "Meetup.com — find local groups around hiking, cooking, chess, photography, and coding.",
        ],
      },
      {
        title: "Scripts That Actually Work",
        phase: "What to Say · Real Conversations",
        items: [
          "At the gym: 'Hey, how long have you been coming here? I just started getting consistent — any tips?'",
          "At church: 'This is a great community. Have you been coming here long? What do you like most about it?'",
          "Volunteering: 'What made you decide to volunteer here today?' — people love talking about their reasons.",
          "General opener: 'I am working on building something new in my life. I am [name], good to meet you.'",
          "Ask questions and listen. Most people love talking about themselves. Be genuinely curious.",
          "Find common ground: 'You from around here? What do you do when you are not here?'",
        ],
      },
      {
        title: "Protect Your Energy and Reputation",
        phase: "What NOT to Say · Guard Your Character",
        items: [
          "Do not lead with your record in a first meeting. Build trust and familiarity first.",
          "Do not complain or talk negatively about police or courts in early conversations.",
          "Do not talk about money struggles or ask to borrow money from new acquaintances.",
          "Do not overshare. Mystery is attractive. Let people ask questions about you.",
          "Do not disappear after a first meeting. Follow up: 'Great meeting you. Want to grab coffee this week?'",
          "Be present, positive, and genuinely interested in others. That alone makes you memorable.",
        ],
      },
    ],
  },
  {
    id: "relationship", icon: "❤️", label: "Find a Partner",
    title: "Finding a Partner", sub: "Confidence & Connection",
    grad: ["#EC4899", "#BE185D"],
    steps: [
      {
        title: "Build Yourself First",
        phase: "Foundation · Attraction Starts Inside",
        items: [
          "Before pursuing a relationship, build your purpose. People are attracted to direction and momentum.",
          "Work on your physical health — gym, diet, and sleep. Confidence is a physical state.",
          "Dress with intention: clean, fitted, and deliberate. You do not need money, you need presentation.",
          "Know your story — where you have been, where you are going. Be proud of your comeback.",
          "A person with vision, discipline, and warmth is magnetic. Become that person first.",
        ],
      },
      {
        title: "Real Places, Real Connections",
        phase: "Where to Meet · Quality Over Quantity",
        items: [
          "Church, community events, and volunteering — people there value substance over status.",
          "Classes (cooking, fitness, and art) — shared activity creates natural, low-pressure conversation.",
          "Through friends and social circles — warm introductions are the most effective approach.",
          "Apps: Bumble (women initiate), Hinge (relationship-focused), and OkCupid.",
          "Your workplace or school — organic relationships built on shared time and goals.",
        ],
      },
      {
        title: "Be Real, Be Confident",
        phase: "Approach & Disclosure · Honesty Wins",
        items: [
          "Approach directly: 'I wanted to introduce myself. I am [name]. I noticed you and wanted to say hello.'",
          "Ask for her opinion or perspective — not just her number. Build interest before asking for contact.",
          "Be honest about your past before things get serious — the third to fifth date is the right time.",
          "Frame it as growth, not shame: 'I went through a serious chapter in my life. I made mistakes and I have grown. I am building something real now.'",
          "A woman worth having will respect honesty and growth. One who does not is not the right person.",
          "Consistency, reliability, and presence are what keep a strong relationship together.",
        ],
      },
    ],
  },
  {
    id: "nova", icon: "📍", label: "NoVA Resources",
    title: "Fairfax County & NoVA", sub: "Local Reentry Resources",
    grad: ["#F97316", "#C2410C"],
    steps: [
      {
        title: "OAR NOVA — Start Here First",
        phase: "Top Priority · Best Match for Reentry",
        items: [
          "OAR NOVA (Offender Aid and Restoration of Northern Virginia) is your #1 first call in Fairfax County.",
          "Services: employment help (resumes, job referrals, uniforms and tools), emergency food, clothing, rent and utility assistance, housing referrals, counseling, and life skills workshops.",
          "Also offers: driver's license restoration workshops, family support, and mentoring.",
          "Address: 10700 Page Ave., Suite 200, Fairfax, VA 22030 (near Tysons area).",
          "Phone: (703) 246-3033 — call to schedule intake.",
          "Email: info@oarnova.org | Website: oarnova.org",
          "Serves Fairfax, Loudoun, and Prince William counties. Assists both pre- and post-release individuals.",
        ],
      },
      {
        title: "Fairfax County Coordinated Services Planning (CSP)",
        phase: "One-Stop Connection · All County Resources",
        items: [
          "CSP is the central hub that connects you to every county resource in one call — explain your full situation honestly.",
          "Resources available: emergency shelter, food, clothing, healthcare, employment, financial aid, rent help, and ID assistance.",
          "Phone: 703-222-0880 (TTY 711) — Monday through Friday, 8:00 AM to 4:30 PM.",
          "Multilingual support is available.",
          "Call today — tell them you are homeless, have a felony record, and need immediate stabilization. They are designed for exactly this situation.",
        ],
      },
      {
        title: "Additional Fairfax & NoVA Contacts",
        phase: "Support Network · Know Every Option",
        items: [
          "Virginia 211: Dial 211 any time, 24 hours a day, 7 days a week — immediate referrals to shelter, food, addiction help, and reentry services.",
          "Fairfax County Sheriff's Office – Reentry Programs: 703-246-3227 or sheriff@fairfaxcounty.gov | 4110 Chain Bridge Road, Fairfax, VA 22030. Coordinates reentry even if you are not currently incarcerated.",
          "Fairfax County Community Services Board (CSB): Mental health, substance abuse treatment, and some reentry support. Main line: 703-383-8500.",
          "Virginia Career Works – Annandale/Fairfax: Free job help for the reentry population. Phone: 703-533-5400 | 7611 Little River Turnpike, Annandale, VA.",
        ],
      },
      {
        title: "Your Quick Action Plan — Tysons/Fairfax",
        phase: "Do This Today · Step by Step",
        items: [
          "Step 1 — Call CSP right now: 703-222-0880. Be fully honest: homeless, no ID, felony record, addiction or ADHD. The more they know, the better they can help.",
          "Step 2 — Contact OAR NOVA next: (703) 246-3033. Ask specifically for reentry case management and employment assistance.",
          "Step 3 — Use a Tysons-area library for free computers and WiFi to follow up via email and print any documents you need.",
          "Step 4 — Ask every agency specifically about: ID replacement (birth certificate and Social Security card), food and clothing vouchers, rapid rehousing, recovery programs, and work programs that do not require immediate background check clearance.",
          "Step 5 — Ask about transportation assistance. Many of these programs offer bus passes or transit help to get you to appointments.",
          "These programs are built for your exact situation. Go today. Be honest. Take notes on every name and number they give you.",
        ],
      },
    ],
  },
];

const AFFIRMATIONS = [
  { quote: "The impediment to action advances action. What stands in the way becomes the way.", author: "Marcus Aurelius" },
  { quote: "You have power over your mind, not outside events. Realize this, and you will find strength.", author: "Marcus Aurelius" },
  { quote: "Difficulties strengthen the mind, as labor does the body.", author: "Seneca" },
  { quote: "It is not what happens to you, but how you react to it that matters.", author: "Epictetus" },
  { quote: "Your past does not define your future. Your next move does.", author: "Rock Bottom 2 Relentless" },
  { quote: "The system counted you out. Prove them wrong — quietly, powerfully.", author: "Rock Bottom 2 Relentless" },
  { quote: "You are not your record. You are your choices from this day forward.", author: "Rock Bottom 2 Relentless" },
  { quote: "The comeback is always greater than the setback.", author: "Rock Bottom 2 Relentless" },
];

// ─── COMPONENT ───────────────────────────────────────────────────────────────

export default function App() {
  const [screen, setScreen] = useState("home"); // home | module | step
  const [activeModule, setActiveModule] = useState(null);
  const [activeStep, setActiveStep] = useState(null);
  const [affirmIdx, setAffirmIdx] = useState(0);
  const [checked, setChecked] = useState({});
  const [aiQ, setAiQ] = useState("");
  const [aiA, setAiA] = useState("");
  const [aiLoading, setAiLoading] = useState(false);
  const [tab, setTab] = useState("home"); // home | search | progress | ask

  const mod = MODULES.find(m => m.id === activeModule);
  const step = mod && activeStep !== null ? mod.steps[activeStep] : null;

  const toggleCheck = (key) => setChecked(p => ({ ...p, [key]: !p[key] }));

  const progress = (modId) => {
    const m = MODULES.find(x => x.id === modId);
    if (!m) return 0;
    const total = m.steps.reduce((a, s) => a + s.items.length, 0);
    const done = m.steps.reduce((a, s, si) =>
      a + s.items.filter((_, ii) => checked[`${modId}-${si}-${ii}`]).length, 0);
    return total ? Math.round((done / total) * 100) : 0;
  };

  const askAI = async () => {
    if (!aiQ.trim()) return;
    setAiLoading(true); setAiA("");
    try {
      const res = await fetch("https://api.anthropic.com/v1/messages", {
        method: "POST",
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify({
          model: "claude-sonnet-4-20250514",
          max_tokens: 1000,
          system: `You are a compassionate, direct life coach for people with felony records in the United States. Give practical, legal, actionable advice. Be encouraging, specific, and never judgmental. Keep responses clear and concise — this is a mobile app.`,
          messages: [{ role: "user", content: aiQ }],
        }),
      });
      const data = await res.json();
      setAiA(data.content?.map(b => b.text || "").join("\n") || "Please try again.");
    } catch { setAiA("Connection issue. Please try again in a moment."); }
    setAiLoading(false);
  };

  // ── SCREENS ──

  const renderHome = () => (
    <div style={s.screen}>
      {/* Hero */}
      <div style={s.hero}>
        <div style={s.heroGlow} />
        <div style={s.logoRow}>
          <div style={s.logoMark}>✦</div>
          <div>
            <div style={s.logoName}>ROCK BOTTOM 2</div>
            <div style={s.logoName2}>RELENTLESS</div>
          </div>
        </div>
        <p style={s.heroSub}>Restoration · Sovereignty · Renewal</p>

        {/* Affirmation card */}
        <div style={s.affirmCard}>
          <div style={s.affirmQuote}>"{AFFIRMATIONS[affirmIdx].quote}"</div>
          <div style={s.affirmAuthor}>— {AFFIRMATIONS[affirmIdx].author}</div>
          <div style={s.affirmDots}>
            {AFFIRMATIONS.map((_, i) => (
              <div key={i} onClick={() => setAffirmIdx(i)}
                style={{ ...s.dot, background: i === affirmIdx ? "#C9A84C" : "#333" }} />
            ))}
          </div>
        </div>
      </div>

      {/* Emergency strip */}
      <div style={s.emergencyStrip}>
        <span style={s.emergencyDot} />
        <span style={s.emergencyText}>Fairfax/NoVA? Call <strong>OAR NOVA: (703) 246-3033</strong> or dial <strong>211</strong> — 24/7</span>
      </div>

      {/* Section label */}
      <div style={s.sectionHeader}>
        <span style={s.sectionLabel}>YOUR ROADMAP</span>
        <span style={s.sectionCount}>{MODULES.length} modules</span>
      </div>

      {/* Module cards */}
      <div style={s.moduleList}>
        {MODULES.map(m => {
          const pct = progress(m.id);
          return (
            <div key={m.id} style={s.moduleCard}
              onClick={() => { setActiveModule(m.id); setActiveStep(null); setScreen("module"); }}>
              <div style={{ ...s.moduleAccent, background: `linear-gradient(135deg, ${m.grad[0]}, ${m.grad[1]})` }} />
              <div style={s.moduleCardInner}>
                <div style={s.moduleCardLeft}>
                  <div style={{ ...s.moduleIcon, background: `linear-gradient(135deg, ${m.grad[0]}22, ${m.grad[1]}22)` }}>
                    <span style={{ fontSize: 22 }}>{m.icon}</span>
                  </div>
                  <div>
                    <div style={s.moduleTitle}>
                      {m.title}
                      {m.id === "nova" && <span style={s.localBadge}>LOCAL</span>}
                    </div>
                    <div style={s.moduleSub}>{m.sub}</div>
                    {pct > 0 && (
                      <div style={s.moduleProgress}>
                        <div style={{ ...s.moduleProgressBar, width: `${pct}%`, background: m.grad[0] }} />
                      </div>
                    )}
                  </div>
                </div>
                <div style={{ ...s.moduleChevron, color: m.grad[0] }}>›</div>
              </div>
            </div>
          );
        })}
      </div>

      <div style={s.bottomPad} />
    </div>
  );

  const renderModule = () => {
    if (!mod) return null;
    const pct = progress(mod.id);
    return (
      <div style={s.screen}>
        {/* Module hero */}
        <div style={{ ...s.modHero, background: `linear-gradient(135deg, ${mod.grad[0]}, ${mod.grad[1]})` }}>
          <button style={s.backBtn} onClick={() => setScreen("home")}>← Back</button>
          <div style={s.modHeroIcon}>{mod.icon}</div>
          <div style={s.modHeroTitle}>{mod.title}</div>
          <div style={s.modHeroSub}>{mod.sub}</div>
          {pct > 0 && (
            <div style={s.modProgressRow}>
              <div style={s.modProgressTrack}>
                <div style={{ ...s.modProgressFill, width: `${pct}%` }} />
              </div>
              <span style={s.modProgressPct}>{pct}%</span>
            </div>
          )}
        </div>

        {/* Steps list */}
        <div style={s.stepsList}>
          {mod.steps.map((step, si) => {
            const done = step.items.filter((_, ii) => checked[`${mod.id}-${si}-${ii}`]).length;
            return (
              <div key={si} style={s.stepCard}
                onClick={() => { setActiveStep(si); setScreen("step"); }}>
                <div style={s.stepCardLeft}>
                  <div style={{ ...s.stepNum, background: `linear-gradient(135deg, ${mod.grad[0]}, ${mod.grad[1]})` }}>
                    {String(si + 1).padStart(2, "0")}
                  </div>
                  <div style={s.stepCardText}>
                    <div style={s.stepPhase}>{step.phase}</div>
                    <div style={s.stepTitle}>{step.title}</div>
                    <div style={s.stepMeta}>{done}/{step.items.length} completed</div>
                  </div>
                </div>
                <div style={{ ...s.stepChevron, color: mod.grad[0] }}>›</div>
              </div>
            );
          })}
        </div>

        {/* Module AI */}
        <div style={s.aiBox}>
          <div style={s.aiBoxTitle}>Ask a Question</div>
          <textarea value={aiQ} onChange={e => setAiQ(e.target.value)}
            placeholder={`Ask anything about "${mod.title}"...`}
            style={s.aiInput} rows={2} />
          <button onClick={askAI} disabled={aiLoading || !aiQ.trim()}
            style={{ ...s.aiBtn, background: `linear-gradient(135deg, ${mod.grad[0]}, ${mod.grad[1]})`, opacity: (aiLoading || !aiQ.trim()) ? 0.5 : 1 }}>
            {aiLoading ? "Getting answer…" : "Get Answer"}
          </button>
          {aiA && <div style={s.aiAnswer}>{aiA}</div>}
        </div>
        <div style={s.bottomPad} />
      </div>
    );
  };

  const renderStep = () => {
    if (!mod || !step) return null;
    const si = activeStep;
    return (
      <div style={s.screen}>
        {/* Step header */}
        <div style={{ ...s.stepHero, background: `linear-gradient(135deg, ${mod.grad[0]}18, ${mod.grad[1]}10)`, borderBottom: `1px solid ${mod.grad[0]}33` }}>
          <button style={s.backBtn2} onClick={() => setScreen("module")}>← {mod.label}</button>
          <div style={s.stepHeroPhase}>{step.phase}</div>
          <div style={s.stepHeroTitle}>{step.title}</div>
        </div>

        {/* Action items */}
        <div style={s.actionList}>
          {step.items.map((item, ii) => {
            const key = `${mod.id}-${si}-${ii}`;
            const done = !!checked[key];
            return (
              <div key={ii} style={{ ...s.actionItem, background: done ? `${mod.grad[0]}12` : "#1A1A1F", borderColor: done ? mod.grad[0] : "#2A2A32" }}
                onClick={() => toggleCheck(key)}>
                <div style={{ ...s.checkCircle, borderColor: mod.grad[0], background: done ? mod.grad[0] : "transparent" }}>
                  {done && <span style={s.checkMark}>✓</span>}
                </div>
                <span style={{ ...s.actionText, opacity: done ? 0.45 : 1, textDecoration: done ? "line-through" : "none" }}>{item}</span>
              </div>
            );
          })}
        </div>

        {/* Encouragement */}
        <div style={{ ...s.encourageBox, borderColor: mod.grad[0] + "44" }}>
          <span style={{ color: mod.grad[0], fontSize: 18 }}>💪</span>
          <span style={s.encourageText}>Check off each step as you complete it. Progress compounds.</span>
        </div>

        <div style={s.bottomPad} />
      </div>
    );
  };

  const renderSearch = () => (
    <div style={s.screen}>
      <div style={s.searchHeader}>
        <div style={s.searchTitle}>Explore Resources</div>
        <div style={s.searchSub}>All 10 modules at a glance</div>
      </div>
      <div style={s.searchGrid}>
        {MODULES.map(m => (
          <div key={m.id} style={s.searchCard}
            onClick={() => { setActiveModule(m.id); setActiveStep(null); setScreen("module"); setTab("home"); }}>
            <div style={{ ...s.searchCardGrad, background: `linear-gradient(135deg, ${m.grad[0]}, ${m.grad[1]})` }}>
              <span style={{ fontSize: 28 }}>{m.icon}</span>
            </div>
            <div style={s.searchCardLabel}>{m.label}</div>
          </div>
        ))}
      </div>
      <div style={s.bottomPad} />
    </div>
  );

  const renderProgress = () => (
    <div style={s.screen}>
      <div style={s.searchHeader}>
        <div style={s.searchTitle}>Your Progress</div>
        <div style={s.searchSub}>Track your journey to restoration</div>
      </div>
      {MODULES.map(m => {
        const pct = progress(m.id);
        const total = m.steps.reduce((a, s) => a + s.items.length, 0);
        const done = m.steps.reduce((a, s, si) =>
          a + s.items.filter((_, ii) => checked[`${m.id}-${si}-${ii}`]).length, 0);
        return (
          <div key={m.id} style={s.progressCard}
            onClick={() => { setActiveModule(m.id); setActiveStep(null); setScreen("module"); setTab("home"); }}>
            <div style={s.progressCardLeft}>
              <span style={{ fontSize: 20 }}>{m.icon}</span>
              <div>
                <div style={s.progressCardTitle}>{m.label}</div>
                <div style={s.progressCardSub}>{done} of {total} steps completed</div>
              </div>
            </div>
            <div style={s.progressCardRight}>
              <div style={{ ...s.progressPct, color: pct === 100 ? "#10B981" : m.grad[0] }}>{pct}%</div>
              <div style={s.progressTrack2}>
                <div style={{ ...s.progressFill2, width: `${pct}%`, background: pct === 100 ? "#10B981" : m.grad[0] }} />
              </div>
            </div>
          </div>
        );
      })}
      <div style={s.bottomPad} />
    </div>
  );

  const renderAsk = () => (
    <div style={s.screen}>
      <div style={s.searchHeader}>
        <div style={s.searchTitle}>AI Advisor</div>
        <div style={s.searchSub}>Ask anything — no judgment, real answers</div>
      </div>
      <div style={s.askBox}>
        <textarea value={aiQ} onChange={e => setAiQ(e.target.value)}
          placeholder="Example: 'I have a drug felony from 2019 in Texas. Can I get an apartment?' or 'What IT certifications can I get for free near Atlanta?'"
          style={s.askInput} rows={4} />
        <button onClick={askAI} disabled={aiLoading || !aiQ.trim()}
          style={{ ...s.askBtn, opacity: (aiLoading || !aiQ.trim()) ? 0.5 : 1 }}>
          {aiLoading ? "Getting your answer…" : "Get My Answer →"}
        </button>
        {aiA && (
          <div style={s.askAnswer}>
            <div style={s.askAnswerLabel}>YOUR ADVISOR SAYS</div>
            <div style={s.askAnswerText}>{aiA}</div>
          </div>
        )}
      </div>

      {/* Suggested questions */}
      {!aiA && (
        <div style={s.suggestBox}>
          <div style={s.suggestLabel}>SUGGESTED QUESTIONS</div>
          {[
            "What jobs can I get with a felony in my state?",
            "How do I get my record expunged?",
            "Can I get a CDL with a felony conviction?",
            "What free IT training is near me?",
            "How do I open a bank account with no credit?",
          ].map((q, i) => (
            <div key={i} style={s.suggestItem} onClick={() => setAiQ(q)}>
              <span style={s.suggestQ}>{q}</span>
              <span style={s.suggestArrow}>›</span>
            </div>
          ))}
        </div>
      )}
      <div style={s.bottomPad} />
    </div>
  );

  const isDetail = screen === "module" || screen === "step";
  const showNav = !isDetail;

  return (
    <div style={s.app}>
      {/* Status bar spacer */}
      <div style={s.statusBar} />

      {/* Content */}
      <div style={s.content}>
        {screen === "home" && tab === "home" && renderHome()}
        {screen === "home" && tab === "search" && renderSearch()}
        {screen === "home" && tab === "progress" && renderProgress()}
        {screen === "home" && tab === "ask" && renderAsk()}
        {screen === "module" && renderModule()}
        {screen === "step" && renderStep()}
      </div>

      {/* Bottom nav */}
      {showNav && (
        <div style={s.nav}>
          {[
            { id: "home", icon: "⊞", label: "Home" },
            { id: "search", icon: "◎", label: "Explore" },
            { id: "progress", icon: "◈", label: "Progress" },
            { id: "ask", icon: "✧", label: "Ask AI" },
          ].map(n => (
            <button key={n.id} style={{ ...s.navBtn, opacity: tab === n.id ? 1 : 0.45 }}
              onClick={() => { setTab(n.id); setScreen("home"); }}>
              <span style={{ ...s.navIcon, color: tab === n.id ? "#C9A84C" : "#888" }}>{n.icon}</span>
              <span style={{ ...s.navLabel, color: tab === n.id ? "#C9A84C" : "#666" }}>{n.label}</span>
              {tab === n.id && <div style={s.navDot} />}
            </button>
          ))}
        </div>
      )}
    </div>
  );
}

// ─── STYLES ──────────────────────────────────────────────────────────────────

const s = {
  app: {
    minHeight: "100vh",
    background: "#0E0E12",
    color: "#F0EDE8",
    fontFamily: "'Georgia', 'Times New Roman', serif",
    display: "flex",
    flexDirection: "column",
    maxWidth: 480,
    margin: "0 auto",
    position: "relative",
  },
  statusBar: { height: 8, background: "#0E0E12" },
  content: { flex: 1, overflowY: "auto", overflowX: "hidden", paddingBottom: 72 },
  screen: { minHeight: "100%", paddingBottom: 24 },

  // ── Hero
  hero: {
    background: "linear-gradient(180deg, #141418 0%, #0E0E12 100%)",
    padding: "28px 20px 20px",
    position: "relative",
    overflow: "hidden",
  },
  heroGlow: {
    position: "absolute", top: -60, right: -60,
    width: 200, height: 200,
    background: "radial-gradient(circle, #C9A84C18 0%, transparent 70%)",
    pointerEvents: "none",
  },
  logoRow: { display: "flex", alignItems: "center", gap: 12, marginBottom: 4 },
  logoMark: { fontSize: 28, color: "#C9A84C", lineHeight: 1 },
  logoName: { fontSize: 20, fontWeight: 900, letterSpacing: "0.12em", color: "#FFF", lineHeight: 1.1 },
  logoName2: { fontSize: 20, fontWeight: 900, letterSpacing: "0.12em", color: "#C9A84C", lineHeight: 1.1 },
  heroSub: { margin: "6px 0 20px 40px", fontSize: 10, letterSpacing: "0.18em", color: "#666", textTransform: "uppercase" },

  affirmCard: {
    background: "linear-gradient(135deg, #1A1A22, #141418)",
    border: "1px solid #C9A84C22",
    borderRadius: 16,
    padding: "18px 20px 14px",
  },
  affirmQuote: { fontSize: 13.5, lineHeight: 1.65, color: "#D4C9B0", fontStyle: "italic", marginBottom: 10 },
  affirmAuthor: { fontSize: 11, color: "#C9A84C", letterSpacing: "0.08em" },
  affirmDots: { display: "flex", gap: 6, marginTop: 12 },
  dot: { width: 6, height: 6, borderRadius: 3, cursor: "pointer", transition: "background 0.2s" },

  // ── Emergency
  emergencyStrip: {
    display: "flex", alignItems: "center", gap: 8,
    background: "#1A0D0D", borderTop: "1px solid #EF444422", borderBottom: "1px solid #EF444422",
    padding: "10px 20px",
  },
  emergencyDot: { width: 7, height: 7, borderRadius: "50%", background: "#EF4444", flexShrink: 0, boxShadow: "0 0 6px #EF4444" },
  emergencyText: { fontSize: 12, color: "#FCA5A5", lineHeight: 1.4 },
  localBadge: {
    display: "inline-block", marginLeft: 8,
    background: "linear-gradient(135deg, #F97316, #C2410C)",
    color: "#FFF", fontSize: 9, fontWeight: 800, letterSpacing: "0.1em",
    padding: "2px 6px", borderRadius: 4, verticalAlign: "middle",
  },

  // ── Section
  sectionHeader: {
    display: "flex", justifyContent: "space-between", alignItems: "center",
    padding: "20px 20px 10px",
  },
  sectionLabel: { fontSize: 10, letterSpacing: "0.2em", color: "#555", fontWeight: 600 },
  sectionCount: { fontSize: 11, color: "#444", background: "#1A1A22", padding: "3px 10px", borderRadius: 20 },

  // ── Module cards
  moduleList: { padding: "0 16px", display: "flex", flexDirection: "column", gap: 10 },
  moduleCard: {
    background: "#1A1A22", borderRadius: 16, overflow: "hidden",
    cursor: "pointer", position: "relative",
    border: "1px solid #252530",
    transition: "transform 0.1s",
  },
  moduleAccent: { position: "absolute", left: 0, top: 0, bottom: 0, width: 4 },
  moduleCardInner: { display: "flex", alignItems: "center", justifyContent: "space-between", padding: "14px 16px 14px 18px" },
  moduleCardLeft: { display: "flex", alignItems: "center", gap: 14, flex: 1 },
  moduleIcon: { width: 48, height: 48, borderRadius: 12, display: "flex", alignItems: "center", justifyContent: "center", flexShrink: 0 },
  moduleTitle: { fontSize: 15, fontWeight: 700, color: "#F0EDE8", marginBottom: 2 },
  moduleSub: { fontSize: 11.5, color: "#666" },
  moduleProgress: { width: 100, height: 3, background: "#252530", borderRadius: 2, marginTop: 6 },
  moduleProgressBar: { height: "100%", borderRadius: 2, transition: "width 0.4s" },
  moduleChevron: { fontSize: 26, fontWeight: 300, lineHeight: 1 },

  // ── Module detail
  modHero: {
    padding: "48px 20px 24px",
    position: "relative",
  },
  backBtn: {
    position: "absolute", top: 16, left: 16,
    background: "rgba(0,0,0,0.3)", border: "1px solid rgba(255,255,255,0.15)",
    color: "#FFF", borderRadius: 20, padding: "6px 14px", fontSize: 12, cursor: "pointer",
  },
  modHeroIcon: { fontSize: 44, marginBottom: 10, lineHeight: 1 },
  modHeroTitle: { fontSize: 26, fontWeight: 900, color: "#FFF", marginBottom: 4 },
  modHeroSub: { fontSize: 13, color: "rgba(255,255,255,0.7)" },
  modProgressRow: { display: "flex", alignItems: "center", gap: 10, marginTop: 16 },
  modProgressTrack: { flex: 1, height: 4, background: "rgba(255,255,255,0.2)", borderRadius: 2 },
  modProgressFill: { height: "100%", background: "rgba(255,255,255,0.85)", borderRadius: 2, transition: "width 0.4s" },
  modProgressPct: { fontSize: 12, color: "rgba(255,255,255,0.85)", minWidth: 32 },

  // ── Steps list
  stepsList: { padding: "16px 16px 0" },
  stepCard: {
    background: "#1A1A22", borderRadius: 14, padding: "14px 16px",
    display: "flex", alignItems: "center", justifyContent: "space-between",
    cursor: "pointer", marginBottom: 10, border: "1px solid #252530",
  },
  stepCardLeft: { display: "flex", alignItems: "center", gap: 14, flex: 1 },
  stepNum: {
    width: 40, height: 40, borderRadius: 10,
    display: "flex", alignItems: "center", justifyContent: "center",
    fontSize: 13, fontWeight: 800, color: "#FFF", flexShrink: 0,
  },
  stepCardText: { flex: 1 },
  stepPhase: { fontSize: 10, color: "#666", letterSpacing: "0.08em", marginBottom: 2 },
  stepTitle: { fontSize: 14, fontWeight: 700, color: "#F0EDE8", lineHeight: 1.3 },
  stepMeta: { fontSize: 11, color: "#555", marginTop: 3 },
  stepChevron: { fontSize: 24, fontWeight: 300 },

  // ── Step detail
  stepHero: {
    padding: "52px 20px 20px",
  },
  backBtn2: {
    display: "block", background: "transparent", border: "none",
    color: "#C9A84C", fontSize: 13, cursor: "pointer", marginBottom: 16, padding: 0,
  },
  stepHeroPhase: { fontSize: 10, color: "#666", letterSpacing: "0.12em", marginBottom: 6 },
  stepHeroTitle: { fontSize: 22, fontWeight: 800, color: "#F0EDE8", lineHeight: 1.3 },

  actionList: { padding: "12px 16px 0" },
  actionItem: {
    display: "flex", alignItems: "flex-start", gap: 14,
    padding: "14px 16px", borderRadius: 12, marginBottom: 8,
    cursor: "pointer", border: "1px solid", transition: "all 0.15s",
  },
  checkCircle: {
    width: 22, height: 22, borderRadius: 11, border: "2px solid",
    display: "flex", alignItems: "center", justifyContent: "center",
    flexShrink: 0, marginTop: 1, transition: "background 0.15s",
  },
  checkMark: { fontSize: 12, fontWeight: 900, color: "#FFF" },
  actionText: { fontSize: 13.5, lineHeight: 1.6, color: "#C8C4BC", transition: "all 0.15s" },

  encourageBox: {
    margin: "16px 16px 0", padding: "14px 16px",
    background: "#141418", borderRadius: 12, border: "1px solid",
    display: "flex", alignItems: "center", gap: 12,
  },
  encourageText: { fontSize: 12.5, color: "#888", fontStyle: "italic" },

  // ── AI box (in module)
  aiBox: {
    margin: "20px 16px 0",
    background: "#141418", borderRadius: 16, padding: "18px",
    border: "1px solid #252530",
  },
  aiBoxTitle: { fontSize: 13, fontWeight: 700, color: "#C9A84C", marginBottom: 12, letterSpacing: "0.05em" },
  aiInput: {
    width: "100%", background: "#1A1A22", border: "1px solid #2A2A35",
    borderRadius: 10, color: "#F0EDE8", padding: "12px 14px", fontSize: 13,
    fontFamily: "Georgia, serif", resize: "none", boxSizing: "border-box", lineHeight: 1.5,
  },
  aiBtn: {
    marginTop: 10, width: "100%", border: "none", borderRadius: 10,
    padding: "13px", color: "#FFF", fontWeight: 700, fontSize: 13,
    cursor: "pointer", letterSpacing: "0.04em",
  },
  aiAnswer: {
    marginTop: 14, padding: "14px", background: "#0E0E12",
    borderRadius: 10, fontSize: 13, lineHeight: 1.7, color: "#C8C4BC",
    whiteSpace: "pre-wrap",
  },

  // ── Search / Explore
  searchHeader: { padding: "32px 20px 16px" },
  searchTitle: { fontSize: 26, fontWeight: 900, color: "#F0EDE8", marginBottom: 4 },
  searchSub: { fontSize: 13, color: "#666" },
  searchGrid: {
    display: "grid", gridTemplateColumns: "repeat(3, 1fr)",
    gap: 12, padding: "0 16px",
  },
  searchCard: { cursor: "pointer", textAlign: "center" },
  searchCardGrad: {
    borderRadius: 16, padding: "20px 0",
    display: "flex", alignItems: "center", justifyContent: "center",
    marginBottom: 8,
  },
  searchCardLabel: { fontSize: 11, color: "#888", lineHeight: 1.3 },

  // ── Progress
  progressCard: {
    margin: "0 16px 10px",
    background: "#1A1A22", borderRadius: 14, padding: "14px 16px",
    display: "flex", alignItems: "center", justifyContent: "space-between",
    cursor: "pointer", border: "1px solid #252530",
  },
  progressCardLeft: { display: "flex", alignItems: "center", gap: 12 },
  progressCardTitle: { fontSize: 14, fontWeight: 700, color: "#F0EDE8" },
  progressCardSub: { fontSize: 11, color: "#555", marginTop: 2 },
  progressCardRight: { alignItems: "flex-end", display: "flex", flexDirection: "column", gap: 6, minWidth: 80 },
  progressPct: { fontSize: 16, fontWeight: 800 },
  progressTrack2: { width: 80, height: 4, background: "#252530", borderRadius: 2 },
  progressFill2: { height: "100%", borderRadius: 2, transition: "width 0.4s" },

  // ── Ask AI
  askBox: { padding: "0 16px" },
  askInput: {
    width: "100%", background: "#1A1A22", border: "1px solid #2A2A35",
    borderRadius: 14, color: "#F0EDE8", padding: "14px 16px", fontSize: 14,
    fontFamily: "Georgia, serif", resize: "none", boxSizing: "border-box",
    lineHeight: 1.6, marginBottom: 12,
  },
  askBtn: {
    width: "100%", border: "none", borderRadius: 12,
    padding: "14px", color: "#000", fontWeight: 800, fontSize: 14,
    cursor: "pointer", letterSpacing: "0.04em",
    background: "linear-gradient(135deg, #C9A84C, #F0C84C)",
  },
  askAnswer: {
    marginTop: 16, background: "#141418", borderRadius: 14, padding: "18px",
    border: "1px solid #C9A84C22",
  },
  askAnswerLabel: { fontSize: 10, color: "#C9A84C", letterSpacing: "0.15em", marginBottom: 10 },
  askAnswerText: { fontSize: 14, lineHeight: 1.75, color: "#D4C9B0", whiteSpace: "pre-wrap" },

  suggestBox: { margin: "20px 16px 0" },
  suggestLabel: { fontSize: 10, color: "#444", letterSpacing: "0.15em", marginBottom: 10 },
  suggestItem: {
    background: "#1A1A22", borderRadius: 12, padding: "13px 16px",
    marginBottom: 8, cursor: "pointer", border: "1px solid #252530",
    display: "flex", justifyContent: "space-between", alignItems: "center",
  },
  suggestQ: { fontSize: 13, color: "#C8C4BC" },
  suggestArrow: { fontSize: 20, color: "#444" },

  // ── Bottom nav
  nav: {
    position: "fixed", bottom: 0, left: "50%", transform: "translateX(-50%)",
    width: "100%", maxWidth: 480,
    background: "rgba(14,14,18,0.97)", borderTop: "1px solid #1E1E26",
    display: "flex", justifyContent: "space-around", alignItems: "center",
    padding: "8px 0 16px", zIndex: 100,
    backdropFilter: "blur(20px)",
  },
  navBtn: {
    background: "transparent", border: "none", cursor: "pointer",
    display: "flex", flexDirection: "column", alignItems: "center", gap: 3,
    padding: "4px 16px", position: "relative",
  },
  navIcon: { fontSize: 20, lineHeight: 1, transition: "color 0.2s" },
  navLabel: { fontSize: 10, letterSpacing: "0.04em", transition: "color 0.2s" },
  navDot: {
    position: "absolute", bottom: -6, width: 4, height: 4,
    borderRadius: 2, background: "#C9A84C",
  },

  bottomPad: { height: 32 },
};
