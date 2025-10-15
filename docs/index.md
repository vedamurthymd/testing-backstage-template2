<img alt="Backstage" src="https://img.shields.io/badge/backstage-%23ffffff.svg?style=for-the-badge&amp;logo=backstage&amp;logoColor=black">

<img alt="TypeScript" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&amp;logo=typescript&amp;logoColor=white">

<img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&amp;logo=react&amp;logoColor=%2361DAFB">

A developer portal built with Backstage for the Lululemon development team. This portal provides a centralized location for discovering, documenting, and managing our software ecosystem.

🌟 Features
Service Catalog: Discover and manage all Lululemon services, APIs, and components
Documentation Hub: Centralized technical documentation with TechDocs
CI/CD Integration: Connect with our build pipelines and deployments
Template Library: Standardized templates for new projects and components
Search & Discovery: Powerful search across all documentation and services
User Management: Role-based access and team management
🚀 Quick Start
Prerequisites
Node.js (v16 or later)
Yarn package manager
Docker (optional, for some features)
Installation
Clone the repository

Install dependencies

Configure environment

Start the development server

Open your browser

Navigate to http://localhost:7008

📖 Usage
Adding New Components
Create a catalog-info.yaml file in your service repository
Register it in the portal's catalog locations
Add documentation using TechDocs
Creating Documentation
Add mkdocs.yml and docs/ folder to your repository
Annotate your component with backstage.io/techdocs-ref
Documentation will be automatically built and published
Using Templates
Navigate to "Create" in the sidebar
Select a template (React Component, Service, etc.)
Fill in the required information
Your new project will be scaffolded automatically
🏗️ Architecture
🔧 Configuration
Environment Variables
Variable	Description	Required
GITHUB_TOKEN	GitHub API access	Yes
GITLAB_TOKEN	GitLab API access	Optional
POSTGRES_HOST	Database host	Optional
Plugin Configuration
Edit app-config.yaml to configure plugins and integrations.

🤝 Contributing
We welcome contributions! Please see our Contributing Guide for details.

Development Workflow
Fork the repository
Create a feature branch
Make your changes
Add tests
Submit a pull request
Code Standards
Use TypeScript for all new code
Follow the existing code style
Add comprehensive tests
Update documentation
📚 Documentation
Backstage Documentation
TechDocs Guide
Plugin Development
🐛 Troubleshooting
Common Issues
Portal not loading

Check that all dependencies are installed
Verify environment variables are set
Check console for error messages
Documentation not building

Ensure MkDocs is installed
Check TechDocs configuration
Verify file paths in annotations
Catalog not updating

Check catalog location configurations
Verify entity YAML syntax
Restart the backend service
📄 License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

🙋 Support
Issues: GitHub Issues
Discussions: GitHub Discussions
Slack: #backstage-support (internal)
👥 Team
Platform Team: platform@lululemon.com
DevOps Team: devops@lululemon.com
Built with ❤️ by the Lululemon Platform Team

Empowering developers to build better software, faster.
