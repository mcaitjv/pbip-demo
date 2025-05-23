# Copilot Instructions

## Repository Content
This repository contains Power BI reports in PBIP (Power BI Project) format, located in the src folder. The repository is structured to include report definitions and semantic model defintions.

## Guidelines for Copilot

### File-Specific Instructions
- For '.tmdl' files:
    - Ensure that descriptions for measures and columns are generated accurately and placed in the correct locations within the '.tmdl' file structure.
    - Maintain the integrity of the '.tmdl' file by preserving all existing properties and syntax.
    - Avoid overwriting or removing any properties while inserting descriptions.
    - Validate the '.tmdl' file structure after generating descriptions to ensure it remains valid.
    - Use concise and meaningful descriptions that align with the purpose of the measure or column.
    - The format should be '/// Descriptions' here placed right above each 'table, 'column', or 'measure' identifier in the TMDL code.
    - Ensure comments provide clear explanations of the defintions and purpose of the table, column or measure, incorporating COMPANY X's business and data practices
- For '.dax' files: Provide explanations and optimization for DAX queries.

### Restrictions
- Keep in mind that existing descriptions are likely to be correct and validate but could potentially use improvements.

### Context for description generation
- This repository contains Power BI reports for COMPANY X
- COMPANY X sells ...
