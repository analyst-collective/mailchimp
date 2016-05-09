### analyst-collective/mailchimp

A collection of SQL-based analytics for Mailchimp.

### Usage

All data models are built to be compiled and run with [dbt](https://github.com/analyst-collective/dbt). After installing dbt and creating a new project, use the analytics in this repo by adding it as a dependency to your project and running `dbt deps`.

### Contributing
Contributions are welcome! To contribute:
- fork this repo,
- build a test dataset,
- make and test changes, and
- submit a PR.

Two important notes:
- All contributions must be widely relevant to Mailchimp customers and not contain logic specific to a given business.
- PRs without accompanying datasets cannot be tested and therefore will not be accepted. We suggest you use [data-generator](https://github.com/analyst-collective/data-generator) to generate your test datasets.
