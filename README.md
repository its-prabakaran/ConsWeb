# Siva Infra & Design Consultants Website

A responsive, dependency-free static website designed for GitHub Pages and standard web hosting.

## Working features
- Responsive navigation and mobile menu
- English/Tamil content switch for primary website copy
- Animated counters
- Service-to-contact selection
- Filterable project gallery and keyboard-accessible lightbox
- Project brief builder with copy/save behavior
- Auto/manual testimonial carousel
- FAQ accordions
- Contact form validation and local JSON enquiry download
- Local company-profile download
- Back-to-top button and scroll animations

## Publish to GitHub Pages
1. Extract the ZIP.
2. Create a GitHub repository and upload all three website files to its root.
3. In the repository, open Settings, then Pages.
4. Choose Deploy from a branch, select the main branch and the root folder, then save.

## Required changes before launch
- Replace phone, email and address placeholders.
- Replace demo photos and project names with authorized company content.
- Replace placeholder testimonials with approved statements.
- Change the WhatsApp link in index.html from #contact to your official wa.me link.
- Connect the enquiry form to Formspree, EmailJS or a custom backend. The supplied static form validates data and downloads it locally, but does not transmit anything.
- Add formal business details, terms and privacy statement as needed.

No build step or external JavaScript library is required. Images are loaded from Unsplash, so an internet connection is needed for those images.
