# DrugDiscovery: Bridging Molecules and Minds with AI & Real-Time Tools

*DrugDiscovery* addresses the need for a comprehensive, intuitive platform designed to simplify molecular research and foster collaboration. Researchers and developers often face challenges with the complexity of molecular structures, the intricacies of designing novel molecules with SMILES notation, and inefficiencies in team communication. Traditional methods can be time-consuming and lack the AI-driven tools and real-time collaboration needed for efficient, impactful research.


## ⚙ Tech Stack

- *Next.js*
- *TypeScript*
- *Tailwind CSS*
- *RDKit* (for visualizing protein data)
- *Nvidia Nim* 
- *MongoDb*
- *Mongoose* 
- *Ably* 


## Key Features

With *DrugDiscovery*, users benefit from a variety of powerful tools, including:

- *Instant Molecular Visualization*  
  Leverage RDKit integration for immediate molecular visualization, providing clear insights into molecular properties and interactions to aid in research and discovery.

- *Streamlined Molecule Generation with SMILES Notation*  
  Supported by AI-powered suggestions, our platform facilitates molecule generation with SMILES notation, helping users design novel molecular structures with high precision and aiding breakthroughs in drug discovery and chemical synthesis.

- *Real-Time Group Messaging*  
  A collaborative research space where teams can easily share findings, brainstorm, and make decisions together in real-time.

- *Secure, Modern User Interface*  
  A contemporary UI/UX with advanced authentication and verification ensures a seamless and intuitive user experience, prioritizing data security and ease of use.

*DrugDiscovery* consolidates visualization, molecule generation, and team collaboration into a single platform, accelerating research, supporting informed decision-making, and fostering scientific advancement.

## Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- npm (Node Package Manager, included with Node.js)

### Cloning the Repository

Clone the repository and navigate into the project directory:

bash
git clone https://github.com/mendsalbert/ProteinBind.git
cd proteinbind


### Installation

Install the project dependencies using npm:


npm install


### *Set Up Environment Variables*

Create a new file named .env in the root of your project and add the following content:

env
NEXTAUTH_SECRET=
RESEND_KEY=
NEXT_PUBLIC_API_BASE_URL=http://localhost:3000
MONGODB_URL=
NEXT_PUBLIC_NVIDIA_API_KEY=
NEXT_PUBLIC_ABLY_API_KEY=


### *Running the Project*

bash
npm run dev


Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.