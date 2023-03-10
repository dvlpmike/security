# Software Bill of Materials (SBOM)

## What is SBOM?

- A Software Bill of Materials (SBOM) is a detailed list of all components and dependencies in a software application.
- It provides a complete inventory of all software components used in an application, including open source libraries, commercial software, and custom code.
- The purpose of an SBOM is to help organizations manage and secure their software supply chain by identifying potential security vulnerabilities and ensuring compliance with licensing obligations.

## Key Elements of an SBOM:

- Component Name: The name of the software component
- Component Version: The version of the software component
- License Information: The license(s) under which the software component is released
- Dependencies: Other software components required by the component
- Origin: The source of the software component (e.g. open source library, commercial software, custom code)
- Hash: A unique identifier for the software component to ensure its integrity and authenticity

## Benefits of SBOM:

- Improved Security: SBOM helps identify potential vulnerabilities and allows organizations to quickly respond to security incidents.
- Compliance: SBOM helps organizations manage licensing and compliance obligations by identifying open source and commercial components used in the software application.
- Risk Management: SBOM helps organizations manage supply chain risks by identifying dependencies and potential points of failure.
- Transparency: SBOM provides transparency and visibility into the software supply chain, which helps build trust with customers, partners, and stakeholders.

## SBOM Standards:

- SPDX: SPDX (Software Package Data Exchange) is a standard for communicating SBOM information. It provides a standard format for identifying software components, their versions, and their licenses.
- CycloneDX: CycloneDX is an SBOM standard that aims to simplify the exchange of SBOM information. It provides a standard format for describing software components, their dependencies, and their associated metadata.
- SWID: SWID (Software Identification) is a standard for identifying software components. It provides a unique identifier for each software component, which can be used to track its use and ensure compliance with licensing obligations.

## References
- https://www.cisa.gov/sbom
- https://github.com/microsoft/sbom-tool
