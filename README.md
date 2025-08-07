# WrangleAI Investor Deck - Project Documentation

## 🎯 **PROJECT OVERVIEW**
This folder contains all assets, files, and documentation for the WrangleAI investor presentation. The presentation is a modern, interactive HTML document hosted on GitHub Pages and designed for investor pitches and fundraising meetings.

**Live Presentation URL**: https://wrangleai.github.io/investor-deck

---

## 📁 **FILE STRUCTURE**

### **Core Presentation Files**
- **`index.html`** - Main presentation file (master copy for editing and deployment)

### **Brand Assets**
- **`brand elements/`** - Directory containing all WrangleAI brand assets:
  - `BoyandBot.png` - Character illustrations
  - `WrAI-*.png` - Various character states (advisor, analyzer, explainer, problem solver, working together)
  - `WrangleAICoreLogo.png` - Core logo
  - `whitelogo.png` - White version logo

### **Supporting Images**
- **`1.png`** - Kevin's profile image (CEO/Founder)
- **`image.png`** - Primary supporting graphics
- **`image copy.png`, `image copy 2.png`, `image copy 3.png`** - Additional visual assets

### **Branding Guidelines**
- **`WrangleAI BRAND GUIDELINES.png/.svg`** - Official brand guidelines document
- **`WrangleAIlogo50x150.svg`** - Vector logo file

### **Reference Materials**
- **`Wrangle AI Pitch Deck v4.pdf`** - Original PDF pitch deck (reference only)
- **`DEPLOYMENT_GUIDE.md`** - GitHub Pages deployment instructions

---

## 🛠️ **EDITING WORKFLOW**

### **CRITICAL RULES FOR AI MODELS:**

1. **EDIT THE MASTER FILE**: Make changes to `index.html` (this is the master and deployment file)
2. **PRESERVE STRUCTURE**: The HTML uses a custom slide framework - maintain the section structure
3. **IMAGE PATHS**: All images use relative paths - maintain the folder structure
4. **TEST LOCALLY**: Open `index.html` in browser to test changes before deployment

### **Safe Editing Process:**
```bash
# 1. Edit the presentation file
# Edit: index.html

# 2. Test locally
# Open index.html in browser

# 3. Deploy to GitHub (if authorized)
git add .
git commit -m "Update presentation: [describe changes]"
git push origin main
```

---

## 🎨 **DESIGN PRINCIPLES**

### **Visual Style**
- **Color Scheme**: Dark theme with WrangleAI brand colors
- **Typography**: Modern, clean fonts optimized for readability
- **Layout**: Slide-based presentation using reveal.js framework
- **Animations**: Smooth transitions and subtle animations

### **Content Structure**
1. **Opening Hook** - Problem statement and market opportunity
2. **Solution Overview** - WrangleAI's core value proposition
3. **Product Demo** - Key features and capabilities
4. **Market Analysis** - TAM, SAM, SOM breakdown
5. **Business Model** - Revenue streams and pricing
6. **Traction/Metrics** - Growth indicators and validation
7. **Team Introduction** - Key personnel and expertise
8. **Funding Ask** - Investment requirements and use of funds
9. **Vision/Future** - Long-term roadmap and opportunities

---

## 🚀 **DEPLOYMENT**

### **GitHub Pages Setup**
- **Repository**: https://github.com/WrangleAI/investor-deck
- **Branch**: main
- **Source**: / (root)
- **Domain**: wrangleai.github.io/investor-deck

### **Automatic Deployment**
Changes pushed to the main branch automatically deploy to GitHub Pages within 2-3 minutes.

---

## 🔄 **ITERATION GUIDELINES**

### **For Future AI Models Working on This Project:**

#### **DO:**
- ✅ Always read this README first for context
- ✅ Edit `index.html` as the master file
- ✅ Maintain the custom slide structure (`<section>` tags)
- ✅ Keep image references relative and intact
- ✅ Test changes by opening `index.html` in browser
- ✅ Preserve existing animations and transitions
- ✅ Follow the established design language

#### **DON'T:**
- ❌ Break the custom slide framework structure
- ❌ Change image file paths without updating HTML
- ❌ Remove or modify brand assets without explicit approval
- ❌ Change the core presentation flow without understanding the investor journey

### **Common Iteration Tasks:**
1. **Content Updates** - Metrics, financials, team info, product features
2. **Design Refinements** - Typography, spacing, color adjustments
3. **New Slides** - Following the established template pattern
4. **Image Updates** - Replacing visuals while maintaining paths
5. **Animation Tweaks** - Enhancing transitions and reveals

---

## 📋 **TECHNICAL SPECS**

### **Framework**: Reveal.js
### **Styling**: Custom CSS with WrangleAI branding
### **Images**: PNG/SVG format, optimized for web
### **Responsive**: Mobile and desktop compatible
### **Performance**: Optimized for fast loading

---

## 💡 **CONTEXT FOR AI MODELS**

**What We're Building**: A compelling, modern investor presentation that showcases WrangleAI's value proposition, market opportunity, and growth potential.

**Target Audience**: Potential investors, VCs, angel investors, and strategic partners.

**Key Success Metrics**: 
- Clear value proposition communication
- Professional visual presentation
- Smooth user experience
- Fast loading and accessibility
- Easy to update and maintain

**Previous Iterations**: This presentation has been iteratively improved based on investor feedback and changing business metrics. Always preserve the core narrative flow while updating specific data points.

---

## 🎯 **BRAND CONSISTENCY**

Always reference the `WrangleAI BRAND GUIDELINES.png/.svg` files for:
- Official color palette
- Typography standards  
- Logo usage rules
- Visual style guidelines
- Tone and messaging

---

**Last Updated**: July 2024  
**Maintained By**: WrangleAI Team  
**AI-Friendly**: This documentation is designed to provide context for AI models working on future iterations. 