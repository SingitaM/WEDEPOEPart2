Kei Mouth Hardware Website
Project Overview
This project is the foundation of a website for Kei Mouth Hardware, a primary hardware retail store based in Kei Mouth, Eastern Cape.
The goal is to create a semantic, accessible, and well-structured HTML5 codebase that is styled and enhanced with additional functionality.

Website Pages
index.html – Home page with featured products and specials
about.html – Store information, mission, and values
products.html – Product categories and listings
specials.html – Current promotions and discount offers
contact.html – Contact details and inquiry form
Research Foundation
Semantic HTML
The website uses semantic HTML5 elements to improve structure, SEO, and accessibility:

<header> → site banner and navigation
<nav> → primary menu with active state tracking
<main> → page-specific content
<section> → grouped content with headings
<article> → self-contained product listings
<footer> → copyright + secondary navigation
<form> → structured user interactions
This ensures better SEO, accessibility for screen readers, and maintainability.

Accessibility Implementation (WCAG 2.1)
Navigation
Semantic navigation with <ul> and <li>
Keyboard-friendly menu with focus states
ARIA labels for screen readers
Skip links for bypassing repetitive navigation
Forms
Accessible form structure with required fields and ARIA support:

<div class="form-group">
  <label for="firstName">First Name *</label>
  <input type="text" id="firstName" name="firstName" 
         placeholder="Enter your first name" 
         aria-required="true" required>
  <span class="sr-only">This field is required</span>
</div>

<div class="form-group">
  <label for="enquiryType">Enquiry Type *</label>
  <select id="enquiryType" name="enquiryType" 
          aria-required="true" required>
      <option value="" disabled selected>Select an option</option>
      <option value="account">Account Enquiry</option>
      <option value="product">Product Availability</option>
  </select>
</div>
Images
Descriptive alt attributes for meaningful images
Empty alt attributes for decorative visuals
Detailed descriptions for product images
Color & Contrast
Contrast ratio ≥ 4.5:1
Color not the only way of conveying information
Focus indicators for all interactive elements
Technical Features
Responsive Design
Mobile-first with progressive enhancement
Flexible layouts using CSS Grid & Flexbox
Responsive images with proper sizing
Touch-friendly controls
Performance Optimization
Optimized WebP images
Minimal CSS & JavaScript footprint
Efficient asset loading strategy
Semantic HTML for faster parsing
Browser Compatibility
Compatible with Chrome, Firefox, Safari, Edge
Progressive enhancement for older browsers
Modern CSS with fallbacks
File Structure
📦ST10465147-Singita Mushwana-WEDE5020-POE
 ┣ 📂.git
 ┃ ┣ 📂hooks
 ┃ ┃ ┣ 📜applypatch-msg.sample
 ┃ ┃ ┣ 📜commit-msg.sample
 ┃ ┃ ┣ 📜fsmonitor-watchman.sample
 ┃ ┃ ┣ 📜post-update.sample
 ┃ ┃ ┣ 📜pre-applypatch.sample
 ┃ ┃ ┣ 📜pre-commit.sample
 ┃ ┃ ┣ 📜pre-merge-commit.sample
 ┃ ┃ ┣ 📜pre-push.sample
 ┃ ┃ ┣ 📜pre-rebase.sample
 ┃ ┃ ┣ 📜pre-receive.sample
 ┃ ┃ ┣ 📜prepare-commit-msg.sample
 ┃ ┃ ┣ 📜push-to-checkout.sample
 ┃ ┃ ┣ 📜sendemail-validate.sample
 ┃ ┃ ┗ 📜update.sample
 ┃ ┣ 📂info
 ┃ ┃ ┗ 📜exclude
 ┃ ┣ 📂logs
 ┃ ┃ ┣ 📂refs
 ┃ ┃ ┃ ┣ 📂heads
 ┃ ┃ ┃ ┃ ┗ 📜main
 ┃ ┃ ┃ ┗ 📂remotes
 ┃ ┃ ┃ ┃ ┗ 📂origin
 ┃ ┃ ┃ ┃ ┃ ┣ 📜HEAD
 ┃ ┃ ┃ ┃ ┃ ┗ 📜main
 ┃ ┃ ┗ 📜HEAD
 ┃ ┣ 📂objects
 ┃ ┃ ┣ 📂07
 ┃ ┃ ┃ ┗ 📜c3a8afecd014bf05604696b8fcc9f13ef4dc8a
 ┃ ┃ ┣ 📂0e
 ┃ ┃ ┃ ┗ 📜6207236f8788ccb3710f52a8eacd6f77c1bc7d
 ┃ ┃ ┣ 📂12
 ┃ ┃ ┃ ┗ 📜90a016a5864bc29e0e28fbc677d99d7fa41ee3
 ┃ ┃ ┣ 📂1c
 ┃ ┃ ┃ ┣ 📜14e6341aa2b3665bcb4177e60478f417a71227
 ┃ ┃ ┃ ┗ 📜19e192041017a785f3b61fd2feff9fa89278f2
 ┃ ┃ ┣ 📂1f
 ┃ ┃ ┃ ┗ 📜48bbd2ba464f6e311c563a6fc75acc5e10239d
 ┃ ┃ ┣ 📂40
 ┃ ┃ ┃ ┗ 📜b3a598fea51c0b5d0f8433efa919637679726e
 ┃ ┃ ┣ 📂47
 ┃ ┃ ┃ ┗ 📜3d436d74e5946af655c0793b1fb5cb27398e21
 ┃ ┃ ┣ 📂48
 ┃ ┃ ┃ ┗ 📜9df5f13a4a70fb5ddd01238acece9651acfc8b
 ┃ ┃ ┣ 📂50
 ┃ ┃ ┃ ┗ 📜4feb80973335e683fdca8ddbb97f4d384e5fc0
 ┃ ┃ ┣ 📂63
 ┃ ┃ ┃ ┗ 📜2b5f4f8f702dd5f2bbbb0016a501d799e171b3
 ┃ ┃ ┣ 📂66
 ┃ ┃ ┃ ┗ 📜0ecb230ab4d0300794a153f7dca15208a3911a
 ┃ ┃ ┣ 📂7a
 ┃ ┃ ┃ ┗ 📜ca4fcfaf6a3d7e01abac0a439b0160d7d97764
 ┃ ┃ ┣ 📂7e
 ┃ ┃ ┃ ┗ 📜6ebd739964a6640e0ce260c6fdc264fd60e4c9
 ┃ ┃ ┣ 📂7f
 ┃ ┃ ┃ ┗ 📜18bcef75a86e05cd59a084b51fe7eee2cee3a5
 ┃ ┃ ┣ 📂81
 ┃ ┃ ┃ ┗ 📜23a484e48e5b63593bf0a80bc68b394d28e64a
 ┃ ┃ ┣ 📂82
 ┃ ┃ ┃ ┗ 📜7faf2c6f7b37979e7b08e5bd358ad6765d7f35
 ┃ ┃ ┣ 📂8d
 ┃ ┃ ┃ ┗ 📜cc69f96c0bd98e522206ed598b6a3d63dee4ce
 ┃ ┃ ┣ 📂96
 ┃ ┃ ┃ ┗ 📜340dbd96e268ae7e0beb5e759b9d7e45a7a4cf
 ┃ ┃ ┣ 📂98
 ┃ ┃ ┃ ┗ 📜5ba52e5f1737bd9346a11fe9c11388c3a3277f
 ┃ ┃ ┣ 📂9c
 ┃ ┃ ┃ ┗ 📜abcf44f2dfa71f03765fb5aa9750dd35b34cca
 ┃ ┃ ┣ 📂9e
 ┃ ┃ ┃ ┗ 📜139fce8dc0487b9da7a9ab75c692a012b2f8a8
 ┃ ┃ ┣ 📂ad
 ┃ ┃ ┃ ┗ 📜7273b55badf93219a6749812d5e35fd4f14fbd
 ┃ ┃ ┣ 📂af
 ┃ ┃ ┃ ┗ 📜164f9fc407824ce60af43b1db30a4169b84f04
 ┃ ┃ ┣ 📂b5
 ┃ ┃ ┃ ┗ 📜24cffe0bb32b2ca4c6d3a5e8d22d9a7ed45d23
 ┃ ┃ ┣ 📂b9
 ┃ ┃ ┃ ┗ 📜b4b321f5e818bc460fd878e97715ab4e1f4242
 ┃ ┃ ┣ 📂ba
 ┃ ┃ ┃ ┗ 📜a6fb777235dac836fd6472a3d3b244ba2f022c
 ┃ ┃ ┣ 📂cc
 ┃ ┃ ┃ ┗ 📜ade5c4061e180e341a8603f068e37716adcb6f
 ┃ ┃ ┣ 📂d3
 ┃ ┃ ┃ ┗ 📜1e303039d4039a6a45ac45254ce384cb114ba1
 ┃ ┃ ┣ 📂d6
 ┃ ┃ ┃ ┗ 📜e7f49393c5ed66df52f6921de9c3cb5b23fa8a
 ┃ ┃ ┣ 📂e0
 ┃ ┃ ┃ ┗ 📜78249ee589c4516f1ead34e706d4af4aa36d18
 ┃ ┃ ┣ 📂e5
 ┃ ┃ ┃ ┗ 📜f4536034fdde503ada66ae008999010750fe17
 ┃ ┃ ┣ 📂e6
 ┃ ┃ ┃ ┗ 📜9de29bb2d1d6434b8b29ae775ad8c2e48c5391
 ┃ ┃ ┣ 📂ea
 ┃ ┃ ┃ ┗ 📜0f527587b9750651c341276e76cd95f44e4158
 ┃ ┃ ┣ 📂f2
 ┃ ┃ ┃ ┗ 📜34a059a9d4f192b60bc2f906d01d1430382379
 ┃ ┃ ┣ 📂fd
 ┃ ┃ ┃ ┗ 📜338b60be688a109ca0e58c10fc49cd280705d5
 ┃ ┃ ┣ 📂info
 ┃ ┃ ┗ 📂pack
 ┃ ┣ 📂refs
 ┃ ┃ ┣ 📂heads
 ┃ ┃ ┃ ┗ 📜main
 ┃ ┃ ┣ 📂remotes
 ┃ ┃ ┃ ┗ 📂origin
 ┃ ┃ ┃ ┃ ┣ 📜HEAD
 ┃ ┃ ┃ ┃ ┗ 📜main
 ┃ ┃ ┗ 📂tags
 ┃ ┣ 📜.MERGE_MSG.swp
 ┃ ┣ 📜COMMIT_EDITMSG
 ┃ ┣ 📜config
 ┃ ┣ 📜description
 ┃ ┣ 📜FETCH_HEAD
 ┃ ┣ 📜HEAD
 ┃ ┣ 📜index
 ┃ ┗ 📜ORIG_HEAD
 ┣ 📂.vscode
 ┃ ┗ 📜launch.json
 ┣ 📂Images
 ┃ ┣ 📜brick-1.webp
 ┃ ┣ 📜brick-3.webp
 ┃ ┣ 📜brick-4.webp
 ┃ ┣ 📜cement-1.webp
 ┃ ┣ 📜cement-2.webp
 ┃ ┣ 📜cement-3.png
 ┃ ┣ 📜gardening tools 2.jpg
 ┃ ┣ 📜Gardening tools.png
 ┃ ┣ 📜gradening tools 1.webp
 ┃ ┣ 📜grinder.png
 ┃ ┣ 📜light bulb.avif
 ┃ ┣ 📜logo.png
 ┃ ┣ 📜muthc-brick.webp
 ┃ ┣ 📜paint brush.jpg
 ┃ ┣ 📜Paint.jpg
 ┃ ┣ 📜Pine 2.jpg
 ┃ ┣ 📜pine wood.jpg
 ┃ ┣ 📜Plumbing fittings.jpg
 ┃ ┣ 📜plumbing pipes.jpg
 ┃ ┣ 📜power tool 1.webp
 ┃ ┣ 📜SA Pine.webp
 ┃ ┣ 📜Tool Box.webp
 ┃ ┗ 📜Wires.avif
 ┣ 📜about.html
 ┣ 📜contact.html
 ┣ 📜index.html
 ┣ 📜products.html
 ┣ 📜specials.html
 ┗ 📜styles.css
