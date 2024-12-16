## Core Technologies
These technologies form the foundation of every project unless specifically noted otherwise.

### Frontend Framework
- **React** with **TypeScript** - Primary framework for all projects
  - **Preact** - Used for lightweight sites where bundle size is critical

### Styling
- **TailwindCSS** - Default styling solution for all projects
- **UI Components**:
  - **HeadlessUI** - Default UI kit
  - **daisyUI** - Used when pre-styled components are required

### Static Site Generation
- **Gatsby** - Primary static site generator
- **Vite** - Development server and build tool

## Content Management Systems
Selection based on client requirements:

- **Sanity** - Default choice for most projects
- **Contentful** - Used when extensive customization is needed
- **Prismic** - Preferred when client prioritizes editor experience

## Hosting & Deployment
Base choice depends on client requirements:

- **Cloudflare Pages** - Default choice for static sites
- **Netlify** - Alternative with additional features
- **Render** - Used for specific deployment requirements

## Development Tools & Quality Assurance
Standard tools used across all projects:

- **Git** - Version control with feature branch workflow
- **ESLint** & **Prettier** - Code formatting and quality
- **Testing**:
  - **Jest** - Unit testing
  - **Cypress** - E2E testing

## Analytics & Monitoring
- **Plausible** (self-hosted) - Default analytics solution
- **PostHog** (self-hosted) - Used when advanced marketing analytics are required
- **Sentry** - Error tracking (when budget and requirements align)

## Authentication & Database
- **Supabase** - Standard solution for both authentication and database needs

## Form Handling
Solutions selected based on requirements and budget:

- **AWS Lambda** - Custom serverless solution
- **Netlify Forms** - Simple form handling for Netlify-hosted sites
- **Formik** - Complex form handling in React

## API Integration
- **Axios** - Default for simple API calls
- **TanStack Query** - Used for complex API integration requirements

## State Management
- **Zustand** - When global state management is required
- React Context - For simpler state management needs

## Additional Tools & Libraries

### UI/UX Enhancement
- **Framer Motion** - Animation library
- **Heroicons** - Icon library

### Development Experience
- **Storybook** - Component documentation for larger projects
- **GitHub Actions** - CI/CD for static sites when required

## Project Setup Considerations

### When to Use Specific Tools

1. **CMS Selection**:
   - Default to Sanity for most projects
   - Use Contentful when extensive customization is needed
   - Choose Prismic when editor experience is a priority

2. **Hosting Selection**:
   - Start with Cloudflare Pages for static sites
   - Consider Netlify when its specific features are needed
   - Use Render for special deployment requirements

3. **Analytics Implementation**:
   - Use Plausible for standard analytics needs
   - Implement PostHog when detailed marketing data is required
   - Add Sentry when robust error tracking is needed

4. **Form Handling**:
   - Use Netlify Forms for simple forms on Netlify-hosted sites
   - Implement AWS Lambda for custom solutions
   - Choose Formik for complex form requirements

5. **State Management**:
   - Start with React Context for simple state
   - Implement Zustand when global state becomes complex

6. **Component Documentation**:
   - Implement Storybook only for larger projects
   - Use JSDoc comments for smaller projects

## Best Practices

### Version Control
- Use feature branches for development
- Maintain clean commit history
- Regular merges to main/development branch

### Performance
- Regular Lighthouse audits
- Image optimization
- Code splitting when necessary
- Bundle size monitoring

### Security
- Regular dependency updates
- Secure authentication practices with Supabase
- HTTPS enforcement
- Proper environment variable management

## Project Setup Checklist
1. Initialize React + TypeScript project with Vite
2. Configure TailwindCSS and HeadlessUI
3. Set up ESLint and Prettier
4. Configure testing environment (Jest + Cypress)
5. Set up version control and branching strategy
6. Configure CMS based on project requirements
7. Set up deployment and hosting
8. Implement analytics and monitoring
9. Configure authentication if required
10. Set up additional tools based on project needs
