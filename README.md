# TalentOS
TalentOS is a modular platform designed for managing talent profiles and curriculums. It follows a microservices architecture, separating concerns between user management, curriculum handling, and the frontend user experience.

## Project Structure
This repository acts as a central aggregator for the TalentOS ecosystem. The project is organized into the following submodules:
- web-app: The main frontend application interface.
- bff-web-app: Backend for Frontend (BFF) service that orchestrates data for the web application.
- user-api: Core service dedicated to user authentication and profile management.
- curriculum-api: Service specialized in managing curriculum vitae data and structure.
- domain-api: Domain-specific logic and rules processing.
- commons: Shared libraries, utilities, and contracts used across the different services.

## Getting Started
### Installation
To set up the project locally, you need to clone this repository along with all its submodules.
1. Clone the repository:
```bash 
git clone --recurse-submodules git@github.com:GiuseppeFalcone/talentos.git
cd talentos
```
2. If you have already cloned the repository without submodules:
```bash
git submodule update --init --recursive
```

### Contributing
Please check the individual submodules for specific contribution guidelines and coding standards.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
