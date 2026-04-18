# Microsoft Project (microsoft-project)
Microsoft Project is a project management software product developed by Microsoft. It provides tools for developing plans, assigning resources to tasks, tracking progress, managing budgets, and analyzing workloads. Microsoft Project offers REST APIs via SharePoint/Project Online, a Client-Side Object Model (CSOM), OData reporting feeds, and JavaScript APIs for building add-ins and integrations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/microsoft-project/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Budgeting, Gantt Charts, Microsoft, Portfolio Management, Project Management, Resource Management, Scheduling, Task Management

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-18

## APIs

### Microsoft Project Online REST API
REST API for accessing and managing Microsoft Project Online and Project Server data including projects, tasks, resources, assignments, calendars, custom fields, timesheets, lookup tables, and workflow activities. Uses SharePoint-based REST endpoints via the ProjectServer service.

**Human URL:** [https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013](https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013)

#### Tags:

 - Assignments, Calendars, Custom Fields, Projects, Resources, REST, Tasks, Timesheets

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013)
- [APIReference](https://learn.microsoft.com/en-us/office/client-developer/project/javascript-library-and-rest-reference-for-project-server-2013)
- [Authentication](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/authorization-and-authentication-of-sharepoint-add-ins)
- [CodeExamples](https://github.com/OfficeDev/Project-Samples/tree/main/O365-Project-Online-REST-Samples)
- [CodeExamples - REST CRUD Operations Sample](https://github.com/OfficeDev/Project-Add-in-REST-BasicDataOperations)
- [OpenAPI](openapi/microsoft-project-rest-api.yaml)
- [JSONSchema - Project Schema](json-schema/rest-api-project-schema.json)
- [JSONSchema - Task Schema](json-schema/rest-api-task-schema.json)
- [JSONSchema - Enterprise Resource Schema](json-schema/rest-api-enterprise-resource-schema.json)
- [JSONSchema - Assignment Schema](json-schema/rest-api-assignment-schema.json)
- [JSONSchema - Calendar Schema](json-schema/rest-api-calendar-schema.json)
- [JSONSchema - Custom Field Schema](json-schema/rest-api-custom-field-schema.json)
- [JSONSchema - TimeSheet Schema](json-schema/rest-api-time-sheet-schema.json)
- [JSONLD](json-ld/microsoft-project-rest-api-context.jsonld)

### Microsoft Project Online CSOM API
Client-Side Object Model API for programmatic access to Project Online and Project Server. Provides .NET, Silverlight, Windows Phone, and JavaScript interfaces for CRUD operations on projects, tasks, resources, assignments, custom fields, lookup tables, and enterprise project types.

**Human URL:** [https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013](https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013)

#### Tags:

 - .NET, Client Library, CSOM, JavaScript, Projects, Resources, Tasks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/client-developer/project/client-side-object-model-csom-for-project-2013)
- [SDK - .NET SDK](https://www.nuget.org/packages/Microsoft.SharePointOnline.CSOM/)
- [GettingStarted](https://learn.microsoft.com/en-us/office/client-developer/project/getting-started-with-the-project-server-csom-and-.net)

### Microsoft Project OData Reporting API
OData-based reporting feed for read-only access to Project Server and Project Online reporting data. Provides access to project, task, resource, assignment, and timesheet reporting tables and views via the ProjectData service endpoint.

**Human URL:** [https://learn.microsoft.com/en-us/office/client-developer/project/project-server-2013-architecture](https://learn.microsoft.com/en-us/office/client-developer/project/project-server-2013-architecture)

#### Tags:

 - OData, Projects, Reporting, Resources, Tasks

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/client-developer/project/project-server-2013-architecture)
- [Authentication](https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/authorization-and-authentication-of-sharepoint-add-ins)

### Microsoft Project JavaScript API
JavaScript API for building Office Add-ins that extend Microsoft Project desktop client. Enables reading task, resource, and view data from the active project within a task pane add-in.

**Human URL:** [https://learn.microsoft.com/en-us/office/dev/add-ins/project/project-add-ins](https://learn.microsoft.com/en-us/office/dev/add-ins/project/project-add-ins)

#### Tags:

 - Add-Ins, JavaScript, Office, Task Pane

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/office/dev/add-ins/project/project-add-ins)
- [Quickstart](https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/project-quickstart)
- [APIReference](https://learn.microsoft.com/en-us/javascript/api/office/office.context)
- [CodeExamples](https://developer.microsoft.com/en-us/microsoft-365/gallery/?filterBy=Project,Samples)

## Common Properties

- [Portal](https://developer.microsoft.com/en-us/microsoft-365)
- [DeveloperPortal](https://learn.microsoft.com/en-us/office/client-developer/project/project-programming-tasks)
- [Blog](https://techcommunity.microsoft.com/t5/project-blog/bg-p/ProjectBlog)
- [TermsOfService](https://www.microsoft.com/en-us/legal/terms-of-use)
- [PrivacyPolicy](https://privacy.microsoft.com/en-us/privacystatement)
- [Pricing](https://www.microsoft.com/en-us/microsoft-365/project/compare-microsoft-project-management-software)
- [Support](https://support.microsoft.com/)
- [GitHubRepository](https://github.com/OfficeDev/Project-Samples)
- [StackOverflow](https://stackoverflow.com/questions/tagged/ms-project)
- [Training](https://support.microsoft.com/en-us/project)
- [GettingStarted](https://learn.microsoft.com/en-us/office/client-developer/project/getting-started-developing-project-server-workflows)
- [GitHubOrganization](https://github.com/OfficeDev)
- [CodeExamples - Project Accelerator](https://github.com/OfficeDev/Project-Accelerator)
- [CodeExamples - Dataverse Plugin Sample](https://github.com/OfficeDev/Project-Dataverse-Plugin-Sample)

## Features

| Name | Description |
|------|-------------|
| Gantt Charts | Visual timeline charts for project scheduling with task dependencies, critical path analysis, and milestone tracking. |
| Task Management | Create, assign, and track tasks with predecessors, successors, constraints, and deadlines. |
| Resource Management | Assign resources to tasks, view workloads, and manage resource availability and capacity. |
| Portfolio Management | Manage multiple projects as a portfolio with prioritization, budgeting, and resource allocation across projects. |
| Budgeting and Cost Tracking | Track project costs, budgets, and earned value metrics for financial project management. |
| Scheduling Engine | Automatic scheduling with task dependencies, resource leveling, and critical path calculation. |
| Timesheets | Time tracking and approval workflows for resource hours and project progress reporting. |
| Custom Fields | Define enterprise custom fields, lookup tables, and formulas for extended project metadata. |
| Reporting and Dashboards | Pre-built and custom reports with Power BI integration for project, resource, and portfolio analytics. |
| Workflow Automation | Demand management workflows for project proposals, approvals, and stage-gate governance. |
| Collaboration | SharePoint-based project sites with document libraries, issue tracking, and team communication. |
| Power Platform Integration | Integration with Power BI, Power Automate, and Power Apps for extended project management scenarios. |

## Use Cases

| Name | Description |
|------|-------------|
| IT Project Management | Plan and track IT infrastructure, software development, and digital transformation projects. |
| Construction Project Planning | Schedule construction phases, manage subcontractors, and track material costs. |
| Product Development | Coordinate product development timelines, milestones, and cross-functional team resources. |
| Portfolio Optimization | Evaluate and prioritize project portfolios based on strategic alignment, ROI, and resource constraints. |
| Resource Capacity Planning | Forecast resource demand, identify bottlenecks, and optimize resource allocation across projects. |
| Program Management | Manage interdependent projects as programs with shared resources and coordinated timelines. |
| Agile Project Tracking | Track agile sprints, backlogs, and team velocity alongside traditional waterfall schedules. |
| Compliance Reporting | Generate audit trails and compliance reports for project governance and regulatory requirements. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft Teams | View and manage project tasks directly within Microsoft Teams channels and tabs. |
| Power BI | Connect to Project Online data for interactive dashboards and portfolio analytics. |
| SharePoint | SharePoint-based project sites for document management, collaboration, and task synchronization. |
| Microsoft 365 | Deep integration with Outlook, Excel, Word, and other Microsoft 365 applications. |
| Power Automate | Automate project workflows, notifications, and approvals using Power Automate flows. |
| Power Apps | Build custom project management applications using Power Apps with Project data. |
| Azure DevOps | Connect project schedules with Azure DevOps work items for software development projects. |
| Microsoft Planner | Integrate lightweight task planning in Planner with enterprise project management in Project. |
| Dataverse | Project for the web stores data in Microsoft Dataverse, enabling custom integrations and extensions. |
| Excel | Export and import project data to Excel for custom analysis, reporting, and data manipulation. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Microsoft Project Online REST API](openapi/microsoft-project-rest-api.yaml)

### JSON Schema

- [Project Schema](json-schema/rest-api-project-schema.json)
- [Task Schema](json-schema/rest-api-task-schema.json)
- [Enterprise Resource Schema](json-schema/rest-api-enterprise-resource-schema.json)
- [Assignment Schema](json-schema/rest-api-assignment-schema.json)
- [Calendar Schema](json-schema/rest-api-calendar-schema.json)
- [Custom Field Schema](json-schema/rest-api-custom-field-schema.json)
- [TimeSheet Schema](json-schema/rest-api-time-sheet-schema.json)

### JSON Structure

- [Project Structure](json-structure/rest-api-project-structure.json)
- [Task Structure](json-structure/rest-api-task-structure.json)
- [Enterprise Resource Structure](json-structure/rest-api-enterprise-resource-structure.json)
- [Assignment Structure](json-structure/rest-api-assignment-structure.json)
- [Calendar Structure](json-structure/rest-api-calendar-structure.json)
- [Custom Field Structure](json-structure/rest-api-custom-field-structure.json)
- [TimeSheet Structure](json-structure/rest-api-time-sheet-structure.json)

### JSON-LD

- [Microsoft Project REST API Context](json-ld/microsoft-project-rest-api-context.jsonld)

### Examples

- [Project Example](examples/rest-api-project-example.json)
- [Task Example](examples/rest-api-task-example.json)
- [Enterprise Resource Example](examples/rest-api-enterprise-resource-example.json)
- [Assignment Example](examples/rest-api-assignment-example.json)
- [Calendar Example](examples/rest-api-calendar-example.json)
- [Custom Field Example](examples/rest-api-custom-field-example.json)
- [TimeSheet Example](examples/rest-api-time-sheet-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Microsoft Project Online REST API](capabilities/shared/project-rest-api.yaml) — 18 operations for project, task, resource, and calendar management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Project Management](capabilities/project-management.yaml) | Project REST API | 18 | Project Manager, PMO |

## Vocabulary

- [Microsoft Project Vocabulary](vocabulary/microsoft-project-vocabulary.yaml) — Unified taxonomy mapping 12 resources, 10 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Microsoft Project Spectral Rules](rules/microsoft-project-spectral-rules.yml) — 39 rules across 13 categories enforcing Microsoft Project API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
