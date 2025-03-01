# GitHub Automation Workflows

This repository contains automated GitHub workflows that help streamline our development process. These workflows handle routine tasks automatically, reducing manual effort and ensuring consistency across our projects.

## Setup and Configuration

### Prerequisites
- GitHub repository with Actions enabled
- Appropriate permissions to create and modify workflows

### Installation

1. Copy the workflow files to your repository:
   - `.github/workflows/auto-assign.yml`
   - `.github/workflows/auto-label.yml`
   - `.github/workflows/promotion-merge.yml`

2. Create or modify configuration files:
   - `.github/auto-assign.yml`
   - `.github/auto-label.yml`
   - `.github/promotion-config.yml`

3. Customize the configuration files to match your project's requirements.

## Troubleshooting

### Common Issues

1. **Workflow not running**
   - Check workflow permissions in repository settings
   - Verify workflow file syntax
   - Ensure workflow triggers are correctly defined

2. **Auto-assign not working**
   - Check that team names are correct
   - Verify file path patterns
   - Ensure reviewers have proper permissions

3. **Auto-label not applying labels**
   - Verify label names exist in repository
   - Check pattern matching rules
   - Ensure workflow has permission to apply labels

4. **Promotion merge failures**
   - Check for conflicts between branches
   - Verify required checks are passing
   - Ensure branch protection rules allow the workflow to merge

## Contributing

To contribute to these workflows:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-workflow`)
3. Commit your changes (`git commit -m 'Add some amazing workflow'`)
4. Push to the branch (`git push origin feature/amazing-workflow`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
