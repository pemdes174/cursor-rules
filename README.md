# My Cursor Rules for Vibe Coding in 2025 🚀

Hey, I'm Ryan Wang, ex-faang engineer currenlty building [Daxtr.ai](https://daxtr.ai). These are the rules I use with [Cursor](https://cursor.sh/) to achieve that sweet spot of rapid and high-quality development.

With this setup + a solid project structure, I can usually one-shot feature requests with minimal bugs and rework. It's my personal recipe for productive, enjoyable coding sessions that actually ship to production.

## 📁 Repository Structure

```
.cursor/
└── rules/
    ├── nextjs-development.mdc    # Comprehensive Next.js development guidelines
    └── unit-testing.mdc          # Unit testing best practices and patterns
```

## 🎯 What's in My Toolkit

### Next.js Development Rules (`nextjs-development.mdc`)

My go-to rules for building modern, scalable Next.js apps - the same patterns I used to build testable production ready code for my customers. This covers everything I need to:

- **Tech Stack Guidelines**: Next.js 15+, React 19, TypeScript, Vitest, Tailwind CSS, shadcn/ui
- **Project Structure**: Organized directory layout with clear separation of concerns
- **App Router Patterns**: Server vs Client Components, Server Boundaries, Performance optimization
- **API Architecture**: tRPC integration, internal vs external APIs, error handling
- **Database & Data Layer**: ORM best practices, data access patterns
- **Authentication & Authorization**: Security best practices
- **Testing Strategy**: Unit, integration, and component testing approaches
- **Code Quality**: TypeScript strict mode, functional programming patterns, naming conventions
- **Development Workflow**: Step-by-step process for implementing features
- **Common Patterns**: Templates for tRPC procedures, routers, error handling, and more

### Unit Testing Rules (`unit-testing.mdc`)

My testing philosophy - keep it simple, focused, and actually useful. Learned this the hard way at Amazon and Atlassian where I had to maintain massive codebases:

- **Core Principles**: Isolation, determinism, structure, and quality gates
- **Test Structure**: Arrange-Act-Assert pattern with descriptive naming
- **Mocking Guidelines**: When and how to mock external dependencies
- **Common Patterns**: Examples for testing pure functions, async functions, and error cases
- **File Organization**: Clear test directory structure

## 🚀 How To Use This

1. **Clone this repo** to your local machine
2. **Copy the `.cursor/rules/` directory** to your project's root
3. **Restart Cursor** to load the new rules
4. **Start vibing** - Cursor now follows my preferred patterns automatically

### Quick Setup

```bash
git clone [https://github.com/ryanrawlingswang/cursor-rules.git](https://github.com/ryanrawlingswang/cursor-rules.git)
cp -r cursor-rules/.cursor/rules/ ~/your-project/.cursor/
```

### Why This Works for Me

These rules are battle-tested from building enterprise SaaS platforms, working at scale (Amazon, Atlassian), and shipping production code that actually works. They strike the right balance between:
- **Speed**: Get features done quickly without cutting corners (crucial when you're the founder/CEO doing the coding)
- **Quality**: Production-ready code that doesn't need major refactoring (learned this from maintaining massive codebases)
- **Maintainability**: Clear patterns that make future changes predictable (essential for long-term projects)
- **Developer Experience**: Fun to work with, not a chore (because life's too short for miserable coding sessions)

## 🔧 Make It Yours

Feel free to adapt these rules to your own style:

- **Add your own rules** by creating additional `.mdc` files in the `.cursor/rules/` directory
- **Tweak existing rules** to match your preferences and coding style
- **Use glob patterns** to apply rules only to specific file types
- **Set `alwaysApply: true`** for rules that should apply to all files

## 📋 Rule File Format

Each rule file uses the following format:

```markdown
---
alwaysApply: true/false
description: Brief description of the rules
globs: "**/*.ts" (optional - for file-specific rules)
---

# Rule Title

## Section 1
Content...

## Section 2
Content...
```

## 🎨 What Makes This Special

- **One-Shot Features**: These patterns let me implement most features correctly on the first try (essential when you're building a company and every hour counts)
- **TypeScript-First**: Strict typing catches issues early, so I spend less time debugging (learned this from Amazon's massive codebases)
- **Testing That Actually Helps**: Focused unit tests that prevent regressions without being a burden (not the testing-for-testing's-sake I've seen at big companies)
- **Performance Built-In**: Next.js App Router patterns that scale without optimization headaches (built this way from day one)
- **Security Without Friction**: Authentication and authorization patterns that work out of the box (HIPAA compliance taught me this)
- **Accessibility by Default**: Built-in a11y guidelines so I don't have to think about it later (because inclusive design matters)

## 🤝 Sharing the Vibe

This is my personal setup, but I'm happy to share! I've always believed in the power of open source and community. Feel free to:

1. Fork this repository and make it your own
2. Create your own rules based on these patterns
3. Share back any improvements you discover

*P.S. If you're building something cool with these rules, I'd love to hear about it! I'm always down to chat about tech, startups, or whatever. And if you need help building something bigger, check out [Stratus Softworks](https://stratussoftworks.dev/) - we're always looking for interesting projects to work on.*

## 📚 Related Resources

- [Cursor Documentation](https://docs.cursor.sh/)
- [Next.js Documentation](https://nextjs.org/docs)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [Vitest Documentation](https://vitest.dev/)

## 📄 License

This is my personal setup - feel free to use and modify these rules for your own projects.

---

**Happy vibe coding! 🚀**
