# Data

No data files are stored in this repository.

The dataset (`project_itsm.dataset_list`, ~46,600 tickets × 25 columns, Feb 2012 to Mar 2014) was provided through a read-only MySQL database as part of the DataMites Project Mentoring programme (project PM-PR-0012). It is not redistributed here; the course materials are proprietary.

To rerun the notebook, set the connection details as environment variables (see `.env.example` in the repo root).

Key columns: `CI_Cat`, `CI_Subcat`, `WBS`, `Impact`, `Urgency`, `Priority`, `Category`, `Open_Time`, `Close_Time`, `No_of_Reassignments`, `No_of_Related_Incidents`, `No_of_Related_Changes`, `Closure_Code`.
