# 15min - Frontend Style Guide

## Technologies Used
- Next.js 13
- TypeScript
- React
- Tailwind CSS

## File System
```
src/
├── modules/
│   ├── auth/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── types/
│   │   ├── AuthPage/
│   │   └── ...
│   ├── home/
│   │   ├── components/
│   │   ├── hooks/
│   │   ├── types/
│   │   ├── HomePage/
│   │   └── ...
│   └── ...
├── styles/
├── utils/
├── types/
│   ├── index.d.ts
│   ├── global.d.ts
│   └── ...
└── ...
```

## Naming Conventions
- Use PascalCase for components, such as `LoginPage.tsx`
- Use camelCase for variables and functions
- Use kebab-case for CSS class names

## Tailwind CSS
- Prioritize editing the `tailwind.config.js` file over using arbitrary values in components
- Reuse Tailwind classes whenever possible and group them together to avoid arbitrary values
- Use Tailwind's utility classes instead of writing custom CSS whenever possible

## Types and Interfaces
- Use TypeScript to add static type checking to the project
- Use interfaces to define the shape of objects
- Use types to define complex types, such as unions or intersections
- Use interfaces to define props for React components
- Use interfaces to define the return type for custom hooks
- Place global types in the `types/` directory at the root level
- Place module-specific types in a `types/` directory within the module folder

## SOLID Principles
- Follow the SOLID principles when creating components and services
  - Single Responsibility Principle (SRP)
  - Open/Closed Principle (OCP)
  - Liskov Substitution Principle (LSP)
  - Interface Segregation Principle (ISP)
  - Dependency Inversion Principle (DIP)

### SRP - Single Responsibility Principle
A component should have only one reason to change. It should do one thing and do it well.

### OCP - Open/Closed Principle
A component should be open for extension but closed for modification. It should be possible to add new functionality without changing existing code.

### LSP - Liskov Substitution Principle
A component should be substitutable by its subtypes without affecting the correctness of the program.

### ISP - Interface Segregation Principle
A component should not be forced to depend on interfaces it does not use.

### DIP - Dependency Inversion Principle
A component should depend on abstractions rather than concretions.

## Custom Hooks
- Place reusable logic in custom hooks
- Use descriptive names for custom hooks

# Guidelines for Testing in the Frontend

1. Write unit tests for components, custom hooks, and utility functions.
2. Use a testing framework like Jest or React Testing Library.
3. Make sure tests are easy to read and understand by using descriptive names and comments.
4. Test both positive and negative scenarios.
5. Use mocks or stubs for external dependencies like API calls.
6. Use snapshot testing for visual regressions.
7. Test accessibility using tools like Axe or Pa11y.
8. Use code coverage tools to ensure that all code paths are tested.
9. Use Continuous Integration (CI) tools to automatically run tests on every commit.
10. Write end-to-end tests for critical user flows using tools like Cypress or Selenium.

Remember that testing is an important part of the development process, and it can save time and effort in the long run by catching bugs and regressions early on.

## Pull Request Format
When creating a pull request, please follow this format:

### Description
Describe the changes made and the purpose of the pull request.

### Issues Closed
List any GitHub issues that are closed by this pull request.

### Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Refactoring
- [ ] Documentation update

### Checklist
- [ ] The code builds without errors
- [ ] The code follows the SOLID principles
- [ ] The code has been tested
- [ ] The code follows the style guidelines
- [ ] The pull request has a descriptive title
- [ ] The pull request is linked to any relevant GitHub issues

## Conclusion
By following these guidelines, we can maintain a consistent and maintainable codebase.
