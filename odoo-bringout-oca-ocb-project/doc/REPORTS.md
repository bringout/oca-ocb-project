# Reports

Report definitions and templates in project.

```mermaid
classDiagram
    class ReportProjectTaskUser
    Model <|-- ReportProjectTaskUser
    class ReportProjectTaskBurndownChart
    AbstractModel <|-- ReportProjectTaskBurndownChart
```

## Available Reports

### Analytical/Dashboard Reports
- **Tasks Analysis** (Analysis/Dashboard)
- **Burndown Chart** (Analysis/Dashboard)


## Report Files

- **__init__.py** (Python logic)
- **project_report.py** (Python logic)
- **project_report_views.xml** (XML template/definition)
- **project_task_burndown_chart_report.py** (Python logic)
- **project_task_burndown_chart_report_views.xml** (XML template/definition)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
