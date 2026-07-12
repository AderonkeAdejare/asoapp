AsoApp
**The cultural bridal coordination app for Nigerian weddings.**

AsoApp is a mobile-first bridal coordination app built for brides planning traditional Yoruba Nigerian weddings and brides marrying into Nigerian families. The app brings together style discovery, aso ebi coordination, vendor connection, and cultural education in one dedicated platform - giving brides the tools to visualize their look, coordinate fabric and style choices across their entire wedding party, and find vetted tailors and fabric vendors with confidence. Built for the Nigerian diaspora in the US, AsoApp fills a gap that generic wedding platforms have missed: a culturally specific, community-centered experience that honors the richness of Nigerian wedding traditions while solving real logistical challenges for modern brides and their families.

---

## Features

- **Style Quiz** - Personalized Yoruba bridal style recommendations based on ceremony type, aesthetic preferences, and budget *(in progress)*
- **Aso Ebi Coordinator** - Fabric and style coordination tools for the full wedding party *(TBD)*
- **Vendor Directory** - Vetted tailors, fabric vendors, and gele artists across the US, Nigeria, and UK *(TBD)*
- **Cultural Education Hub** - Guides on traditional garments, ceremonies, and Yoruba wedding customs *(TBD)*
- **Lookbook** - Curated bridal inspiration organized by ceremony type and style archetype *(TBD)*
- **Budget Tracker** - Cost management tools specific to traditional Nigerian wedding needs *(TBD)*

## Target Markets
Primary: Nigerian diaspora brides in the United States
Expanding: Nigeria (Lagos, Abuja) and United Kingdom (London) 

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend + Styling | React, Tailwind CSS |
| Backend + AI Recommendations | Node.js, Claude Code (Anthropic API) |
| Database | Firebase |
| Deployment | Vercel |

---

## Roadmap

### Phase 1 - MVP (Current)
- [x] Project scaffolding and setup
- Style quiz - static logic (in progress)
- Lookbook with curated styles
- Cultural Education Hub
- Mobile-responsive UI

### Phase 2 - AI + Vendors
- AI-powered style recommendations via Claude API
- Vendor directory with search and filtering
- Aso ebi coordination tools
- User accounts and saved looks

### Phase 3 - Community + Scale
- Nigeria and UK market expansion
- Community reviews and vendor ratings
- Budget tracker
- Native mobile app (React Native)

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/ "source-reference") v20+
- [npm](https://www.npmjs.com/ "source-reference") v10+
- [Git](https://git-scm.com/ "source-reference")

### Installation

1. Clone the repository:

bash
git clone https://github.com/yourusername/asoapp.git
cd asoapp
Install dependencies:
npm install
Start the development server:
npm start
Open your browser to:
http://localhost:3000

### Project Structure
asoapp/
├── public/
├── src/
│ ├── components/ # Reusable UI components
│ ├── pages/ # Full page views (Home, Quiz, Vendors, etc.)
│ ├── data/ # Static style and cultural content data
│ ├── hooks/ # Custom React hooks
│ ├── styles/ # Global styles and theme variables
│ └── App.js # Root component and routing
├── docs/
│ └── AsoApp_PRD_v1.3.md
├── README.md
└── package.json

## Contributing
AsoApp welcomes contributions from cultural consultants and Nigerian wedding professionals. Please contact Aderonke Adejare at aderonke@aoadigitalstories.com to add your input. 

## Contact
Built by Aderonke Adejare
LinkedIn · Portfolio

## License
This project is licensed under the MIT License.
