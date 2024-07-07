# OWTS-01: Guidelines for Open Web Technologies

![Draft](https://img.shields.io/badge/status-draft-yellow.svg)

## Purpose and Background

The Open WebTech Association (OWTA) advocates for the foundational principles of openness, innovation, and inclusivity in both the development and provision of web technologies.

This specification outlines technical and structural guidelines that projects and products should adhere to in order to uphold these principles. It serves as a framework to assist developers and companies in aligning their offerings with these core values, fostering a transparent and collaborative digital ecosystem.

Following these guidelines allows projects and products to achieve a certification by OWTA. This ensures and confirms that technologies meet these standards. The full process from application to gaining a certification is described in detail in the meta document "[The Certification Process](/meta/certification.md)".

## Conventions and Definitions

The term "WebTech" or "Web Technologies" refers to modern applications, APIs, and protocols built upon the open and versatile platform of the Web. "Open WebTech" further extends this concept by emphasizing free and open-source software principles, inclusivity within a friendly community, and user-centricity. For a more detailed definition, see the meta document "[Definition of WebTech](/meta/webtech-definition.md)".

The term "Project" stands for a mostly collaborative endeavor that involves the development and management of software applications or services. Projects include, but are not limited to, web applications, tools, frameworks, and APIs designed for public use or organizational purposes.

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [IETF RFC 2119](https://datatracker.ietf.org/doc/html/rfc2119).

## Intended Audience and Reading Suggestions

This document is intended for developers, project managers, and organizations looking to align their software projects with OWTA's core values. Readers should have a basic understanding of open-source licensing, software development practices, and community management. For those new to these concepts, it is recommended to consult additional resources.

## Specification

### 1. Open Source Compliance

1. **Licensing:** Projects MUST be licensed under a Free/Libre and Open Source Software (FLOSS) license. Acceptable licenses include, but are not limited to, GPL, Apache, and MIT licenses. This requirement ensures that the software remains free to use, modify, and distribute.

2. **Access:** To allow for open access and collaboration, the project's source code MUST be hosted on a public repository platform such as GitHub or GitLab.

3. **Accepting Contributions:** Projects SHOULD include a `CONTRIBUTING(.md)` file, outlining how other developers can contribute to the project, the process for submitting pull requests, and guidelines for coding standards.

### 2. Quality Assurance

1. **Issue Tracking:** Projects MUST utilize an issue tracking system to manage and respond to user and contributor reports efficiently. This system MUST be publicly accessible to encourage community interaction.

2. **Testing:** All projects MUST include automated tests to verify functionality across updates. Continuous Integration (CI) SHOULD be set up to run tests automatically on all commits to the main branch of the repository.

3. **Security Practices:** Projects MUST adhere to current security best practices. Regular dependency updates are RECOMMENDED to mitigate vulnerabilities. A `SECURITY(.md)` file SHOULD be provided in the repository, providing users with information on how to report security issues and a brief overview of the project's security measures.

### 3. Release Process and Distribution

1. **Versioning:** Projects MUST implement a clear versioning policy, ideally adhering to [Semantic Versioning](https://semver.org/), to help users and developers track changes and updates effectively.

2. **Regular Updates:** Projects SHOULD demonstrate active maintenance through regular updates, feature enhancements, and bug fixes, showing ongoing commitment to improvement and community needs.

3. **Distribution Channels:** Projects SHOULD utilize multiple distribution channels like package managers to ensure wide accessibility and ease of installation.

### 4. Documentation and Support

1. **User Documentation:** Comprehensive user documentation MUST be provided, detailing setup, configuration, and usage instructions. This documentation SHOULD be accessible within the repository and, ideally, hosted on the project's webpage.

2. **Developer Documentation:** Technical documentation SHOULD be available for developers wishing to contribute to the project. This SHOULD include system architecture, module descriptions, API documentation, and setup instructions for a development environment.

### 5. User Experience

1. **Localization:** Efforts to localize the project to support multiple languages are RECOMMENDED to increase accessibility and global reach.

2. **Accessibility Features:** Projects MUST incorporate at least basic accessibility features to ensure usability by people with disabilities. This includes adhering to the [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/).

3. **Responsive Design:** Projects are RECOMMENDED to use responsive web design practices to ensure convenient usability across various devices and screen sizes.

### 6. Recommended Features

1. **API Extensibility:** Where applicable, offering an extensible API is RECOMMENDED for projects, allowing third-party developers to create plugins or extensions easily.

2. **Federation:** Where applicable, projects are RECOMMENDED to support federation to enhance interoperability and expand user networks. This includes adhering to common federation protocols and standards, like ActivityPub.

3. **Two-Factor Authentication:** For projects incorporating a user account system, it is RECOMMENDED to implement a Two-Factor Authentication (2FA) feature, especially for administrative and sensitive access levels. This should include options for both hardware and software token-based methods to provide flexibility and increased security for users.

### 7. Ease of Deployment

1. **Containerization:** To ensure that applications can be easily deployed and managed, projects SHOULD support containerization. This includes providing a `Dockerfile` and a `docker-compose.yml` template in the repository.

2. **Configuration Management:** Projects are RECOMMENDED to offer support for popular configuration management tools like Ansible, Chef, or Puppet to streamline the deployment process.

### 8. Coding Practices and Compatibility

1. **Coding Standards:** The use of modern coding practices and standards as well as a widely accepted, uniform coding style is REQUIRED to maintain good code quality and readability.

2. **Cross-platform Support:** It is RECOMMENDED that projects ensure compatibility with multiple operating systems and platforms to maximize user reach.

### 9. Community

1. **Welcoming Community:** It is RECOMMENDED that projects define a code of conduct that aligns with the principles of openness, collaboration, and inclusivity. This includes adding a `CODE_OF_CONDUCT(.md)` file in the repository. By establishing clear guidelines and expectations for behavior, projects can ensure that all participants feel valued and supported, promoting a healthier and more productive community interaction.

2. **Community Bridging:** When using walled garden services like Discord for the main community hub, it is RECOMMENDED to utilize solutions for bridging to multiple other, ideally open communication services. This approach ensures that the community remains open and accessible to a broad audience.
