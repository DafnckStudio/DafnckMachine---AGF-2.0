# References

This document lists the primary source files provided by the user that formed the basis of this research and integration plan.

1.  **`.roomodes`**:
    *   **Path:** `/.roomodes`
    *   **Description:** JSON file defining the available AI agent modes, their roles, custom instructions, and capabilities within the existing swarm architecture. This was the target file for the proposed integration.

2.  **`01_AI-RUN/` Directory (and its contents):**
    *   **Path:** `/01_AI-RUN/`
    *   **Description:** Contains the sequential prompt files and templates that define the "AI-Assisted Development Workflow." Key files analyzed include:
        *   [`01_AI-RUN/01_Getting_Started.md`](01_AI-RUN/01_Getting_Started.md:1): Overview of the workflow, file naming, and initial AI agent onboarding.
        *   [`01_AI-RUN/02_AutoPilot.md`](01_AI-RUN/02_AutoPilot.md:1): Detailed orchestration logic, state management (`project_session_state.json`), error handling, persona adoption, and phase execution for the `01_AI-RUN` workflow.
        *   [`01_AI-RUN/03_Idea.md`](01_AI-RUN/03_Idea.md:1): Prompt and template for the "Idea Generation" phase.
        *   [`01_AI-RUN/04_Market_Research.md`](01_AI-RUN/04_Market_Research.md:1): Prompt for the "Market Research" phase.
        *   [`01_AI-RUN/05_Core_Concept.md`](01_AI-RUN/05_Core_Concept.md:1): Prompt for the "Core Concept Definition" phase.
        *   [`01_AI-RUN/06_PRD_Generation.md`](01_AI-RUN/06_PRD_Generation.md:1): Prompt for the "PRD Generation" phase, referencing [`01_AI-RUN/Template/PRD_template.md`](01_AI-RUN/Template/PRD_template.md:1).
        *   [`01_AI-RUN/07_Specs_Docs.md`](01_AI-RUN/07_Specs_Docs.md:1): Prompt for the "Technical Specifications & Documentation" phase, detailing template usage from `02_AI-DOCS` and `03_SPECS`, and specific MCP tool usage.
        *   [`01_AI-RUN/08_Start_Building.md`](01_AI-RUN/08_Start_Building.md:1): Prompt for the "Implementation" phase, including landing page creation and MCP usage.
        *   [`01_AI-RUN/09_Task_Manager.md`](01_AI-RUN/09_Task_Manager.md:1): Pointer to task management workflow documents.
        *   [`01_AI-RUN/10_Testing.md`](01_AI-RUN/10_Testing.md:1): Prompt for the "Testing & Preview Visibility" phase.
        *   [`01_AI-RUN/11_Deployment.md`](01_AI-RUN/11_Deployment.md:1): Prompt for the "Deployment" phase.
        *   [`01_AI-RUN/Template/PRD_template.md`](01_AI-RUN/Template/PRD_template.md:1): The structural template for `project_prd.md`.

3.  **`02_AI-DOCS/` Directory (and its contents):**
    *   **Path:** `/02_AI-DOCS/`
    *   **Description:** Contains templates for project-specific technical documentation and foundational AI guidance documents. Key subdirectories and files analyzed include:
        *   `02_AI-DOCS/Architecture/architecture_template.md`
        *   `02_AI-DOCS/Conventions/coding_conventions_template.md`
        *   `02_AI-DOCS/Conventions/design_conventions_template.md`
        *   `02_AI-DOCS/Documentation/AI_Design_Agent_Optimization.md`
        *   `02_AI-DOCS/Documentation/AI_Coding_Agent_Optimization.md`
        *   `02_AI-DOCS/Documentation/Codebase_Xray_Prompt.md`
        *   `02_AI-DOCS/Documentation/Optimizing_the_Design_Process.md`
        *   `02_AI-DOCS/TaskManagement/Roo_Task_Workflow.md`
        *   `02_AI-DOCS/TaskManagement/Tasks_JSON_Structure.md`

4.  **`03_SPECS/` Directory (and its contents):**
    *   **Path:** `/03_SPECS/`
    *   **Description:** Contains templates for feature/bugfix specifications and is the target for other generated specification documents. Key files/templates analyzed include:
        *   `03_SPECS/features/feature_spec_template.md`
        *   `03_SPECS/bugfixes/bugfix_spec_template.md`

These documents collectively formed the "user blueprint" for this research task. No external documents or live searches were used beyond the analysis of these provided files.