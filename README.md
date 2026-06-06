# Adamas CR Voting System

A web-based Class Representative voting application built exclusively for Adamas University. The system helps students verify their identity, cast one secure vote, and view election results while giving administrators tools to manage candidates, classes, election settings, and result exports.

## Features

- Email-based student verification for eligible Adamas voters
- Role-based access for voters and administrators
- Protected voting and admin routes
- Candidate and class management
- Clean voting interface for CR elections
- Admin dashboard for election monitoring
- Live result display and vote statistics
- Election controls for opening or closing voting
- CSV result export

## Tech Stack

- React, TypeScript, and Vite
- React Router v6
- Tailwind CSS and Radix UI
- React Context API
- Firebase
- Recharts
- Framer Motion
- Bun or npm
- Vercel deployment support

## Project Structure

```text
src/
|-- components/         # Shared UI, layout, and admin components
|-- contexts/           # Authentication context provider
|-- hooks/              # Custom React hooks
|-- lib/                # Firebase and utility helpers
|-- pages/              # Application pages
`-- components/ui/      # Reusable Radix-based UI components
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm, Bun, or another compatible package manager

### Installation

```sh
git clone <your-repository-url>
cd adamas-cr-voting-system
npm install
npm run dev
```

Create a `.env` file in the project root and add the required Firebase configuration values before running the app in a real environment.

## Usage

- Students verify with an Adamas University email address, then cast their vote for a CR candidate.
- Administrators use the admin panel to add candidates, manage classes, monitor turnout, update election settings, and export results.

## Contributors

Thanks to everyone who has contributed to this project.

<table>
  <tr>
    <td align="center"><a href="https://github.com/pmohata34"><img src="https://github.com/pmohata34.png" width="100px;" alt="Pranjal"/><br /><sub><b>Pranjal</b></sub></a></td>
    <td align="center"><a href="https://github.com/Sahnik0"><img src="https://github.com/Sahnik0.png" width="100px;" alt="Sahnik Biswas"/><br /><sub><b>Sahnik Biswas</b></sub></a></td>
    <td align="center"><a href="https://github.com/sanks011"><img src="https://github.com/sanks011.png" width="100px;" alt="Sankalpa"/><br /><sub><b>Sankalpa</b></sub></a></td>
  </tr>
</table>

## License

This project is open-source under the MIT License.
