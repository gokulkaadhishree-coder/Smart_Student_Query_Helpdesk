# Smart Student Query Helpdesk

An AI-powered student helpdesk workflow built with **UiPath RPA and
Generative AI concepts**. It is designed to classify student queries and
route them toward an appropriate resolution path, reducing repetitive
manual handling.

## Overview

Students may submit questions in different formats and about different
topics. This project explores how an automated workflow can process
incoming queries, use AI/NLP-based reasoning to understand the request,
and direct it to the relevant handling path.

## Key capabilities

-   **Query classification:** Categorizes incoming student queries to
    support consistent handling.
-   **Automated routing:** Directs queries toward an appropriate
    resolution path based on the workflow logic.
-   **Structured and unstructured inputs:** Designed to handle query
    information that may not always arrive in the same format.
-   **Workflow automation:** Uses UiPath to connect the processing
    steps.
-   **Prompt-driven AI processing:** Uses prompt engineering to guide
    AI-assisted interpretation where configured.

## Workflow at a glance

1.  Receive or read a student query.
2.  Extract the available query information.
3.  Process the query using the configured classification and decision
    logic.
4.  Route the query to the appropriate next step.
5.  Review the resulting output or status.

> The exact input source, AI provider, routing destinations, and
> activities depend on the workflow configuration included in this
> repository.

## Technology

-   UiPath Studio
-   UiPath RPA workflow activities
-   Prompt engineering / Generative AI concepts
-   NLP-based query interpretation and decision logic

## Getting started

1.  Clone or download this repository.
2.  Open the project in a compatible version of UiPath Studio.
3.  Review the workflow and its configured input sources, activities,
    and any required connections.
4.  Configure credentials or integration settings locally if the
    workflow uses external services. Do not commit API keys, passwords,
    or personal data.
5.  Run the workflow with sample queries and check the output at each
    step.

This repository does not specify universal installation commands because
UiPath project dependencies and external connections can vary by
exported project configuration.

## Testing suggestions

Try queries from different categories and with different wording. Check
whether the workflow classifies each query as expected and routes it to
the intended path. Include ambiguous or incomplete queries to understand
how the workflow handles them.

## Notes

-   AI-generated classifications or responses should be reviewed when
    the query is sensitive or requires an official answer.
-   Use synthetic or anonymized student data for testing.
-   Do not place real student records or credentials in the public
    repository.

## Author

**Adhishree Gokulka**

-   GitHub:
    [gokulkaadhishree-coder](https://github.com/gokulkaadhishree-coder)

------------------------------------------------------------------------

*Built as a practical project exploring AI-assisted query handling and
UiPath workflow automation.*
