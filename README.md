# Exabeam NSA Rule Wizard

A comprehensive local web-based tool for creating and configuring new-scale analytics rules for Exabeam New-Scale Analytics through a simple wizard in a guided, step-by-step interface to generate properly structured JSON rule configurations.

## Disclaimer

This tool is **_unoffical experimental_** tool, use with caution!

### **6-Step Wizard Process**

1. **Choose Rule Type** - Select the appropriate rule category for your detection needs
2. **Basic Rule Information & Classification** - Configure rule metadata, family, and group classification
3. **Detection Configuration** - Set up detection parameters, scope, and MITRE ATT&CK mappings
4. **Event Filtering & Conditions** - Define filtering criteria and conditional logic
5. **Advanced Settings** - Fine-tune behavior, thresholds, and maturity levels
6. **Review and Generate** - Preview configuration and export JSON rule file

### **Key Capabilities**

- **MITRE ATT&CK Integration**: Built-in support for mapping rules to MITRE tactics and techniques
- **Rule Classification**: Organized family and group categorization system
- **Template ID Generation**: Automatic generation of unique rule identifiers
- **JSON Export**: One-click download of properly formatted rule configurations
- **Copy to Clipboard**: Quick copying of generated JSON for immediate use
- **Validation**: Form validation to ensure required fields are completed
- **Responsive Design**: Works across desktop and mobile devices

## Usage

### Getting Started

1. Open `nsa-rule-wizard.html` in any modern web browser
2. Follow the step-by-step wizard to configure your rule
3. Export your completed rule as a JSON file
4. Import the JSON file into Exabeam NSA

## File Structure

```
├── nsa-rule-wizard.html   # Main wizard application (standalone HTML file)
└── README.md              # This documentation
```

## Rule Output Format

The wizard generates JSON files compatible with security analytics platforms, containing:

- Rule metadata (name, description, family, group)
- Detection parameters and thresholds
- Event filtering criteria
- MITRE ATT&CK mappings
- Advanced configuration options

