# 🎉 Two-Column Layout Created!

## 📁 New Files Created:

1. **index-two-column.html** - New two-column layout page
2. **styles-two-column.css** - Styling for two-column layout
3. **script-two-column.js** - JavaScript for two-column layout

## 🚀 How to Preview:

### Option 1: Direct Open
1. Open `index-two-column.html` in your browser
2. Compare with your current `index.html`

### Option 2: Side-by-Side
1. Open `index.html` in one browser tab
2. Open `index-two-column.html` in another tab
3. Compare the layouts

---

## 🎨 Two-Column Layout Features:

### LEFT SIDEBAR (30% width):
✅ Profile Photo with vertical social icons overlay
✅ Academic Identity badges (ORCID, Google Scholar)
✅ Biography section
✅ Expertise Information (Research Group, Areas of Interest)

### RIGHT MAIN CONTENT (70% width):
✅ Name Header with QR code placeholder
✅ Contact information
✅ Biosketch download button
✅ **Colored Statistics Cards** (horizontal row):
   - 🟢 Green - Publications
   - 🟡 Yellow - Best Paper Award
   - 🔵 Blue - PhD CGPA
   - 🔴 Red - Certifications
✅ Scholar ID box with room number
✅ Accordion sections (collapsible)

---

## 🎯 Layout Comparison:

### Current Layout (index.html):
- Single column
- Hero section with video
- Profile photo in center
- Stats cards in grid
- All accordions below

### New Layout (index-two-column.html):
- Two columns (sidebar + main)
- No hero video (cleaner, faster)
- Profile photo in left sidebar
- Stats cards in horizontal row
- Professional academic look

---

## 📱 Responsive Design:

### Desktop (1024px+):
- Two columns side by side
- Full layout visible

### Tablet (768px - 1024px):
- Stacks to single column
- Sidebar appears first
- Main content below

### Mobile (< 768px):
- Single column
- Hamburger menu
- Stats stack vertically

---

## 🔄 To Switch to Two-Column Layout:

### Option A: Replace Current Page
```bash
# Backup current page (already done)
# index_backup.html exists

# Replace with new layout
mv index.html index-old.html
mv index-two-column.html index.html
mv styles-two-column.css styles.css
mv script-two-column.js script.js
```

### Option B: Keep Both
- Keep `index.html` as is
- Use `index-two-column.html` for new layout
- Choose which one to deploy

---

## ✏️ Customization Guide:

### 1. Update Profile Photo:
```html
<!-- Line 32 in index-two-column.html -->
<img src="images/KANNURU SRINADH.png" alt="Kannuru Srinadh">
```

### 2. Update Social Links:
```html
<!-- Lines 35-50 in index-two-column.html -->
<a href="YOUR_GOOGLE_SCHOLAR_URL" target="_blank">
<a href="YOUR_LINKEDIN_URL" target="_blank">
```

### 3. Update Biography:
```html
<!-- Lines 75-77 in index-two-column.html -->
<p>Your biography text here...</p>
```

### 4. Update Stats Numbers:
```html
<!-- Lines 135-150 in index-two-column.html -->
<h3 class="counter" data-target="3">0</h3>  <!-- Change 3 to your number -->
```

### 5. Add QR Code:
Replace the QR placeholder:
```html
<!-- Line 127 in index-two-column.html -->
<div class="qr-placeholder">
    <img src="images/your-qr-code.png" alt="QR Code">
</div>
```

### 6. Update Room Number:
```html
<!-- Line 157 in index-two-column.html -->
<p><i class="fas fa-door-open"></i> Room Number: EC-XXX</p>
```

---

## 🎨 Color Customization:

### Change Colors in styles-two-column.css:

```css
:root {
    --navy-blue: #003366;    /* Main blue */
    --gold: #FFB81C;         /* Gold accent */
    --green: #28a745;        /* Publications */
    --yellow: #ffc107;       /* Awards */
    --blue: #17a2b8;         /* CGPA */
    --red: #dc3545;          /* Certifications */
}
```

---

## 📊 What's Different:

### Removed:
- ❌ Hero video section (for faster loading)
- ❌ Large hero banner
- ❌ Download CV button in hero

### Added:
- ✅ Two-column professional layout
- ✅ Sidebar with photo and bio
- ✅ Horizontal stats row with colors
- ✅ Scholar ID box
- ✅ QR code placeholder
- ✅ Biosketch button in header

### Kept:
- ✅ Navigation menu
- ✅ All accordion sections
- ✅ Contact form
- ✅ Animated counters
- ✅ Responsive design

---

## 🚀 Next Steps:

1. **Preview** the new layout in browser
2. **Compare** with current layout
3. **Customize** content (bio, stats, etc.)
4. **Add** your QR code image
5. **Test** on mobile devices
6. **Choose** which layout to use
7. **Deploy** your preferred version

---

## 💡 Tips:

### For Best Results:
- Use a professional profile photo (800x1000px)
- Generate a QR code linking to your profile
- Keep biography concise (2-3 paragraphs)
- Update all social media links
- Test on different screen sizes

### Performance:
- Two-column layout loads faster (no video)
- Better for printing/PDF export
- More professional for academic use

---

## 🆘 Need Help?

### Common Issues:

**Q: Stats not animating?**
A: Check browser console for errors, ensure script-two-column.js is loaded

**Q: Layout broken on mobile?**
A: Clear browser cache and test in incognito mode

**Q: Social icons not showing?**
A: Ensure Font Awesome CDN is loading (check internet connection)

**Q: Want to add more sections?**
A: Copy an existing accordion-item and modify the content

---

## 📝 File Structure:

```
WEBPAGE/
├── index.html                  ← Current single-column
├── index-two-column.html       ← NEW two-column layout
├── index_backup.html           ← Backup of original
├── styles.css                  ← Current styles
├── styles-two-column.css       ← NEW two-column styles
├── script.js                   ← Current JavaScript
├── script-two-column.js        ← NEW two-column JavaScript
├── images/
│   ├── KANNURU SRINADH.png
│   └── hero.mp4
└── documents/
    └── Kannuru_Srinadh_CV.pdf
```

---

## ✅ Checklist Before Going Live:

- [ ] Preview in browser
- [ ] Test all links
- [ ] Update biography
- [ ] Add QR code
- [ ] Update room number
- [ ] Test on mobile
- [ ] Check all accordions work
- [ ] Test contact form
- [ ] Update social media links
- [ ] Add your CV PDF

---

**Enjoy your new professional two-column layout!** 🎉

If you like it, you can replace your current index.html with this new version!
