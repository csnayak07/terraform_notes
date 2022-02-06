# Concept of workspace
Workspaces allow the use of the same configuration but having separate state backends for each workspace. One use case is having production and dev workspaces. This allows the same setup for both environments but each with their own state. When working in the dev workspace you can ensure that you are only modifying that infrastructure and not production. This is great for testing changes without affecting other environments. 

# topics to cover when working on multiple workspace
- Use the CLI to create, update, switch, list, show and delete workspaces
- Use dev.tfvars and prod.tfvars files to set different variables depending on the workspace
- Examine the different state between workspaces
- Access the current workspace in config files with terraform.workspace

# Course Examples:
https://github.com/WillBrock/terraform-course-examples

# Documentation:
https://www.terraform.io/docs/state/workspaces.html

