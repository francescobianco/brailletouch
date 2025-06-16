# Haptic Braille Research Project

![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)
![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile%20%7C%20Hardware-blue)
![Status](https://img.shields.io/badge/Status-Research%20Active-green)

An open source research project exploring haptic feedback systems for tactile Braille experiences on mobile devices, aimed at improving digital accessibility for blind and visually impaired users.

## 🎯 Project Overview

This research project investigates the use of standard mobile device vibration APIs to create meaningful tactile experiences for shape recognition and spatial understanding. The project provides multiple implementation approaches - from web-based prototypes to native mobile applications and hardware solutions.

**Key Features:**
- 🌐 **Web-based implementation** using HTML5 Vibration API
- 📱 **Native mobile app** built with Flutter for guaranteed haptic feedback
- 🔧 **Hardware prototype** using Arduino and dedicated vibration motors
- 📊 **Comprehensive research documentation** and comparative analysis
- 🔬 **Open source framework** for accessibility researchers and developers

## 📋 Repository Structure

```
haptic-braille-research/
├── PAPER.md                 # Complete research paper and findings
├── README.md               # This file
├── LICENSE                 # CC BY 4.0 license details
├── web/                    # Web-based implementation
│   ├── index.html         # Main haptic experience page
│   ├── styles.css         # Mobile-first responsive design
│   └── app.js             # Haptic feedback logic
├── mobile/                 # Flutter mobile application
│   ├── lib/               # Dart source code
│   ├── pubspec.yaml       # Dependencies
│   └── README.md          # Mobile setup instructions
├── hardware/               # Arduino hardware prototype
│   ├── haptic_braille.ino # Main Arduino sketch
│   ├── schematics/        # Circuit diagrams
│   └── README.md          # Hardware setup guide
├── docs/                   # Additional documentation
│   ├── api-analysis.md    # Vibration API compatibility study
│   ├── user-guidelines.md # Best practices for developers
│   └── testing-results.md # Preliminary testing outcomes
└── experiments/            # Research experiments and data
    ├── pattern-testing/    # Vibration pattern experiments
    ├── user-feedback/      # Informal user testing results
    └── performance/        # System performance measurements
```

## 📖 Documentation

### 📄 Research Paper
The complete research paper, methodology, findings, and academic references are available in:
**[PAPER.md](PAPER.md)**

The paper includes:
- Comprehensive literature review of haptic accessibility research
- Technical implementation details across web, mobile, and hardware platforms
- Comparative analysis of different approaches
- Evaluation of current API limitations and proposed solutions
- Future research directions and recommendations

### 🧪 Experiments and Data
Detailed experimental data, user testing protocols, and research findings are available upon request.

**For access to experimental data and research collaboration:**
📧 Contact: **bianco@javanile.org**

## 🚀 Quick Start

### Web Implementation
```bash
# Clone the repository
git clone https://github.com/francesco-bianco/haptic-braille-research.git

# Navigate to web directory  
cd haptic-braille-research/web

# Serve locally (HTTPS required for vibration API)
python -m http.server 8000 --bind 127.0.0.1
# Or use any local HTTPS server

# Open https://localhost:8000 on mobile device
```

### Mobile Application
```bash
cd mobile/

# Install Flutter dependencies
flutter pub get

# Run on connected device
flutter run
```

### Hardware Prototype
```bash
cd hardware/

# Upload haptic_braille.ino to Arduino
# Follow wiring diagram in schematics/
# See hardware/README.md for detailed setup
```

## 🔬 Research Contributions

This project contributes to accessibility research by:

1. **Demonstrating feasibility** of haptic shape recognition using standard mobile hardware
2. **Providing open source implementations** across multiple platforms
3. **Analyzing technical limitations** of current web APIs for haptic feedback
4. **Establishing design principles** for effective haptic user interfaces
5. **Creating a reusable framework** for accessibility researchers and developers

## 🎯 Use Cases and Applications

### Educational
- Teaching geometric concepts to blind students
- Spatial reasoning development
- Interactive learning materials

### Navigation and Mobility
- Indoor navigation assistance
- Obstacle detection prototypes
- Environmental mapping tools

### Gaming and Entertainment
- Accessible game development
- Haptic puzzle experiences
- Interactive storytelling

### Research and Development
- Haptic interface prototyping
- Accessibility technology testing
- User experience research

## 🛠️ Technical Requirements

### Web Implementation
- Modern browser with Vibration API support
- HTTPS connection (required for API access)
- Mobile device recommended for optimal haptic feedback
- **Note:** Limited iOS support due to Apple's API restrictions

### Mobile Application
- Flutter SDK 3.0+
- Android 5.0+ or iOS 12.0+
- Device with vibration motor
- ~15MB storage space

### Hardware Prototype
- Arduino Uno/Nano
- 3.5" resistive touchscreen
- 2x vibration motors (3V/60mA)
- Supporting electronics (transistors, resistors)
- 5V power supply for motors

## 📊 Performance and Compatibility

| Platform | Compatibility | Haptic Control | Development Ease | User Experience |
|----------|---------------|----------------|------------------|-----------------|
| Web API | Limited (60%) | Low | High | Inconsistent |
| Mobile Native | Excellent (95%) | High | Medium | Excellent |
| Hardware | Complete (100%) | Complete | Low | Optimal |

## 🤝 Contributing

We welcome contributions from researchers, developers, and accessibility advocates!

### How to Contribute
1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-improvement`)
3. **Commit** your changes (`git commit -m 'Add amazing improvement'`)
4. **Push** to the branch (`git push origin feature/amazing-improvement`)
5. **Open** a Pull Request

### Contribution Guidelines
- All code must consider accessibility requirements
- Documentation must be screen reader compatible
- Include tests for new haptic patterns or features
- Follow existing code style and conventions
- Update documentation for any API changes

### Research Collaboration
For academic collaboration, experimental data access, or research partnerships:
📧 **bianco@javanile.org**

## 📚 Academic Citations

If you use this work in your research, please cite:

```bibtex
@article{bianco2025haptic,
  title={Development of a Haptic System for Tactile Braille Experiences on Mobile Devices: An Open Source Approach to Digital Accessibility},
  author={Bianco, Francesco},
  journal={Open Source Accessibility Research Project},
  year={2025},
  url={https://github.com/francesco-bianco/haptic-braille-research}
}
```

**IEEE Format:**
```
F. Bianco, "Development of a Haptic System for Tactile Braille Experiences on Mobile Devices: An Open Source Approach to Digital Accessibility," Open Source Accessibility Research Project, 2025.
```

## 📄 License

This project is licensed under the **Creative Commons Attribution 4.0 International License** (CC BY 4.0).

### License Summary
- ✅ **Commercial use** - You can use this work for commercial purposes
- ✅ **Modifications** - You can modify and build upon this work
- ✅ **Distribution** - You can distribute this work and derivatives
- ⚠️ **Attribution required** - You must give appropriate credit to the original author
- ⚠️ **Share alike** - Derivative works should use compatible licenses

### Attribution Requirements
When using this work, you must:
1. **Credit the author**: Francesco Bianco
2. **Link to the original source**: This repository
3. **Indicate any changes** made to the original work
4. **Include license notice** in derivative works

See [LICENSE](LICENSE) for the full legal text.

## 🔗 Links and Resources

- 📄 **Full Research Paper**: [PAPER.md](PAPER.md)
- 🌐 **Live Web Demo**: [Demo Link] (when deployed)
- 📱 **Mobile App**: [App Store/Play Store links] (when published)
- 📧 **Contact Author**: bianco@javanile.org
- 🐛 **Report Issues**: [GitHub Issues](https://github.com/francesco-bianco/haptic-braille-research/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/francesco-bianco/haptic-braille-research/discussions)

## 🏆 Recognition and Awards

This research project aims to contribute to the accessibility community and advance digital inclusion through open source innovation.

**Potential Submissions:**
- ASSETS Conference (ACM SIGACCESS)
- CHI Conference on Human Factors in Computing Systems
- W4A Web for All Conference
- James Dyson Award for Design Innovation

## 🔄 Project Status

**Current Status**: Active Research  
**Last Updated**: June 2025  
**Version**: 1.0.0-research

### Roadmap
- [x] Web prototype implementation
- [x] Mobile application development
- [x] Hardware prototype design
- [x] Research paper completion
- [ ] User testing with blind community
- [ ] Conference paper submission
- [ ] Performance optimization
- [ ] Advanced pattern library development

## 💡 Future Development

### Planned Features
- Machine learning for personalized haptic patterns
- Integration with screen readers (NVDA, JAWS, VoiceOver)
- Support for complex geometric shapes
- Multi-finger interaction support
- IoT device connectivity for environmental feedback

### Research Opportunities
- Longitudinal user studies
- Cross-cultural accessibility research
- Integration with existing assistive technologies
- Development of haptic web standards

---

## 🙏 Acknowledgments

Special thanks to:
- The global accessibility research community
- Blind and visually impaired users who provided informal feedback
- Open source contributors and accessibility advocates
- Academic researchers in haptic technologies

---

**Made with ❤️ for digital accessibility**

*For questions, collaborations, or research partnerships, contact Francesco Bianco at bianco@javanile.org*
