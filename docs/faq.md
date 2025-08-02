# Frequently Asked Questions (FAQ)

## General Questions

### Q: What is the purpose of this playground repository?

A: This repository is designed as a safe environment to experiment with GitHub Projects features. You can test different configurations, workflows, and automations without affecting production projects.

### Q: Can I create real projects here or should I only experiment?

A: Feel free to create both experimental and real projects! This playground can serve as a learning environment and also host actual projects that benefit from the collaborative setup.

### Q: Who can contribute to this repository?

A: Anyone interested in learning about or improving GitHub Projects workflows! See our [Contributing Guidelines](../CONTRIBUTING.md) for more details.

## Technical Questions

### Q: How do I create my first GitHub Project?

A: Check out our [Getting Started Guide](getting-started.md) for step-by-step instructions on creating and configuring your first project.

### Q: What's the difference between repository projects and organization projects?

A: Repository projects (like this one) are scoped to a single repository and its issues/PRs. Organization projects can span multiple repositories and provide broader project management capabilities.

### Q: Can I use GitHub Projects API with this playground?

A: Yes! This repository is perfect for testing GitHub Projects API integrations. You can find example API usage in the [`docs/examples/api/`](examples/api/) directory.

### Q: How do I set up automation in GitHub Projects?

A: GitHub Projects offers built-in automation for common workflows. Check our [automation guide](automation.md) for examples and best practices.

## Workflow Questions

### Q: What view should I use for my project?

A: It depends on your needs:
- **Board View**: Great for Kanban-style workflows
- **Table View**: Best for detailed tracking and bulk operations  
- **Timeline View**: Perfect for deadline-driven work
- **Roadmap View**: Ideal for high-level planning

### Q: How many custom fields should I add?

A: Start with just the essential fields you need. You can always add more later. Common useful fields include Priority, Story Points, and Sprint.

### Q: Should I create separate projects for different types of work?

A: Generally yes. It's better to have focused projects for specific teams or initiatives rather than one large project that tries to handle everything.

## Troubleshooting

### Q: Why aren't my automation rules working?

A: Common issues include:
- Rules not being enabled
- Conflicting automation rules
- Incorrect trigger conditions
- Permissions issues

Check our [troubleshooting guide](troubleshooting.md) for more detailed solutions.

### Q: I can't see certain items in my project view. What's wrong?

A: This is usually due to filters being applied. Check:
- Active filters in your view
- Item status (archived items are hidden by default)
- Repository permissions for linked issues/PRs

### Q: How do I move items between projects?

A: Currently, GitHub Projects doesn't support directly moving items between projects. You'll need to:
1. Add the item to the new project
2. Remove it from the old project
3. Reconfigure any custom field values

## Best Practices

### Q: How often should I update my project?

A: For active projects, daily updates are ideal. At minimum, review and update your project weekly to keep it current and useful.

### Q: Should I archive completed items?

A: Yes, archiving completed items helps keep your active views clean while preserving the history for reference.

### Q: How do I train my team on using our project?

A: Start with our [Getting Started Guide](getting-started.md), then create team-specific documentation for your particular workflow and conventions.

## Getting Help

### Q: Where can I get help if I'm stuck?

A: You can:
- Check this FAQ and our documentation
- Search existing issues in this repository
- Create a new issue with the "question" label
- Join discussions in the GitHub Community forums

### Q: How do I report a bug in GitHub Projects?

A: For bugs in GitHub Projects itself, report them to GitHub Support. For issues with this playground repository, create an issue here using our bug report template.

### Q: Can I suggest new features for GitHub Projects?

A: Yes! You can suggest features through:
- GitHub's official feedback channels
- Creating a feature request issue in this repository for playground-specific improvements
- Participating in GitHub's beta programs

---

Don't see your question here? [Create an issue](https://github.com/anschn/github-projects-playgound/issues/new/choose) and we'll help you out! 💬