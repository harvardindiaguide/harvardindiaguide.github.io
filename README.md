# Harvard India Guide

A community-driven, open-source guide for Indian students at Harvard University.

## 🌟 About

This website helps Indian students navigate life at Harvard by providing practical information about:
- 🍛 Indian restaurants and grocery stores
- 👥 Student organizations and communities  
- 🕉️ Places of worship and wellness centers
- 📋 Practical tips for settling in

## 🚀 Live Site

Visit: [harvardindiaguide.github.io](https://harvardindiaguide.github.io)

## 🤝 How to Contribute

This is a community project - **everyone can help improve it!**

All the content is stored in easy-to-edit YAML files in the `_data/` folder:

- `_data/food.yml` - Restaurants, grocery stores, dining tips
- `_data/community.yml` - Student organizations, religious groups, sports
- `_data/places.yml` - Temples, mosques, yoga studios, wellness centers
- `_data/practical.yml` - First week tips, transportation, healthcare, homesickness

### Easy Way (GitHub Web Interface)

1. Navigate to the file you want to edit (e.g., `_data/food.yml`)
2. Click the pencil icon (✏️) to edit
3. Make your changes following the existing format
4. Scroll down and click "Propose changes"
5. Submit the pull request

**No coding knowledge needed!** Just edit the YAML files like a simple list.

### Advanced Way (Git)

```bash
# Fork and clone the repository
git clone https://github.com/harvardindiaguide/harvardindiaguide.github.io.git
cd harvardindiaguide.github.io

# Make your changes to YAML files in _data/

# Test locally (optional)
bundle install
bundle exec jekyll serve

# Commit and push
git add .
git commit -m "Add new restaurant/update info"
git push origin main

# Create a pull request on GitHub
```

## 🛠️ Tech Stack

- **Jekyll** - Static site generator (GitHub Pages native)
- **YAML** - Data storage for easy editing
- **Liquid** - Template engine
- **HTML/CSS** - Minimal, soothing design with earth tones

## 📝 Adding New Content

### Adding a Restaurant

Edit `_data/food.yml` and add:

```yaml
- name: "Restaurant Name"
  type: "North Indian"  # or South Indian, Street Food, etc.
  location: "Cambridge, MA"
  distance: "2 miles from Harvard Square"
  description: "Brief description of the place"
  price: "$$"  # $, $$, or $$$
  vegetarian_friendly: true
  highlights:
    - "Signature Dish 1"
    - "Signature Dish 2"
```

### Adding a Community Group

Edit `_data/community.yml` and add:

```yaml
- name: "Organization Name"
  description: "What this group does"
  contact: "email@example.com"
  activities:
    - "Activity 1"
    - "Activity 2"
```

### Adding a Place of Worship

Edit `_data/places.yml` under the appropriate section (temples/mosques):

```yaml
- name: "Temple/Mosque Name"
  location: "City, State"
  distance: "X miles from Harvard"
  description: "Brief description"
  timings: "Hours of operation"
  transportation: "How to get there"
```

## 🎨 Design Philosophy

- **Minimal & Soothing** - Clean layout with earth tones (terracotta, sage, cream)
- **Mobile-First** - Responsive design that works on all devices
- **Accessible** - Easy navigation with smooth scrolling
- **Community-Driven** - Anyone can contribute via YAML edits

## 📄 License

MIT License - Feel free to fork and adapt for other universities!

## 💬 Contact

Have questions or suggestions? [Open an issue](https://github.com/harvardindia/harvardindiaguide.github.io/issues) or reach out to the Harvard Indian community.

---

**Made with ❤️ by the Harvard Indian community**
