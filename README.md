# docs-product-requirements.md
1. Title: Container Image Vulnerability Dashboard
2. Overview
This product enables users to scan container images for known vulnerabilities, view detailed findings, and prioritize remediation based on severity. It targets DevOps, Security Engineers, and Platform Engineers who manage large repositories of container images.

3. Goals
Provide a centralized dashboard to track vulnerabilities in container images.

Allow filtering, sorting, and prioritization of images based on vulnerability severity.

Enable users to drill down into specific vulnerabilities and get remediation guidance.

4. User Stories
As a user, I want to see a list of container images with their vulnerability status.

As a user, I want to filter images by severity (Critical, High, Medium, Low).

As a user, I want to sort images by the number of vulnerabilities or severity.

As a user, I want to click into an image to view details about each vulnerability.

As a user, I want to export a list of vulnerable images for action tracking.

5. Features
a. Dashboard Overview
Total scanned images

Number of images with vulnerabilities (grouped by severity)

Pie or bar chart showing severity distribution

b. Image Table View
Columns: Image Name, Tags, Scan Date, Total Vulnerabilities, Critical, High, Medium, Low, Last Updated

Actions: View Details, Export, Re-scan

c. Image Details View
Image metadata

List of vulnerabilities: Name, CVE, Severity, Package Name, Version, Fix Available (Y/N)

Filters by severity

Sorting options

Fix recommendations

d. Search & Filters
Search by image name/tag

Filters: Severity, Fix available, Date range

e. Notifications/Alerts (Optional for V1)
Set alerts for images with Critical/High vulnerabilities

