# Instructions for Claude

This document contains instructions for maintaining this repository when working with the user.

---

## 📋 Repository Maintenance

### README Index Updates

**IMPORTANT:** Whenever a new document is created or an existing document's scope significantly changes, update the `README.md` file to reflect the current state of the repository.

**What to update:**
1. Add new documents to the "Document Index" section
2. Include a brief description of the document's content
3. Organize by topic category (create new categories if needed)
4. Update the "Last updated" date at the bottom
5. Update topic lists if new areas are covered

**Example workflow:**
```
1. User: "Create a document about altitude training"
2. Create altitude-training-protocol.md
3. Update README.md to include the new document
4. Commit both files together
```

---

## 📝 Document Standards

When creating new documents in this repository:

### Structure
- Include a title and creation date
- Provide research summary and key findings
- Include practical protocols and recommendations
- Add safety considerations where relevant
- Provide complete reference list with working links
- End with a "Bottom Line" summary section

### Research Quality
- Reference peer-reviewed studies when possible
- Include links to primary sources (prefer PMC/PubMed)
- Cite specific findings with context
- Distinguish between optimal and practical protocols
- Note limitations or gaps in research

### Writing Style
- Clear, concise, actionable
- Evidence-based but accessible
- Balance scientific rigor with practical application
- Emphasize consistency over perfection
- Include concrete numbers and timelines

---

## 🔄 Commit Practices

### Commit Messages
- Use descriptive commit messages
- Include "Add", "Update", or "Fix" as appropriate
- Mention key additions or changes
- Include Claude Code attribution footer

### When to Update README
Commit the README update in the **same commit** as the new document:
```bash
git add new-document.md README.md
git commit -m "Add new document and update README index"
```

---

## 📚 Repository Purpose

This repository serves as the user's personal knowledge base for:
- Evidence-based training protocols
- Performance optimization strategies
- Research summaries and practical applications
- Testing methodologies and interpretations

**Guiding principles:**
1. Research-backed information
2. Practical applicability
3. Clear documentation
4. Consistent organization
5. Easy navigation

---

*Last updated: December 10, 2025*
