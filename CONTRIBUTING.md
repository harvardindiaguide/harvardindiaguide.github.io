# Contributing to Harvard India Guide

Thank you for your interest in contributing! This guide will help you add or update information.

## 🎯 Quick Start

All content is stored in YAML files in the `_data/` folder. You can edit these files directly on GitHub without any coding knowledge!

## 📂 File Structure

```
_data/
  ├── food.yml          # Restaurants, grocery stores, dining
  ├── community.yml     # Student orgs, religious groups, sports
  ├── places.yml        # Temples, mosques, yoga, wellness
  └── practical.yml     # First week tips, healthcare, transportation
```

## ✏️ How to Edit (Easy Way)

1. **Navigate to the file** you want to edit on GitHub
2. **Click the pencil icon** (✏️) in the top right
3. **Make your changes** following the format below
4. **Scroll down** and describe your changes
5. **Click "Propose changes"**
6. **Submit the pull request**

Your changes will be reviewed and merged!

## 📋 Content Guidelines

### Adding a Restaurant

In `_data/food.yml`, under `restaurants:` section:

```yaml
- name: "Restaurant Name"
  type: "North Indian"  # Options: North Indian, South Indian, Street Food, Fine Dining
  location: "Cambridge, MA"
  distance: "2 miles from Harvard Square"
  description: "Brief, helpful description (one sentence)"
  price: "$$"  # $ (budget), $$ (moderate), $$$ (expensive)
  vegetarian_friendly: true  # or false
  highlights:
    - "Must-try dish 1"
    - "Must-try dish 2"
    - "Must-try dish 3"
```

### Adding a Grocery Store

In `_data/food.yml`, under `grocery_stores:` section:

```yaml
- name: "Store Name"
  location: "City, State"
  distance: "Miles from Harvard"
  description: "What makes this store special"
  offerings:
    - "Type of products 1"
    - "Type of products 2"
    - "Special items available"
```

### Adding a Student Organization

In `_data/community.yml`, under appropriate section:

```yaml
- name: "Organization Name"
  description: "What the organization does (one sentence)"
  contact: "email@example.com"  # Optional
  activities:
    - "Regular activity 1"
    - "Regular activity 2"
    - "Events hosted"
```

### Adding a Place of Worship

In `_data/places.yml`, under `temples:` or `mosques:` section:

```yaml
- name: "Temple/Mosque Name"
  location: "City, State"
  distance: "Miles from Harvard"
  denomination: "Hindu/Muslim/etc"  # For temples
  description: "Brief description"
  transportation: "How to get there"
  timings: "When it's open"
  special_events:  # Optional
    - "Event 1"
    - "Event 2"
```

### Adding Wellness/Yoga Places

In `_data/places.yml`, under `yoga_wellness:` section:

```yaml
- name: "Studio/Center Name"
  location: "Area/City"
  distance: "Distance from campus"
  description: "What they offer"
  price: "Price range or 'Free'"  # Optional
  access: "Access details"  # Optional
  types:
    - "Type of yoga/practice 1"
    - "Type of yoga/practice 2"
```

### Adding Practical Information

In `_data/practical.yml`, add to appropriate category:

```yaml
- category: "Category Name"
  items:
    - task: "What to do"
      details: "How to do it"
      tips:
        - "Helpful tip 1"
        - "Helpful tip 2"
```

## ✅ Best Practices

- **Be accurate**: Only add information you're confident about
- **Be helpful**: Include practical details (distance, cost, how to get there)
- **Be concise**: Keep descriptions brief and useful
- **Be current**: Update outdated information when you notice it
- **Be respectful**: Maintain a welcoming, inclusive tone

## 🚫 What NOT to Include

- Personal opinions or reviews (stick to factual information)
- Outdated information
- Promotional content
- Contact information without permission
- Incorrect or unverified details

## 🧪 Testing Locally (Optional)

If you want to preview changes before submitting:

```bash
# Install Ruby and Bundler first
gem install bundler

# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve

# Visit http://localhost:4000
```

## 📝 YAML Formatting Tips

- **Indentation matters**: Use 2 spaces (not tabs)
- **Lists**: Start with a dash and space `- Item`
- **Nested items**: Indent by 2 more spaces
- **Quotes**: Use quotes for text with special characters
- **Booleans**: Use `true` or `false` (lowercase, no quotes)

Example of proper indentation:

```yaml
restaurants:
  - name: "Example Restaurant"
    highlights:
      - "Dish 1"
      - "Dish 2"
```

## 🤝 Review Process

1. You submit a pull request
2. Maintainers review your changes
3. If approved, changes go live automatically!
4. If changes are needed, maintainers will comment

## 💡 Ideas & Suggestions

Have an idea for a new section or feature? [Open an issue](https://github.com/harvardindia/harvardindiaguide.github.io/issues) to discuss!

## 📞 Questions?

If you're stuck or have questions:
- Open an issue on GitHub
- Reach out to the Harvard Indian student community
- Check existing pull requests for examples

---

Thank you for helping make this resource better for everyone! 🙏
