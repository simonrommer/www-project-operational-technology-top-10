# Related Documents and Standards

In this document, we will explore the unique challenges and differences between OT networks and traditional IT networks. We will also discuss the relationship between the OWASP OT Top 10 and other relevant projects and international standards, such as the OWASP Top 10, OWASP IoT TOP 10, ISO 27001, ISO 62443, and the European Union NIS2 directive.

## Relationship to other OWASP standards

### OWASP IoT Top 10

In OT we often analyze whole factory floors or power plants, situating our list of Top 10 vulnerabilities on a higher conceptional level. In addition, OT is burdened with long lifetimes and problematic update cycles placing a greater importance on defense-in-depth measures like good network segregation.

(I)IoT is a part of OT, but OT is broader in scope and utilized IoT devices within. This difference in scope is reflected in the Top Vulnerability list: when using the IoT Top 10, only 2 out of the 10 top vulnerabilities directly map onto the OT domain (I4 and I5).

## Related OT standards

### EU NIS2 Directive

- Technical and Organizational Aspects
- Mandatory reporting of any incident that has a significant impact
  - early warning within 24h, incident notifications in 72h, final report not alter than one month after the incident notification. That's gonna be fun.
- high fines
- authorities must be empowered to audit essential entities
- give an overview of a company's obligations, is this targeted against vendors, integrators or operators?

### EU Cyber Resilience Act

- boundaries conditions for the development of secure products with digital elements
- essential requirements, vulnerability handling process

### NIST SP800-82

### IEC 62443

Series of standards, e.g.,

- IEC 62443-2-1: Establish IACS Security Program
- IEC 62443-2-4: Integration and Maintenance Requirements
- IEC 62443-3-2: Security Levels for Zones and Conduits
- IEC 62443-3-3: System Security Requirements
- IEC 62443-4-1: Product Development Requirements
- IEC 62443-4-2: Technical Security Requirements
