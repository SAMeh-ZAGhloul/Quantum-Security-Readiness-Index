# Quantum Security Readiness Index (QSRI) Assessment Tool

A comprehensive web-based assessment tool designed to evaluate an organization's readiness for quantum threats and cryptographic transitions.

## 🎯 Overview

The Quantum Security Readiness Index (QSRI) is a standardized assessment framework that helps organizations:

- **Quantify** their preparedness for quantum threats
- **Benchmark** their security posture against industry standards
- **Prioritize** investments in post-quantum cryptography (PQC)
- **Track** progress across critical security dimensions

## 📊 Assessment Dimensions

The QSRI evaluates eight critical dimensions weighted by strategic importance:

| Dimension | Weight | Description |
|-----------|--------|-------------|
| **Cryptographic Inventory & Discovery** | 15% | Visibility over where cryptography is used in the organization |
| **Risk Assessment & Impact Analysis** | 10% | Understanding which assets and data are vulnerable to quantum threats |
| **Policy & Governance** | 10% | Leadership commitment, PQC strategy, and governance model |
| **Technology & Crypto Agility** | 15% | Ability to upgrade or swap cryptography with minimal disruption |
| **Migration Planning & Execution** | 20% | Defined strategy, timeline, and pilot migrations |
| **Vendor & Supply Chain Readiness** | 10% | Ensuring partners and products support PQC transition |
| **Regulatory & Compliance Alignment** | 10% | Alignment with national and international standards |
| **Awareness & Workforce Training** | 10% | Internal capacity building and training on quantum risks |

## 🎨 Features

### Interactive Assessment Interface
- **Real-time scoring** with dynamic updates as you adjust maturity levels
- **Visual radar chart** displaying maturity across all dimensions
- **Progressive bar charts** showing score distribution
- **Responsive design** that works on desktop and mobile devices

### Comprehensive Reporting
- **PDF export** functionality for assessment reports
- **Score interpretation** with readiness level classification
- **Detailed breakdowns** by dimension with actionable insights
- **Professional formatting** suitable for executive presentations

### Maturity Framework
- **6-level maturity scale** (0-5) from Unaware to Quantum-Safe Ready
- **Weighted scoring** system (0-100 total score)
- **Readiness classification** (Unprepared, Early-stage, Progressing, Mature)
- **Clear progression paths** for each dimension

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/SAMeh-ZAGhloul/Quantum-Security-Readiness-Index.git
   cd Quantum-Security-Readiness-Index
   ```

2. **Open in browser**
   Simply open `qsri-assessment.html` in any modern web browser. No build process required!

3. **Start assessing**
   - Review the current maturity levels (pre-populated with example data)
   - Adjust maturity levels using the dropdown selectors
   - Watch scores update in real-time
   - Generate PDF reports for documentation

### Using the Assessment

1. **Evaluate each dimension** by selecting the appropriate maturity level (0-5)
2. **Review your total score** and readiness classification
3. **Analyze the radar chart** to identify strengths and weaknesses
4. **Export results** to PDF for reporting and planning
5. **Track progress** over time by repeating the assessment

## 📈 Understanding Your Results

### Maturity Levels

| Level | Name | Description |
|-------|------|-------------|
| **0** | Unaware | No awareness of quantum threats; no action taken |
| **1** | Aware | Basic awareness; no formal program or inventory |
| **2** | Initiating | Initial assessments or inventories are in progress |
| **3** | Planning | Roadmaps, governance, and testbeds defined |
| **4** | Migrating | Pilot PQC/hybrid crypto deployments in production |
| **5** | Quantum-Safe Ready | Full cryptographic agility and PQC adoption |

### Readiness Classifications

| Score Range | Classification | Interpretation |
|-------------|----------------|----------------|
| **0-25** | Unprepared | Critical risk; no quantum defense strategy |
| **26-50** | Early-stage | Awareness stage; significant work required |
| **51-75** | Progressing | Partial readiness with some implementation |
| **76-100** | Mature | Quantum-safe ready with strong governance |

## 🔧 Technical Details

### Architecture
- **Single-page application** built with vanilla HTML, CSS, and JavaScript
- **No external dependencies** required for core functionality
- **PDF generation** powered by jsPDF library (loaded from CDN)
- **Responsive design** using CSS Grid and Flexbox

### Browser Support
- Modern browsers (Chrome 60+, Firefox 55+, Safari 12+, Edge 79+)
- Mobile browsers with full feature support
- No Internet Explorer support (due to modern CSS/JS features)

### File Structure
```
├── qsri-assessment.html    # Main assessment application
└── README.md              # This documentation file
```

## 🤝 Contributing

We welcome contributions to improve the QSRI assessment tool!

### Development Setup
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Test thoroughly in multiple browsers
5. Submit a pull request

### Contribution Guidelines
- Maintain backward compatibility
- Follow existing code style and structure
- Test changes across multiple browsers
- Update documentation for significant changes

## 📋 Roadmap

### Planned Enhancements
- [ ] Multi-language support
- [ ] Customizable weight configurations
- [ ] Historical score tracking
- [ ] Industry benchmark comparisons
- [ ] Integration with security frameworks (NIST, ISO 27001)
- [ ] API endpoints for programmatic access

### Future Features
- [ ] Team collaboration features
- [ ] Automated inventory discovery tools
- [ ] Vendor assessment modules
- [ ] Regulatory compliance mapping

## 📚 Resources

### Related Standards and Frameworks
- [NIST Post-Quantum Cryptography Standardization](https://csrc.nist.gov/projects/post-quantum-cryptography)
- [ETSI Quantum-Safe Cryptography](https://www.etsi.org/committee/qsc)
- [ENISA Post-Quantum Cryptography](https://www.enisa.europa.eu/topics/csirt-cert-services/knowledge-base/quantum-safe-cryptography)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

### Quantum Threat Timeline
- **Current**: Classical cryptography remains secure
- **2025-2030**: First quantum computers capable of breaking RSA-2048
- **2030+**: Widespread quantum computing adoption

## 📞 Support

For questions, support, or feature requests:

- **GitHub Issues**: [Open a new issue](https://github.com/SAMeh-ZAGhloul/Quantum-Security-Readiness-Index/issues)
- **Email**: [Contact us](mailto:info@solutions.fixed.global)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **NIST** for their work on post-quantum cryptography standardization
- **ETSI** and **ENISA** for quantum-safe cryptography guidance
- **Open source community** for tools like jsPDF that make this possible

---

**Ready to assess your quantum security readiness?** [Get started now!](#quick-start)