# Contributing to AI Research Agent

Thank you for your interest in contributing to the AI Research Agent project! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

### Types of Contributions

We welcome various types of contributions:

- **Bug Reports**: Help us identify and fix issues
- **Feature Requests**: Suggest new functionality
- **Code Contributions**: Implement new features or fix bugs
- **Documentation**: Improve guides, README, and code comments
- **Testing**: Help ensure code quality and reliability
- **Examples**: Create sample implementations or use cases

### Before You Start

1. **Check existing issues**: Search for similar issues or feature requests
2. **Read the documentation**: Understand the project structure and goals
3. **Set up your environment**: Follow the setup guide in `docs/setup_guide.md`

## 🚀 Development Setup

### Prerequisites
- Python 3.11+
- Git
- IBM Cloud account with watsonx.ai Studio access

### Local Development
1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/yourusername/ai-research-agent-ibm-granite.git
   cd ai-research-agent-ibm-granite
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Set up your IBM Cloud credentials
6. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📝 Code Style Guidelines

### Python Code
- Follow PEP 8 style guidelines
- Use meaningful variable and function names
- Add type hints where appropriate
- Include docstrings for functions and classes
- Keep functions focused and concise

### Jupyter Notebooks
- Clear cell structure and organization
- Descriptive markdown cells
- Proper code comments
- Clean output (remove unnecessary prints)
- Include setup and configuration cells

### Documentation
- Use clear, concise language
- Include code examples where helpful
- Update README.md for significant changes
- Add inline comments for complex logic

## 🔧 Making Changes

### Code Changes
1. Make your changes in your feature branch
2. Test your changes thoroughly
3. Update documentation if needed
4. Ensure all tests pass (if applicable)

### Commit Guidelines
Use conventional commit messages:
```
type(scope): description

[optional body]

[optional footer]
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

Examples:
```
feat(research): add support for multiple paper formats
fix(api): resolve authentication timeout issue
docs(readme): update installation instructions
```

## 🧪 Testing

### Before Submitting
- Test your changes with different inputs
- Verify functionality works as expected
- Check for any breaking changes
- Ensure code follows style guidelines

### Testing Checklist
- [ ] Code runs without errors
- [ ] All functions work as intended
- [ ] Documentation is updated
- [ ] No sensitive data is exposed
- [ ] Performance is acceptable

## 📤 Submitting Changes

### Pull Request Process
1. Push your changes to your fork
2. Create a pull request against the main branch
3. Fill out the pull request template
4. Provide clear description of changes
5. Link any related issues

### Pull Request Template
```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Other (please describe)

## Testing
- [ ] Tested locally
- [ ] Updated documentation
- [ ] No breaking changes

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] No sensitive data exposed
```

## 🐛 Reporting Issues

### Bug Reports
When reporting bugs, please include:
- Clear description of the problem
- Steps to reproduce the issue
- Expected vs actual behavior
- Environment details (OS, Python version, etc.)
- Error messages or logs
- Screenshots if applicable

### Feature Requests
For feature requests, please include:
- Detailed description of the feature
- Use case and benefits
- Implementation suggestions (if any)
- Priority level

## 📋 Review Process

### What We Look For
- Code quality and style
- Functionality and correctness
- Documentation updates
- Test coverage
- Security considerations
- Performance impact

### Review Timeline
- Initial review: Within 1-2 days
- Follow-up reviews: As needed
- Merge decision: Based on review feedback

## 🏆 Recognition

Contributors will be recognized in:
- Project README.md
- Release notes
- GitHub contributors list
- Project documentation

## 📞 Getting Help

If you need help with contributing:
- Check existing documentation
- Search for similar issues
- Ask questions in GitHub Discussions
- Contact maintainers for guidance

## 📜 Code of Conduct

We are committed to providing a welcoming and inclusive environment. Please:
- Be respectful and considerate
- Use inclusive language
- Focus on constructive feedback
- Help others learn and grow

## 🎯 Project Goals

Our mission is to:
- Make academic research more accessible
- Demonstrate AI capabilities in research
- Build a collaborative community
- Create high-quality, reusable tools

Thank you for contributing to the AI Research Agent project! 🚀 