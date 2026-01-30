<div align="center">

# JKT48Connect

**Your Gateway to JKT48 Data Ecosystem**

[![API Status](https://img.shields.io/badge/API-Online-success)](https://v2.jkt48connect.my.id)
[![Documentation](https://img.shields.io/badge/Docs-Available-blue)](https://docs.jkt48connect.com)
[![NPM Package](https://img.shields.io/npm/v/@jkt48/core)](https://www.npmjs.com/package/@jkt48/core)
[![Discord](https://img.shields.io/discord/YOUR_DISCORD_ID?color=7289da&label=Discord&logo=discord&logoColor=white)](https://discord.gg/jkt48connect)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[Website](https://jkt48connect.com) • [Documentation](https://docs.jkt48connect.com) • [API](https://v2.jkt48connect.my.id) • [Discord Server](https://discord.gg/jkt48connect)

</div>

---

## About JKT48Connect

**JKT48Connect** is a comprehensive API ecosystem designed specifically for developers, fans, and communities who need reliable access to JKT48 data. We consolidate various JKT48 data sources into one unified, powerful, and easy-to-use API platform.

Our API system is already trusted and used by official JKT48 fanbase websites including **Cavallery**, **Nayrakuen**, and **FritzyForce**, serving thousands of fans daily with accurate and real-time information.

### What We Offer

- **Complete Member Data** - Access detailed information about all JKT48 members, including profiles, generations, and social media
- **Theater Schedules** - Real-time theater show schedules with complete setlist information
- **Live Streaming Integration** - Monitor live streams from IDN Live and Showroom
- **News & Events** - Stay updated with the latest JKT48 news and upcoming events
- **Multiple SDKs** - Support for Node.js, with more languages coming soon
- **Developer-Friendly** - Well-documented APIs with comprehensive guides and examples

---

## Trusted By Official JKT48 Fanbases

Our API system powers several official JKT48 fanbase websites, providing them with reliable and up-to-date data:

<div align="center">

### Official Fanbases Using JKT48Connect

| Fanbase | Description | Website |
|---------|-------------|---------|
| **Cavallery** | Official fanbase community | [Visit Site](#) |
| **Nayrakuen** | Official fanbase community | [Visit Site](#) |
| **FritzyForce** | Official fanbase community | [Visit Site](#) |

</div>

These official fanbases trust JKT48Connect to deliver accurate, real-time data for their communities. Join them and experience the reliability of our API infrastructure.

---

## Quick Start

### Installation

```bash
# Using npm
npm install @jkt48/core

# Using yarn
yarn add @jkt48/core

# Using pnpm
pnpm add @jkt48/core
```

### Basic Usage

```javascript
const jkt48Api = require('@jkt48/core');

// Get all JKT48 members
async function getMembers() {
  try {
    const apiKey = 'your-api-key-here';
    const members = await jkt48Api.members(apiKey);
    console.log(members);
  } catch (error) {
    console.error(error.message);
  }
}

getMembers();
```

### Free API Keys

Get started immediately with our free API keys (50 requests per key):
- `J48-9F2A7B1D`
- `J48-3C8E6F4A`
- `J48-7D1B9E5C`

For custom API keys with higher limits, contact us on WhatsApp: **+62 857-0147-9245**

---

## Our Projects

### Core Packages

| Package | Description | Status |
|---------|-------------|--------|
| **[@jkt48/core](https://github.com/JKT48Connect/jkt48-core)** | Main Node.js module for JKT48 API | ✅ Active |
| **[@jkt48connect-corp/sdk](https://github.com/JKT48Connect/sdk)** | Legacy SDK (deprecated, use @jkt48/core) | ⚠️ Deprecated |
| **[@jkt48connect-corp/baileys](https://github.com/JKT48Connect/baileys)** | WhatsApp API integration | ✅ Active |

### Bots & Applications

#### **Discord Bot** - Free to Use
Get JKT48 updates and information directly in your Discord server. Our Discord bot is completely free and easy to set up.

**Features:**
- Real-time member information lookup
- Theater schedule notifications
- Live stream alerts
- News and event updates
- Interactive commands for JKT48 data

**Add to Your Server:** [Invite Discord Bot](https://discord.com/api/oauth2/authorize?client_id=YOUR_BOT_ID&permissions=YOUR_PERMISSIONS&scope=bot%20applications.commands)

**Join Our Community:** [JKT48Connect Discord Server](https://discord.gg/jkt48connect)

#### **Other Bots**
- **WhatsApp Bot** - Interactive bot for JKT48 information
- **Telegram Bot** - Real-time notifications and data access

### Tools

- **CLI Tools** - Command-line interface for quick data access
- **Create JKT48 App** - Scaffolding tool to kickstart your JKT48 project
  ```bash
  npm create jkt48-app
  ```

---

## Features

### For Developers

- **Easy Integration** - Simple and intuitive API design
- **Comprehensive Documentation** - Detailed guides and examples at [docs.jkt48connect.com](https://docs.jkt48connect.com)
- **Flexible Authentication** - Support for API keys and priority tokens
- **High Performance** - Fast response times with efficient data caching
- **Auto Updates** - Data automatically synced with official sources
- **TypeScript Support** - Full type definitions included

### For Communities

- **Community Priority Access** - Special privileges for verified fan communities
- **Fanbase Support** - Dedicated features for official fanbase groups
- **Real-time Notifications** - Stay updated with instant alerts
- **Multi-platform Support** - Use across web, mobile, and desktop applications

---

## Our Ecosystem

JKT48Connect consists of specialized teams working together:

### **J-Force**
Focuses on package and module development, creating robust SDKs and libraries.

### **Zenova**
Specializes in website and bot development across multiple platforms (WhatsApp, Discord, Telegram).

### **JKT48Connect Core**
The parent team overseeing all projects and maintaining the API infrastructure.

---

## Priority Access

Get unlimited requests and enhanced support by joining our Priority Access program:

### Who Can Apply?

- Registered JKT48 fan communities
- Official fanbase groups
- Certified developers building JKT48-related applications
- Accredited media organizations covering JKT48
- Educational institutions and researchers

### Benefits

- Unlimited API requests
- No API key required
- Priority support
- Advanced analytics
- Custom endpoints (on request)

**[Apply for Priority Access →](https://docs.jkt48connect.com/priority-access)**

---

## Documentation

Visit our comprehensive documentation at **[docs.jkt48connect.com](https://docs.jkt48connect.com)** for:

- Getting Started Guide
- API Reference
- Code Examples
- Tutorials
- FAQ
- Troubleshooting

---

## Contributing

We welcome contributions from the community! Whether it's:

- Bug reports
- Feature requests
- Documentation improvements
- Code contributions

Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request.

---

## Support & Contact

Need help? We're here for you!

- **Email**: support@jkt48connect.com
- **WhatsApp**: +62 857-0147-9245
- **Discord Server**: [Join JKT48Connect Community](https://discord.gg/jkt48connect)
- **Twitter**: [@JKT48Connect](https://twitter.com/jkt48connect)
- **Documentation**: [docs.jkt48connect.com](https://docs.jkt48connect.com)

Get support, report issues, request features, or chat with other developers and JKT48 fans in our Discord server.

---

## Statistics

<div align="center">

![GitHub Stars](https://img.shields.io/github/stars/JKT48Connect?style=social)
![NPM Downloads](https://img.shields.io/npm/dm/@jkt48/core)
![API Uptime](https://img.shields.io/badge/Uptime-99.9%25-success)
![Active Users](https://img.shields.io/badge/Active%20Users-1000%2B-blue)
![Official Partners](https://img.shields.io/badge/Official%20Fanbases-3-orange)

**Trusted by 3+ official JKT48 fanbase communities**

</div>

---

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## Testimonials

> *"JKT48Connect API sangat membantu kami dalam menyediakan informasi real-time untuk member komunitas Cavallery. Sistemnya stabil dan data selalu update."*  
> — **Cavallery Team**, Official JKT48 Fanbase

> *"Dengan JKT48Connect, website Nayrakuen bisa memberikan pengalaman terbaik bagi para fans. API-nya mudah diintegrasikan dan dokumentasinya lengkap."*  
> — **Nayrakuen Team**, Official JKT48 Fanbase

> *"Sebagai official fanbase, kami butuh data yang akurat dan cepat. JKT48Connect memberikan itu semua. Highly recommended untuk developer JKT48 apps!"*  
> — **FritzyForce Team**, Official JKT48 Fanbase

> *"Nggak nyangka API-nya se-enak ini. Bikin bot buat data JKT48 jadi gampang banget, datanya juga lengkap pol!"*  
> — Developer Community

> *"Sebagai admin situs info JKT48, ini API paling top sih. Stabil banget, datanya lengkap."*  
> — JKT48 Fansite Admin

---

## Creator & Founder

<div align="center">

### **Valzyys**

*Developer & Founder of JKT48Connect*

The visionary behind the entire JKT48Connect ecosystem. Valzyys created and maintains all teams under the JKT48Connect umbrella, including J-Force and Zenova.

[![GitHub](https://img.shields.io/badge/GitHub-Valzyys-181717?style=for-the-badge&logo=github)](https://github.com/Valzyys)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Contact-25D366?style=for-the-badge&logo=whatsapp)](https://wa.me/6285701479245)

</div>

---

## Acknowledgments

Special thanks to:

- All contributors and developers in our community
- JKT48 fans who continue to support and use our services
- Our Priority Access partners
- Everyone who has helped make JKT48Connect better

---

<div align="center">

**Made with care by Valzyys and the JKT48Connect Team**

*Bringing JKT48 data to developers and fans worldwide*

[⬆ Back to Top](#jkt48connect)

</div>
