# Contributing to Awesome AI Models Matrix

Thank you for your interest in contributing to the Awesome AI Models Matrix! This document provides guidelines and instructions for contributing to this project.

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Types of Contributions](#types-of-contributions)
- [Contribution Standards](#contribution-standards)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)
- [Verification Requirements](#verification-requirements)
- [Code of Conduct](#code-of-conduct)

---

## How to Contribute

1. **Fork the Repository**: Create your own fork of the project
2. **Create a Branch**: Make a new branch for your contribution
3. **Make Your Changes**: Follow the guidelines below
4. **Submit a Pull Request**: Describe your changes clearly
5. **Wait for Review**: Maintainers will review and provide feedback

---

## Types of Contributions

We welcome the following types of contributions:

### 1. Adding New Models

When adding a new AI model, please include:

- **Model Name**: Official name and version
- **Company/Organization**: Who developed it
- **Release Date**: When it was released (YYYY-MM-DD format)
- **Coding Ability**: Assessment based on benchmarks
- **Benchmarks**: HumanEval, MMLU, or equivalent scores
- **Pricing**: Input/output costs per 1M tokens (USD)
- **Self-Hosting**: License type and availability
- **Official Website**: Direct link to official documentation

**Example**:

```markdown
| **NewAI** | SuperModel 1.0 | SuperModel 1.0 | 2025-10-15 | ✅ Excellent | 85% / 88% | $2.00 / $8.00 | ✅ Apache 2.0 | [newai.com](https://newai.com) |
```

### 2. Updating Existing Information

- **New Versions**: Update version numbers and release dates
- **Price Changes**: Update pricing with date of change
- **Benchmark Updates**: Add new benchmark scores with sources
- **Link Updates**: Fix broken or outdated links

### 3. Improving Documentation

- **Clarifications**: Make explanations clearer
- **Examples**: Add helpful examples
- **Corrections**: Fix typos, grammar, or formatting
- **Translations**: Add translations (if applicable)

### 4. Adding Resources

- **Tutorials**: Links to quality tutorials
- **Case Studies**: Real-world usage examples
- **Tools**: Deployment and benchmarking tools
- **Research Papers**: Academic publications

---

## Contribution Standards

### Required Information

All model entries MUST include:

1. ✅ **Official Source**: Link to official announcement or documentation
2. ✅ **Verification**: At least one authoritative source (company website, press release, Wikipedia)
3. ✅ **Accuracy**: Information must be current and factual
4. ✅ **Completeness**: All table columns filled (use "N/A" if not applicable)

### Quality Standards

- **Authoritative Sources**: Use official documentation, not rumors or speculation
- **Recent Information**: Prefer sources from the last 6 months
- **Multiple Sources**: Cross-verify critical information
- **Direct Links**: Link directly to relevant pages, not homepages

### Acceptable Sources

✅ **Approved**:
- Official company websites and documentation
- Official company blogs and press releases
- GitHub repositories from official organizations
- Academic papers from reputable journals
- Major tech news outlets (TechCrunch, The Verge, etc.)
- Wikipedia (as secondary source)
- Cloud provider documentation (AWS, Azure, GCP)

❌ **Not Approved**:
- Social media posts (unless official company accounts)
- Personal blogs without verification
- Reddit or forum discussions
- Unverified third-party websites
- Speculation or rumors

---

## Pull Request Process

### Before Submitting

1. **Check Existing Issues**: Ensure your contribution isn't already in progress
2. **Read the Guidelines**: Familiarize yourself with this document
3. **Test Your Changes**: Ensure markdown renders correctly
4. **Update the Date**: Change "Last Updated" date if making significant changes

### PR Description Template

```markdown
## Type of Change
- [ ] New model addition
- [ ] Model information update
- [ ] Documentation improvement
- [ ] Bug fix (broken link, typo, etc.)
- [ ] Other (please describe)

## Description
Brief description of your changes

## Sources
- [Official Documentation](https://example.com)
- [Benchmark Results](https://example.com)
- [Press Release](https://example.com)

## Checklist
- [ ] Information is accurate and verified
- [ ] All required fields are filled
- [ ] Links are working and point to official sources
- [ ] Markdown formatting is correct
- [ ] No duplicate entries
- [ ] Sources are authoritative
```

### Review Process

1. **Automated Checks**: Links and formatting verified
2. **Maintainer Review**: Content accuracy checked
3. **Feedback**: You may receive requests for changes
4. **Approval**: Merged when requirements met

---

## Style Guidelines

### Markdown Formatting

- **Headers**: Use proper hierarchy (H1 → H6)
- **Tables**: Align columns consistently
- **Links**: Use descriptive text, not "click here"
- **Lists**: Use bullet points or numbered lists appropriately

### Table Formatting

```markdown
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Data     | Data     | Data     |
```

### Date Formatting

- Use **YYYY-MM-DD** format (e.g., 2025-10-15)
- Use **YYYY-MM** if exact day unknown (e.g., 2025-10)
- Use **YYYY** if only year known (e.g., 2025)

### Price Formatting

- Use **$X.XX / $X.XX** format (e.g., $1.25 / $10.00)
- Always include two decimal places
- Use "Free" for free models
- Use "Varies" if pricing is complex

### Benchmark Formatting

- Use **XX% / XX%** format (e.g., 85% / 88%)
- Use **~XX%** for approximate values (e.g., ~85%)
- Use **N/A** if not applicable
- Note benchmark type in column header

### Emoji Usage

- ✅ for "Yes" or positive attributes
- ❌ for "No" or restrictions
- 🚀 for highlights or new releases
- ⭐ for notable features
- 📊 for benchmarks and metrics

---

## Verification Requirements

### For New Model Additions

Provide at least **two** of the following:

1. **Official announcement** from company
2. **Documentation page** with model details
3. **API documentation** showing pricing
4. **Press release** or major news coverage
5. **Research paper** (for research models)
6. **GitHub repository** (for open-source models)

### For Benchmark Claims

Provide:

1. **Official benchmark** publication or leaderboard
2. **Company-published** benchmark results
3. **Independent verification** from reputable source

### For Pricing Information

Provide:

1. **Official pricing page** link
2. **API documentation** with rates
3. **Recent announcement** if recently changed

---

## Code of Conduct

### Our Standards

- **Be Respectful**: Treat all contributors with respect
- **Be Constructive**: Provide helpful, actionable feedback
- **Be Collaborative**: Work together toward common goals
- **Be Honest**: Don't submit false or misleading information
- **Be Professional**: Keep discussions on-topic and productive

### Unacceptable Behavior

- Harassment, discrimination, or personal attacks
- Trolling, inflammatory comments, or spam
- Deliberately submitting false information
- Plagiarism or copyright violation
- Any illegal activity

### Enforcement

Violations may result in:
1. Warning from maintainers
2. Temporary ban from contributing
3. Permanent ban for serious or repeated violations

---

## Questions?

If you have questions about contributing:

1. **Check the README**: Many questions are answered there
2. **Open an Issue**: Use the "Question" template
3. **Discussion Board**: For general discussions
4. **Email Maintainers**: For private concerns

---

## Recognition

Contributors who make significant contributions will be:

- Listed in the CONTRIBUTORS.md file
- Mentioned in release notes
- Acknowledged in the README

---

## License

By contributing, you agree that your contributions will be licensed under the same license as the project (GPL-3.0).

---

## Additional Notes

### Monthly Updates

We aim to update the matrix monthly with:
- New model releases
- Version updates
- Price changes
- Benchmark updates

Contributors who help with monthly updates are especially appreciated!

### Prioritization

We prioritize contributions that:
1. Add frontier models from major AI companies
2. Update critical information (pricing, versions)
3. Add open-source alternatives
4. Fix broken or outdated links
5. Improve documentation clarity

---

Thank you for contributing to Awesome AI Models Matrix! 🚀

Your contributions help developers, researchers, and decision-makers stay informed about the rapidly evolving AI landscape.