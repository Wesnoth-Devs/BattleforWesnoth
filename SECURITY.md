# Security Policy

## 🔒 Supported Versions

We actively support and provide security updates for the following versions of Battle for Wesnoth:

| Version | Supported          |
| ------- | ------------------ |
| 1.18.x  | ✅ Current stable  |
| 1.17.x  | ✅ LTS support     |
| 1.16.x  | ❌ End of life     |
| < 1.16  | ❌ Not supported   |

## 🚨 Reporting a Vulnerability

### How to Report
If you discover a security vulnerability, please report it responsibly:

**DO NOT** open a public issue for security vulnerabilities.

Instead, please:
1. **Email**: security@wesnoth.org
2. **Subject**: [SECURITY] Brief description
3. **Include**: Detailed description with steps to reproduce

### What to Include
Please provide as much information as possible:
- **Vulnerability Type**: What kind of security issue
- **Impact**: How it could be exploited
- **Affected Versions**: Which versions are vulnerable
- **Steps to Reproduce**: Detailed reproduction steps
- **Proof of Concept**: If available (responsibly)
- **Suggested Fix**: If you have ideas for mitigation

### Response Timeline
- **24 hours**: Initial acknowledgment
- **72 hours**: Initial assessment and severity classification
- **7 days**: Detailed response with timeline for fix
- **30 days**: Target resolution (may vary based on complexity)

## 🛡️ Security Best Practices

### For Players
- **Download only from official sources**:
  - [Official GitHub Releases](https://github.com/Wesnoth-Devs/BattleforWesnoth/releases)
  - [Official Website](https://wesnoth.org)
  - [Trusted package managers](package-managers)

- **Verify Downloads**:
  - Check file hashes when provided
  - Verify digital signatures
  - Use antivirus software

- **Keep Updated**:
  - Install security updates promptly
  - Enable automatic updates if available
  - Follow our security announcements

### For Developers
- **Code Security**:
  - Follow secure coding practices
  - Validate all user inputs
  - Use parameterized queries
  - Avoid hardcoded credentials

- **Dependencies**:
  - Keep dependencies updated
  - Monitor security advisories
  - Use dependency scanning tools
  - Remove unused dependencies

- **Build Security**:
  - Use reproducible builds
  - Sign release artifacts
  - Secure build environment
  - Audit build dependencies

## 🔍 Common Security Concerns

### Game-Specific Risks
- **Save File Manipulation**: 
  - We validate save file integrity
  - Avoid loading untrusted save files
  
- **Network Play**:
  - All network communications are validated
  - Use official servers when possible
  - Be cautious with unofficial mods

- **Mod Security**:
  - Review mods before installation
  - Only use mods from trusted sources
  - Understand mod permissions

### Data Privacy
- **Local Data**: Game saves and preferences are stored locally
- **Network Data**: Minimal data transmission during online play
- **Analytics**: We collect anonymous usage statistics (opt-out available)

## 🚀 Security Updates

### Update Delivery
- **Automatic**: Critical security fixes via auto-update (if enabled)
- **Manual**: Download from official releases page
- **Package Managers**: Updates through system package managers

### Update Notifications
Stay informed about security updates:
- **GitHub**: Watch repository for security announcements
- **Email**: Subscribe to security mailing list
- **RSS**: Follow our security feed
- **Social Media**: Follow official accounts

## 🔗 Security Resources

### Official Channels
- **Security Email**: security@wesnoth.org
- **General Contact**: contact@wesnoth.org
- **Security Advisories**: [GitHub Security Advisories](https://github.com/Wesnoth-Devs/BattleforWesnoth/security/advisories)

### External Resources
- **CVE Database**: [cve.mitre.org](https://cve.mitre.org)
- **Security Best Practices**: [OWASP Gaming Security](https://owasp.org)
- **Vulnerability Databases**: [NVD](https://nvd.nist.gov)

## 🏆 Security Hall of Fame

We recognize security researchers who responsibly disclose vulnerabilities:

### 2024
- [Researcher Name] - [Vulnerability Type] - [Date]

### 2023
- [Researcher Name] - [Vulnerability Type] - [Date]

*Would you like to be listed here? Report security issues responsibly!*

## ⚖️ Responsible Disclosure

### Our Commitment
- We take all security reports seriously
- We will respond promptly and professionally
- We will credit researchers appropriately
- We will not pursue legal action against responsible researchers

### Researcher Guidelines
- Make a good faith effort to avoid harm
- Don't access or modify other players' data
- Don't disrupt our services or infrastructure
- Give us reasonable time to fix issues before disclosure

## 📞 Emergency Contact

For critical security issues requiring immediate attention:
- **Primary**: security@wesnoth.org
- **Backup**: admin@wesnoth.org
- **Emergency**: [emergency contact method]

---

Thank you for helping keep Battle for Wesnoth secure! 🛡️🎮 