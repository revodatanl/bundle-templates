# RevoData Bundle Templates

The `RevoData Bundle Templates` contains our custom templates for Databricks Asset Bundles. The template should initate a complete development environment for new Databricks projects, including GitHub Actions, pre-commit hooks, and example pipelines and jobs that can be deployed to Databricks.

## Getting started

1. Install the Databricks CLI from <https://docs.databricks.com/dev-tools/cli/databricks-cli.html>

2. Initialize a new project using the template:

   ```bash
   databricks bundle init https://github.com/revodatanl/bundle-templates
   ```

This will create a new directory with the template files. You can now start developing your project.
