# CIS Controls Education Platform

![CIS Controls Platform](https://img.shields.io/badge/CIS-Controls%20v8.1-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Language](https://img.shields.io/badge/language-EN%20%7C%20AR-orange)

A comprehensive, interactive educational platform for learning and implementing the 18 CIS Critical Security Controls with open-source tools and practical guidance.

## 🌟 Features

- **📚 Complete CIS Controls Coverage**: All 18 controls with 153 safeguards
- **🌍 Bilingual Support**: Full English and Arabic interfaces
- **🛠️ Open Source Tools**: 50+ curated open-source security tools mapped to each control
- **💡 Implementation Tips**: Practical guidance for real-world implementation
- **🎯 Implementation Groups**: Filter by IG1, IG2, and IG3
- **🔍 Smart Search**: Quick search across all controls
- **📱 Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **🎨 Modern UI**: Clean, professional interface with dark theme

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. Fork this repository
2. Go to Settings → Pages
3. Select `main` branch as source
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Local Deployment

```bash
# Clone the repository
git clone https://github.com/SiteQ8/cis-controls-platform.git

# Navigate to directory
cd cis-controls-platform

# Open index.html in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Option 3: Web Server

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Then visit: http://localhost:8000
```

## 📋 CIS Controls Covered

The platform covers all 18 CIS Critical Security Controls:

1. **Inventory and Control of Enterprise Assets**
2. **Inventory and Control of Software Assets**
3. **Data Protection**
4. **Secure Configuration of Enterprise Assets and Software**
5. **Account Management**
6. **Access Control Management**
7. **Continuous Vulnerability Management**
8. **Audit Log Management**
9. **Email and Web Browser Protections**
10. **Malware Defenses**
11. **Data Recovery**
12. **Network Infrastructure Management**
13. **Network Monitoring and Defense**
14. **Security Awareness and Skills Training**
15. **Service Provider Management**
16. **Application Software Security**
17. **Incident Response Management**
18. **Penetration Testing**

## 🛠️ Open Source Tools Featured

The platform includes carefully selected open-source tools for each control:

- **Asset Management**: Open-AudIT, OCS Inventory, Snipe-IT, Ralph
- **Vulnerability Scanning**: OpenVAS, Trivy, Vuls
- **SIEM & Logging**: ELK Stack, Graylog, Wazuh, OSSEC
- **Network Security**: Suricata, Zeek, Security Onion, Snort
- **Identity Management**: FreeIPA, Keycloak, OpenLDAP
- **Backup**: Bacula, Restic, BorgBackup
- **And 30+ more tools...**

## 🌐 Language Support

The platform supports two languages with complete translations:

- **English**: Full interface and content
- **العربية (Arabic)**: Complete Arabic translation with RTL support

Switch languages using the toggle in the header.

## 📖 Usage Guide

### Browsing Controls

1. **View All Controls**: Browse the grid of all 18 controls
2. **Filter by IG**: Click IG1, IG2, or IG3 to filter by implementation group
3. **Search**: Use the search box to find specific controls
4. **View Details**: Click any control card to see full details

### Control Details Modal

Each control provides:

- **Description**: Comprehensive explanation of the control
- **Key Safeguards**: Specific safeguards with IDs
- **Open Source Tools**: Recommended tools with links
- **Implementation Tips**: Practical guidance for implementation

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `index.html`:

```css
:root {
    --color-bg-primary: #0f172a;
    --color-accent: #38bdf8;
    /* Modify other colors as needed */
}
```

### Adding Controls or Tools

Edit the `cisControls` object in the JavaScript section to add or modify controls and tools.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Issues**: Found a bug? Open an issue
2. **Suggest Tools**: Know a great open-source tool? Submit a PR
3. **Translations**: Help improve translations
4. **Documentation**: Enhance guides and documentation

### Contribution Guidelines

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **CIS (Center for Internet Security)** for developing the CIS Controls framework
- **Open Source Community** for the amazing security tools featured
- All contributors who help improve this platform

## ⚠️ Disclaimer

This platform is for educational purposes. CIS Controls® is a registered trademark of the Center for Internet Security, Inc. This project is not officially affiliated with or endorsed by CIS.

Always verify tool compatibility and security before deployment in production environments.

## 📞 Contact

**Developed by**: Ali AlEnezi

**GitHub**: [@SiteQ8](https://github.com/SiteQ8)

**Project Link**: [https://github.com/SiteQ8/cis-controls-platform](https://github.com/SiteQ8/cis-controls-platform)

## 🌟 Star History

If you find this project helpful, please consider giving it a star ⭐

## 📈 Version History

- **v1.0.0** (2026-03-03)
  - Initial release
  - All 18 CIS Controls
  - Bilingual support (EN/AR)
  - 50+ open-source tools
  - Responsive design

---

**Made in 🇰🇼 for the cybersecurity community**

