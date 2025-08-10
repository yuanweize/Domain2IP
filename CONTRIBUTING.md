# Contributing to Domain Resolver

Thank you for your interest in contributing to Domain Resolver! 🎉

## How to Contribute

### Reporting Bugs 🐛

Before creating bug reports, please check the existing issues to avoid duplicates. When creating a bug report, include:

- **Clear description** of the problem
- **Steps to reproduce** the issue
- **Expected vs actual behavior**
- **Environment details** (Python version, OS, etc.)
- **Sample domain list** that causes the issue (if applicable)

### Suggesting Features 💡

Feature requests are welcome! Please:

- Check existing issues for similar requests
- Clearly describe the feature and its benefits
- Provide examples of how it would be used
- Consider backward compatibility

### Code Contributions 🔧

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes** following the coding standards below
4. **Test your changes** thoroughly
5. **Commit with clear messages**: `git commit -m 'Add amazing feature'`
6. **Push to your branch**: `git push origin feature/amazing-feature`
7. **Create a Pull Request**

## Coding Standards 📝

### Python Style Guide

- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- Use type hints where appropriate
- Write docstrings for all functions and classes
- Keep functions focused and small
- Use meaningful variable and function names

### Code Example

```python
def resolve_domain(domain: str) -> Dict[str, Any]:
    """
    Resolve a single domain to IP address.
    
    Args:
        domain: Domain name to resolve
        
    Returns:
        Dictionary containing resolution result
        
    Raises:
        socket.gaierror: If domain resolution fails
    """
    # Implementation here
    pass
```

### Testing

- Write tests for new features
- Ensure existing tests pass
- Test with various domain types and edge cases
- Include both positive and negative test cases

## Development Setup 🛠️

1. **Clone your fork**:
   ```bash
   git clone https://github.com/yourusername/domain-resolver.git
   cd domain-resolver
   ```

2. **Create virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install development dependencies**:
   ```bash
   pip install -r requirements-dev.txt
   ```

4. **Run tests**:
   ```bash
   python -m pytest
   ```

## Pull Request Guidelines 📋

### Before Submitting

- [ ] Code follows the style guidelines
- [ ] Self-review of the code completed
- [ ] Tests added for new functionality
- [ ] All tests pass
- [ ] Documentation updated if needed
- [ ] No breaking changes (or clearly documented)

### Pull Request Description

Please include:

- **Summary** of changes made
- **Motivation** for the changes
- **Testing** performed
- **Screenshots** (if UI changes)
- **Breaking changes** (if any)

## Code Review Process 👀

1. **Automated checks** must pass (if configured)
2. **Manual review** by maintainers
3. **Feedback incorporation** if requested
4. **Final approval** and merge

## Recognition 🏆

Contributors will be:

- Listed in the project's contributors section
- Mentioned in release notes for significant contributions
- Given credit in documentation updates

## Questions? 💬

Feel free to:

- Open an issue for discussion
- Reach out to maintainers
- Join community discussions

## Code of Conduct 🤝

This project follows a simple code of conduct:

- **Be respectful** and inclusive
- **Be constructive** in feedback
- **Be patient** with newcomers
- **Be collaborative** in problem-solving

Thank you for contributing to Domain Resolver! 🚀