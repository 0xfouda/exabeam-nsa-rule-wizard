# NSA Rule Wizard

A comprehensive web-based tool for creating and configuring analytics rules for security detection systems. This wizard provides a guided, step-by-step interface to generate properly structured JSON rule configurations.

## Features

### 🎯 **Rule Type Support**
- **Context Feature Rules**: Statistical and behavioral analysis rules
- **Fact Feature Rules**: Event-based detection rules  
- **Count Profile Rules**: Threshold and counting-based rules
- **Histogram Rules**: Distribution analysis rules
- **Custom Rules**: Flexible rule definitions

### 📋 **6-Step Wizard Process**

1. **Choose Rule Type** - Select the appropriate rule category for your detection needs
2. **Basic Rule Information & Classification** - Configure rule metadata, family, and group classification
3. **Detection Configuration** - Set up detection parameters, scope, and MITRE ATT&CK mappings
4. **Event Filtering & Conditions** - Define filtering criteria and conditional logic
5. **Advanced Settings** - Fine-tune behavior, thresholds, and maturity levels
6. **Review and Generate** - Preview configuration and export JSON rule file

### 🔧 **Key Capabilities**

- **MITRE ATT&CK Integration**: Built-in support for mapping rules to MITRE tactics and techniques
- **Rule Classification**: Organized family and group categorization system
- **Template ID Generation**: Automatic generation of unique rule identifiers
- **JSON Export**: One-click download of properly formatted rule configurations
- **Copy to Clipboard**: Quick copying of generated JSON for immediate use
- **Validation**: Form validation to ensure required fields are completed
- **Responsive Design**: Works across desktop and mobile devices

### 📊 **Rule Families & Groups**

The wizard includes pre-configured rule families such as:
- Authentication & Access Control
- Data Exfiltration & Loss Prevention
- Malware & Threat Detection
- Network Security & Traffic Analysis
- Privilege Escalation & Lateral Movement
- System & Process Monitoring
- User Behavior Analytics
- And many more...

## Usage

### Getting Started

1. Open `nsa-rule-wizard.html` in any modern web browser
2. Follow the step-by-step wizard to configure your rule
3. Export your completed rule as a JSON file

### Example Workflow

1. **Select Rule Type**: Choose "Context Feature" for behavioral analysis
2. **Configure Basic Info**: 
   - Enter rule name: "Suspicious Login Patterns"
   - Add description and select appropriate family/group
3. **Set Detection Parameters**: 
   - Configure detection scope and timeframes
   - Map to relevant MITRE ATT&CK techniques
4. **Define Filtering**: Specify event types and conditional logic
5. **Advanced Settings**: Set thresholds and maturity level
6. **Export**: Download the generated JSON rule file

## File Structure

```
├── nsa-rule-wizard.html     # Main wizard application (standalone HTML file)
├── groups-families/         # Rule classification data files
├── sample-rules/           # Example rule JSON files
└── README.md              # This documentation
```

## Technical Details

- **Technology**: Pure HTML5, CSS3, and vanilla JavaScript (no external dependencies)
- **Compatibility**: Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- **Data Format**: Generates industry-standard JSON rule configurations
- **Architecture**: Single-page application with embedded CSV data for rule classifications

## Rule Output Format

The wizard generates JSON files compatible with security analytics platforms, containing:

- Rule metadata (name, description, family, group)
- Detection parameters and thresholds
- Event filtering criteria
- MITRE ATT&CK mappings
- Advanced configuration options

## Contributing

This tool is designed for security analysts, threat hunters, and detection engineers who need to create structured analytics rules efficiently. The wizard simplifies complex rule creation while ensuring consistency and completeness.

## License

This project is developed for cybersecurity defense purposes and should be used in accordance with applicable security policies and regulations.

---

**Note**: This is a client-side tool that runs entirely in your browser. No data is transmitted to external servers, ensuring your rule configurations remain secure and private.