# 📝 CONTRIBUTING.md

Thank you for your interest in contributing to this AI Portfolio project!

## 🤝 How to Contribute

### Reporting Issues

If you find a bug or have a suggestion:

1. Check if the issue already exists in [Issues](../../issues)
2. If not, create a new issue with:
   - Clear description
   - Steps to reproduce (for bugs)
   - Expected vs actual behavior
   - Screenshots if applicable

### Making Changes

#### 1. Fork the Repository
```bash
git clone https://github.com/YOUR_USERNAME/AI_Portfolio.git
cd AI_Portfolio
```

#### 2. Create a Feature Branch
```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/bug-description
```

#### 3. Make Your Changes
- Follow the existing code style
- Keep changes focused and atomic
- Write clear commit messages
- Test your changes

#### 4. Commit Guidelines

**Format:**
```
<type>(<scope>): <subject>

<body>
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `style`: CSS/styling changes
- `docs`: Documentation updates
- `refactor`: Code refactoring
- `test`: Test additions
- `chore`: Build/config changes

**Example:**
```bash
git commit -m "feat(animations): add scroll-triggered card animations"
```

#### 5. Push and Create Pull Request
```bash
git push origin feature/your-feature-name
```

Then [create a Pull Request](../../compare) with:
- Descriptive title
- Reference to related issues
- Screenshots/demos if visual changes
- Testing checklist completed

## 📐 Code Style Guide

### CSS Guidelines
- Use CSS variables for colors and spacing
- Follow existing naming conventions
- Keep selectors simple and specific
- Add comments for complex sections
- Mobile-first approach for responsive design

### JavaScript Guidelines
- Use descriptive function names
- Keep functions small and focused
- Add comments for complex logic
- Use meaningful variable names
- Check for console errors

### HTML Guidelines
- Use semantic HTML5 elements
- Maintain proper heading hierarchy
- Add alt text to images
- Use descriptive classes/IDs
- Keep indentation consistent

## 🎨 Design Contributions

### Color Palette
```
Dark Background: #0a0e27
Card Background: #0f1629
Primary Purple: #8b5cf6
Accent Cyan: #06b6d4
Text Primary: #e4e9f1
Text Secondary: #a8b2c1
```

### Typography
- Primary: Segoe UI, Tahoma, Geneva
- Monospace: Courier New
- Font sizes follow existing scale

### Animation Standards
- Smooth transitions: 0.3s cubic-bezier(0.4, 0, 0.2, 1)
- Slow animations: 0.5s for complex effects
- Respect `prefers-reduced-motion`

## 🧪 Testing Checklist

Before submitting a PR, ensure:

- [ ] No console errors
- [ ] Works on Chrome, Firefox, Safari, Edge
- [ ] Mobile responsive (test on 480px, 768px, 1024px)
- [ ] Links work correctly
- [ ] Form validation works
- [ ] Animations smooth
- [ ] Images load properly
- [ ] Accessibility standards met

## 📊 Performance Guidelines

- Keep CSS file size under 30KB
- Keep JS file size under 15KB
- Minimize external dependencies
- Use CSS Grid/Flexbox (no float layouts)
- Optimize animations (use GPU-accelerated properties)

## ♿ Accessibility Requirements

- [ ] WCAG 2.1 Level AA compliance
- [ ] Semantic HTML elements
- [ ] ARIA labels where needed
- [ ] Keyboard navigation support
- [ ] Color contrast ratios >= 4.5:1
- [ ] Focus states visible
- [ ] Alt text for images

## 📚 Documentation

When adding features:
1. Update this README if structure changes
2. Add code comments for complex logic
3. Update DEPLOYMENT.md if relevant
4. Include usage examples

## 🔍 Review Process

1. Automated checks run (if set up)
2. Code review by maintainer
3. Feedback and discussion
4. approval
5. Merge to main

## 🎓 Learning Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [JavaScript.info](https://javascript.info/)
- [WebAIM Accessibility](https://webaim.org/)

## 🏆 Recognition

Contributors will be:
- Listed in Contributors section
- Credited in commit messages
- Featured in release notes

## 💬 Questions?

- Open a [Discussion](../../discussions)
- Check existing [Issues](../../issues)
- Create a new issue with `question` label

## 📄 License

By contributing, you agree your changes are under the MIT License.

---

**Thank you for making this project better!** 🚀
