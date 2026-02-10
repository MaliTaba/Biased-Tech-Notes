# Quick Start Guide for Contributors

This guide will help you quickly get started with writing blog posts for Biased-Tech-Notes.

## 5-Minute Setup

### Step 1: Copy the Template

Navigate to `blogs/.templates/blog-template.md` and copy the content.

### Step 2: Choose a Category

Create or use an existing category directory under `blogs/`:
- `getting-started/` - Beginner-friendly tutorials
- `best-practices/` - Code quality and patterns
- `architecture/` - System design and architecture
- `devops/` - Infrastructure and deployment
- `performance/` - Optimization techniques
- Or create a new category that fits your topic

### Step 3: Create Your File

Name your file using kebab-case (lowercase with hyphens):
```
blogs/[category]/your-descriptive-title.md
```

Example:
```
blogs/best-practices/writing-testable-code.md
```

### Step 4: Fill In the Template

Replace the placeholder content with your own:

1. **Title and Metadata**
   - Add your name as the author
   - Set the current date
   - Add 3-5 relevant tags
   - Estimate reading time (250 words per minute average)

2. **Abstract**
   - Write 2-3 sentences summarizing your post
   - Make it compelling - this is what readers see first

3. **Content Sections**
   - Introduction: Set the context and hook readers
   - Background: Provide necessary prerequisites
   - Main Content: Break into logical subsections
   - Examples: Include working code with explanations
   - Best Practices: Share your expert recommendations
   - Common Pitfalls: Help readers avoid mistakes
   - Conclusion: Summarize key takeaways

4. **References**
   - Link to authoritative sources
   - Credit any inspiration or borrowed concepts

5. **About the Author**
   - Write a brief bio (2-3 sentences)
   - Add your professional links

## Writing Tips

### Do's ✅
- ✅ Test all code examples before including them
- ✅ Use clear, descriptive variable names in examples
- ✅ Include comments in complex code sections
- ✅ Provide context for why something matters
- ✅ Use real-world scenarios and practical examples
- ✅ Proofread for grammar and spelling
- ✅ Check all links work correctly

### Don'ts ❌
- ❌ Don't copy code from other sources without attribution
- ❌ Don't use overly complex jargon without explanation
- ❌ Don't include untested or broken code
- ❌ Don't make assumptions about reader knowledge without stating prerequisites
- ❌ Don't forget to update the date when making revisions

## Code Example Format

Always include:
1. Context about what the code does
2. The code itself with syntax highlighting
3. Explanation of key concepts
4. When applicable, show both "bad" and "good" examples

Example format:
```markdown
### Handling Async Operations

**Bad Approach:**
```javascript
getData(function(err, data) {
    if (err) {
        console.log(err);
    }
    processData(data, function(err, result) {
        // Callback hell continues...
    });
});
```

**Good Approach:**
```javascript
try {
    const data = await getData();
    const result = await processData(data);
    return result;
} catch (error) {
    handleError(error);
}
```

**Why it's better:**
- Cleaner, more readable code
- Easier error handling
- Avoids callback hell
```

## Submission Checklist

Before submitting your PR:

- [ ] Used the blog template structure
- [ ] Added appropriate metadata (author, date, tags)
- [ ] Tested all code examples
- [ ] Checked spelling and grammar
- [ ] Added author bio and links
- [ ] Included references and citations
- [ ] Named file using kebab-case
- [ ] Placed in appropriate category directory
- [ ] Read through the entire post one final time

## Getting Help

- **Questions?** Open an issue with the `question` label
- **Unsure about categorization?** Ask in the PR description
- **Need a review?** Tag maintainers in your PR

## Example Posts

Look at existing posts for inspiration:
- [Clean Code Principles](../blogs/getting-started/clean-code-principles.md)

## Additional Resources

- Full [Contributing Guide](../CONTRIBUTING.md)
- [Blog Template](../blogs/.templates/blog-template.md)
- [Repository README](../README.md)

---

**Ready to share your knowledge? Start writing! 🚀**
