# Contributing to Biased-Tech-Notes

Thank you for your interest in contributing to this technical blog repository! This guide will help you create high-quality, professional technical content.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Blog Post Guidelines](#blog-post-guidelines)
3. [Writing Style](#writing-style)
4. [Code Examples](#code-examples)
5. [Submission Process](#submission-process)
6. [Review Criteria](#review-criteria)

---

## Getting Started

### Before You Write

1. **Check existing content** to avoid duplication
2. **Choose a relevant topic** that provides value to software developers
3. **Research thoroughly** to ensure accuracy and completeness
4. **Plan your outline** before writing

### Repository Structure

```
Biased-Tech-Notes/
├── blogs/
│   ├── .templates/
│   │   └── blog-template.md
│   ├── [topic-category]/
│   │   └── your-blog-post.md
│   └── README.md
├── docs/
│   └── [additional-documentation]
├── CONTRIBUTING.md
└── README.md
```

---

## Blog Post Guidelines

### Using the Template

1. Copy the template from `blogs/.templates/blog-template.md`
2. Create a new directory under `blogs/` for your topic category if it doesn't exist
3. Name your file using kebab-case: `descriptive-topic-name.md`
4. Fill in all sections of the template

### Naming Conventions

- **File names:** Use lowercase with hyphens (e.g., `understanding-async-await.md`)
- **Directory names:** Category names in lowercase (e.g., `javascript`, `devops`, `architecture`)

### Required Sections

Every blog post must include:

- ✅ Clear title and metadata (author, date, tags)
- ✅ Abstract/Summary
- ✅ Table of contents for posts > 5 minutes reading time
- ✅ Well-structured main content
- ✅ Code examples (where applicable)
- ✅ Conclusion with key takeaways
- ✅ References and citations

---

## Writing Style

### Technical Writing Best Practices

1. **Be Clear and Concise**
   - Use simple, direct language
   - Avoid jargon unless necessary (and explain it when used)
   - Break complex ideas into digestible chunks

2. **Be Professional**
   - Maintain a professional yet approachable tone
   - Avoid slang and informal language
   - Respect diverse audiences and perspectives

3. **Be Accurate**
   - Verify all technical information
   - Test all code examples
   - Cite sources and give credit

4. **Be Practical**
   - Focus on real-world applications
   - Include working examples
   - Address common use cases

### Formatting Guidelines

- Use **bold** for emphasis and important terms
- Use `code formatting` for code elements, commands, and file names
- Use proper heading hierarchy (H2, H3, H4)
- Include code syntax highlighting
- Add images/diagrams where helpful (in PNG or SVG format)

---

## Code Examples

### Requirements for Code

1. **Must be tested and working**
   - All code examples should be executable
   - Test before including

2. **Include comments**
   - Explain complex logic
   - Highlight important concepts
   - Keep comments concise

3. **Follow best practices**
   - Use appropriate naming conventions
   - Follow language-specific style guides
   - Include error handling where relevant

4. **Specify language**
   ```language
   // Always specify the programming language in code blocks
   ```

### Code Example Template

```language
// Brief description of what this code does
function exampleFunction(param) {
    // Step 1: Explanation
    const result = processParam(param);
    
    // Step 2: Explanation
    return result;
}

// Example usage
const output = exampleFunction(input);
```

---

## Submission Process

### Step-by-Step

1. **Fork the repository** (if external contributor)
2. **Create a branch** with a descriptive name
   ```bash
   git checkout -b blog/your-topic-name
   ```
3. **Write your blog post** using the template
4. **Add your post** to the appropriate category directory
5. **Update the blogs README** to include your post
6. **Commit your changes**
   ```bash
   git add .
   git commit -m "Add blog post: Your Topic Name"
   ```
7. **Push to your fork** and create a Pull Request
8. **Respond to review feedback** promptly

### Commit Message Format

```
Add blog post: [Title of Blog Post]

- Brief description of the content
- Any additional context
```

---

## Review Criteria

Your contribution will be evaluated based on:

### Content Quality (50%)
- ✅ Technical accuracy
- ✅ Depth and completeness
- ✅ Practical value
- ✅ Original insights or unique perspective

### Writing Quality (30%)
- ✅ Clear and professional writing
- ✅ Proper grammar and spelling
- ✅ Logical flow and organization
- ✅ Appropriate use of formatting

### Code Quality (20%)
- ✅ Working, tested examples
- ✅ Best practices followed
- ✅ Well-commented code
- ✅ Security considerations addressed

---

## Questions or Suggestions?

If you have questions about contributing or suggestions for improving these guidelines, please:

1. Open an issue in the repository
2. Tag it with `question` or `documentation`
3. Provide context and details

---

**Thank you for contributing to the professional development community!**

*Last Updated: 2026-02-10*
