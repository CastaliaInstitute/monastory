# Monastory - The Inquiry Institute

A digital sanctuary for deep inquiry and contemplative practice.

## About

Monastory is a project of the Inquiry Institute, reimagining the ancient monastic tradition for the digital age. We create conditions for deep work, sustained attention, and the cultivation of insight through structured inquiry and contemplative practice.

## Vision

In a world of constant noise and distraction, Monastory offers a refuge where seekers can:
- Engage in profound inquiry into fundamental questions
- Practice contemplative disciplines
- Connect with a community of fellow seekers
- Draw wisdom from ancient and modern traditions

## Setup

### Local Development

Simply open `index.html` in your browser to view the site locally.

### GitHub Pages Deployment

1. Push this repository to GitHub under the InquiryInstitute organization
2. Go to repository Settings → Pages
3. Set Source to "Deploy from a branch"
4. Select the `main` branch and `/ (root)` folder
5. Save and wait for deployment

### AWS Route 53 Configuration

To set up the subdomain `monastory.inquiry.institute`:

1. Log into AWS Console and navigate to Route 53
2. Select the hosted zone for `inquiry.institute`
3. Create a new record:
   - Record name: `monastory`
   - Record type: `CNAME`
   - Value: `inquiryinstitute.github.io` (or your GitHub Pages domain)
   - TTL: 300
4. Save the record

### Custom Domain on GitHub Pages

1. In your GitHub repository, go to Settings → Pages
2. Under "Custom domain", enter: `monastory.inquiry.institute`
3. Wait for DNS check to complete
4. Enable "Enforce HTTPS" once DNS is verified

## Structure

- `index.html` - Main landing page
- `styles.css` - Styling and visual design
- `README.md` - This file

## Philosophy

Monastory embodies:
- **Deep Inquiry**: Asking questions that matter
- **Contemplative Space**: Sanctuary for reflection and inner work
- **Community**: Fellow travelers on the path of inquiry
- **Wisdom Traditions**: Honoring perennial questions while remaining open to new insights

## Contributing

This is a living project. Contributions that align with the contemplative and inquiry-focused mission are welcome.

## License

© The Inquiry Institute. All rights reserved.
