# Website Template for NAU Prayavaranshala 

A React-based web application which will serve as a resource hub and help spread awareness for he NAU Prayavaranshala (School for Environment) in India. 

## Features

- **Interactive Homepage** - Dynamic content with hero sections and feature highlights
- **Research Showcase** - Display of educational research and findings
- **Case Studies** - Detailed case studies of successful learning environment transformations
- **Pilot Projects** - Showcase of innovative pilot projects and their outcomes
- **Interactive Maps** - Location-based visualization using Leaflet maps
- **Knowledge Library** - Comprehensive resource library for educators
- **Contact Information** - Easy communication channels for stakeholders
- **Responsive Design** - Mobile-friendly interface using Bootstrap

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm (comes with Node.js)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd nau-prayavaranshala
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the URL shown in your terminal)

## Project Structure

```
nau-prayavaranshala/
├── public/                          # Static assets and data files
│   ├── *.json                       # Content data files
│   ├── *.png, *.jpeg               # Images and logos
│   └── pilot_project_*_photos/     # Project photo galleries
├── src/
│   ├── components/                  # React components
│   │   ├── Home.jsx                # Landing page
│   │   ├── AboutUs.jsx             # About us page
│   │   ├── ImpactCreated.jsx       # Impact showcase
│   │   ├── KnowledgeLibrary.jsx    # Resource library
│   │   ├── Locations.jsx           # Interactive maps
│   │   ├── Contact.jsx             # Contact information
│   │   ├── ProjectDetails.jsx      # Individual project pages
│   │   ├── CaseDetails.jsx         # Case study details
│   │   ├── Navbar.jsx              # Navigation component
│   │   └── Footer.jsx              # Footer component
│   ├── App.jsx                     # Main application component
│   ├── main.jsx                    # Application entry point
│   └── assets/                     # Additional assets
├── package.json                    # Dependencies and scripts
└── vite.config.js                 # Vite configuration
```

## ️ Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check code quality

## Technologies Used

- **React 18** - Frontend framework
- **Vite** - Build tool and development server
- **React Router DOM** - Client-side routing
- **Bootstrap 5** - CSS framework for responsive design
- **React Bootstrap** - Bootstrap components for React
- **Leaflet** - Interactive maps
- **React Leaflet** - React wrapper for Leaflet
- **React Icons** - Icon library
- **React Responsive Carousel** - Image carousel component

## Data Management

The application uses JSON files in the `public/` directory to manage content:

- `home.json` - Homepage content and descriptions
- `research.json` - Research data and findings
- `case_study.json` - Case study information
- `pilot_projects.json` - Pilot project details
- `locations.json` - Location data for maps

## Key Pages

1. **Home** (`/`) - Landing page with overview and navigation
2. **About Us** (`/about-us`) - Information about the organization
3. **Impact Created** (`/impact-created`) - Showcase of achievements
4. **Knowledge Library** (`/knowledge-library`) - Educational resources
5. **Locations** (`/locations`) - Interactive map of project locations
6. **Contact** (`/contact`) - Contact information and form
7. **Project Details** (`/project/:id`) - Individual project pages
8. **Case Study Details** (`/case_study/:id`) - Detailed case studies

## Development

### Adding New Content

1. Update the appropriate JSON file in the `public/` directory
2. Add any new images to the relevant folder in `public/`
3. The components will automatically fetch and display the new content

### Styling

- The application uses Bootstrap 5 for responsive design
- Custom CSS is in `src/App.css` and `src/index.css`
- Component-specific styles are defined inline or in component files

### Routing

The application uses React Router for navigation. Routes are defined in `src/App.jsx`.

## Deployment

To build the application for production:

```bash
npm run build
```

The built files will be in the `dist/` directory, ready for deployment to any static hosting service.

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support or questions, please contact the development team or refer to the contact information on the website.

---

**NAU Prayavaranshala** - Transforming early childhood education through innovative design and research.
