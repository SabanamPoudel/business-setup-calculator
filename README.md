# Business Cost Calculator - WordPress Elementor Setup

## Files in this Directory

### 1. `index.html` (Original - 2669 lines)
- **Purpose**: Standalone HTML file for testing
- **Usage**: Open directly in a web browser to test the calculator
- **Structure**: Complete HTML document with `<!DOCTYPE>`, `<html>`, `<head>`, `<body>` tags
- **Best for**: Local testing and development

### 2. `elementor-ready.html` (WordPress Version - 2676 lines)  ✅
- **Purpose**: Ready to paste into WordPress Elementor HTML widget
- **Usage**: Copy entire file content and paste into Elementor
- **Structure**: No document tags - starts with `<style>`, ends with `</script>`
- **Best for**: WordPress Elementor HTML widget

---

## How to Use in WordPress Elementor

### Step-by-Step Instructions:

1. **Login to WordPress Admin**
   - Go to your WordPress dashboard

2. **Edit Page with Elementor**
   - Navigate to the page where you want the calculator
   - Click "Edit with Elementor"

3. **Add HTML Widget**
   - In the Elementor left sidebar, search for "HTML"
   - Drag and drop the **HTML widget** to your desired location

4. **Paste the Code**
   - Click on the HTML widget you just added
   - Open the file `elementor-ready.html` in a text editor
   - Select ALL content (Cmd+A on Mac, Ctrl+A on Windows)
   - Copy it (Cmd+C or Ctrl+C)
   - Paste into the Elementor HTML widget's code editor

5. **Save and Preview**
   - Click "Update" in Elementor
   - Preview your page to see the calculator in action

---

## Features Included

✅ **7-Step Calculator**
- Step 1: Basic contact details  
- Step 2: Business activity selection
- Step 3: Company name entry
- Step 4: License customization (with/without bank account)
- Step 5: Visa count selection
- Step 6: Additional services
- Step 7: Summary with cost breakdown

✅ **Modern Design**
- Background color: `#e9effb` (light blue)
- Primary color: `#002a6f` (navy blue)
- Accent color: `#c40f0e` (red)
- Compact panels with modern shadows and spacing
- Fully responsive (mobile, tablet, desktop)

✅ **Email Integration**
- Powered by EmailJS (client-side email service)
- Sends submissions to: **info@bizemirate.com**
- Service ID: `service_8ivl27h`
- Template ID: `template_k8f6s3f`
- Public Key: `2Ar6TSoG43Fr0cle3`

✅ **Form Validation**
- Required field checks
- Email format validation
- Phone number validation
- Consent checkbox requirement

---

## Email Configuration Details

The calculator uses **EmailJS** to send form submissions. Make sure:

1. Your EmailJS account is active
2. The service (`service_8ivl27h`) is configured
3. The template (`template_k8f6s3f`) is set up to receive:
   - Customer name, email, phone
   - Company name
   - Selected business activities
   - License options
   - Visa count
   - Additional services
   - Total cost calculation

4. The template should send notifications to: **info@bizemirate.com**

---

## Important Notes

⚠️ **For WordPress Elementor:**
- Always use `elementor-ready.html` (NOT `index.html`)
- `elementor-ready.html` has no `<!DOCTYPE>`, `<html>`, `<head>`, or `<body>` tags
- These document tags would conflict with WordPress's own HTML structure

💡 **Testing:**
- Test the calculator using `index.html` in a browser first
- Once confirmed working, deploy `elementor-ready.html` to WordPress

🔧 **Customization:**
- All styling is self-contained in the `<style>` tag
- Colors can be modified by searching and replacing hex codes
- EmailJS settings are in the initialization script

📱 **Mobile Responsive:**
- Works on all screen sizes
- Automatically adjusts layout for tablets and phones
- Country dropdown fixed at 200px width for better mobile UX

---

## Troubleshooting

### Calculator doesn't appear
- Make sure you copied the ENTIRE content from `elementor-ready.html`
- Check that Elementor HTML widget is on the page
- Clear browser cache and reload

### Emails not sending
- Verify EmailJS account is active
- Check service ID, template ID, and public key are correct
- Open browser console (F12) to see error messages
- Confirm template is configured to send to info@bizemirate.com

### Styles look broken
- Don't use `index.html` in Elementor (use `elementor-ready.html`)
- Check for CSS conflicts with your WordPress theme
- All calculator styles are prefixed to avoid conflicts

### Form validation not working
- JavaScript must be enabled in browser
- Check browser console for errors
- Ensure EmailJS CDN loaded successfully

---

## Technical Specifications

- **Total Lines (Elementor version):** 2676
- **CSS Lines:** ~1200
- **JavaScript Lines:** ~400
- **HTML Content:** All 7 steps fully coded
- **External Dependencies:** EmailJS CDN v4 only
- **Browser Support:** Chrome, Firefox, Safari, Edge (modern versions)

---

## Support

For any issues:
1. Check this README for solutions
2. Test with `index.html` in a browser first
3. Verify EmailJS dashboard for delivery status
4. Check WordPress/Elementor console for JavaScript errors

---

**Created for:** Biz Emirates Business Setup Cost Calculator  
**Target Email:** info@bizemirate.com  
**Last Updated:** 2024  
