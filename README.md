# HWH Bunclody GAA Club Website

Official website for the Half Way House Bunclody GAA Club.

## 🏆 About

This is the official website for HWH Bunclody GAA Club, featuring information about the club, teams, facilities, and community involvement.

## 🚀 Deployment to Azure Static Web Apps

This website is configured for deployment to Azure Static Web Apps with automated CI/CD through GitHub Actions.

### Prerequisites

- Azure subscription
- GitHub repository with the code
- Azure Static Web Apps resource

### Deployment Steps

1. **Create Azure Static Web App**
   - Go to the Azure Portal
   - Create a new Static Web App resource
   - Connect it to your GitHub repository
   - Azure will automatically create the GitHub Actions workflow

2. **Configure GitHub Secrets**
   - The deployment token will be automatically added as `AZURE_STATIC_WEB_APPS_API_TOKEN`
   - No additional configuration needed

3. **Automatic Deployment**
   - Every push to the `main` branch triggers automatic deployment
   - Pull requests create preview environments

### Local Development

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd HWHBunclodyWebsite
   ```

2. Open in your preferred web server or IDE
3. The site is a static website - no build process required

### Project Structure

```
├── index.html              # Homepage
├── about.html              # About page
├── contact.html            # Contact information
├── ClubDev.html            # Club Development
├── ClubHistory.html        # Club History
├── Gallery.html            # Photo Gallery
├── Mission.html            # Club Mission
├── ColinByrneBursary.html  # Colin Byrne Bursary
├── OneClub.html           # One Club initiative
├── Community.html         # Community involvement
├── Packageoptions.html    # Package options
├── styles.css             # Main stylesheet
├── staticwebapp.config.json # Azure Static Web Apps config
└── .github/workflows/     # GitHub Actions workflow
```

### Features

- 📱 Responsive design for all devices
- 🎨 Modern, clean interface
- 🏃‍♂️ Club information and history
- 📸 Photo galleries
- 📞 Contact information
- 🔗 Social media integration
- 📰 News and updates

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

### License

This project is for the HWH Bunclody GAA Club. All rights reserved.

## 📞 Contact

For questions about the website or club, please contact the club directly through the contact page.

---

**HWH Bunclody GAA Club** - Building community through Gaelic games.
