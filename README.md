# Cyber Safe Uganda Hub

A cybersecurity awareness platform helping individuals, small businesses, schools, and organizations in Uganda stay safer online.

An initiative by **Solo Soft Technologies**, founded by **Odyek Solomon**.

## Our Mission

Make cybersecurity knowledge accessible and practical through awareness resources, training, and business consultations.

## Awareness Topics

- Phishing and online scams
- Password security and account protection
- Mobile money fraud prevention
- Data privacy and protection
- Safe internet and social media use
- Cyber hygiene for small businesses

## Platform Features

### Visitors and Members

- Explore cybersecurity training programs.
- Read awareness guides and educational resources.
- Request training sessions and business consultations.
- Create an account and view training bookings.

### Administration

The project includes a basic admin dashboard for:

- Reviewing and updating training bookings
- Managing inquiries and consultation requests
- Creating and publishing programs, events, and resources
- Updating training prices in Uganda shillings (UGX)
- Viewing registered profiles and updating account status
- Managing available site settings

Further dashboard improvements are planned.

## Technology Stack

| Area | Technologies |
| --- | --- |
| Application | React, TypeScript, TanStack Start |
| Routing | TanStack Router |
| Styling | Tailwind CSS, shadcn/ui |
| Data fetching | TanStack Query |
| Authentication and database integration | Supabase |
| Build tools | Vite |
| Validation | Zod |
| Testing | Vitest |

## Local Development

### Requirements

- A compatible Node.js installation and npm
- Access to the project's Supabase configuration
- Git

### Installation

1. Clone this repository and open its directory.

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure the environment variables required by the project.

   Obtain the correct configuration from the project owner.
   Database-backed features require a configured backend and its schema.

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL displayed in the terminal.

## Available Commands

```bash
npm run dev       # Start development server
npm run build     # Build the application
npm run preview   # Preview the build
npm run lint      # Run ESLint
npm run test      # Run the configured test suite
```

## Project Structure

```text
src/
├── assets/                 # Images and visual assets
├── components/
│   ├── site/               # Website components
│   └── ui/                 # Reusable interface components
├── integrations/           # Authentication and backend integrations
├── lib/                    # Shared utilities and authentication state
└── routes/
    └── _authenticated/     # Protected member and admin routes

drizzle/
└── migrations/             # Database migration files
```

## Admin Access

The admin dashboard is available at `/admin`.

Users must sign in and have an administrator role.
Creating a normal account does not grant administrator access.
Admin roles should be assigned through a trusted backend process.

## Payments

Payment processing is not currently integrated.
Displayed prices support training and consultation enquiries;
they do not indicate that online payments are available.

## Security

- Keep passwords, database credentials, and service-role keys out of Git.
- Keep privileged credentials on the server.
- Enforce access permissions through database policies as well as application checks.
- Use cybersecurity demonstrations only in authorized environments.
- Report security concerns privately to the project maintainer.

## Planned Improvements

- Enhanced admin dashboard and editing workflows
- Better booking search and filtering
- Training attendance and reporting tools
- Additional cybersecurity learning resources
- Payment integration with a suitable provider

These items are planned and should not be treated as completed features.

## Maintainer

**Odyek Solomon**  
**Solo Soft Technologies**  
Uganda

## License

No open-source license has been specified.
Contact the project owner for permission to reuse or redistribute this code.
