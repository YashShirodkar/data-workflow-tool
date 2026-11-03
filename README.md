Data Pipeline Flow

An interactive map of a data pipeline, from source system to final dashboard. Select any stage, or any connection between stages, to see its purpose, the code behind it, the commands used to run it, the repository it lives in, the owning team and the right point of contact.

Live demo: https://yashshirodkar.github.io/data-workflow-tool/

The tool contains no customer data. It shows documentation and structure only, so it is safe to use in walkthroughs and knowledge-transfer sessions.

What it is:

Data Pipeline Flow turns a pipeline that usually lives in people's heads, wikis and scattered repositories into a single clickable page. The demo follows one example pipeline:

Customer API  ->  Database  ->  S3  ->  Glue and Athena  ->  Snowflake  ->  Power BI

Each stage (a system) and each arrow (the process that moves data between two systems, such as a Lambda function, a Spark job, a crawler or Snowpipe) is clickable.

Who it is for
Data engineers, analytics engineers and data platform teams, and the engineering managers and data leads who oversee them.
New team members, and anyone handing over or taking over a pipeline.
Cross-functional teams who mainly work with the final product, such as a dashboard or report, and are unsure who owns the underlying data or whom to contact when there is a data issue.
Why it matters

Knowledge of how data moves through a stack often sits with a few individuals or is spread across tools, wikis and repositories. When an incident occurs or a team member leaves, it becomes hard to tell what feeds what, who owns each step and where the code lives.

Most lineage and catalog tools focus on data assets and table-level lineage. Few treat each movement step as an owned object with its own code location and commands. This project aims to give teams one reference for knowledge transfer, and to give business teams a clear answer to "who do I contact about this data?"
