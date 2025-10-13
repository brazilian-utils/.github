<div align="center">

# 🇧🇷 Brazilian Utils

### Utils libraries for Brazilian-specific businesses

[![Website](https://img.shields.io/badge/Website-brazilian--utils.com.br-blue)](https://brazilian-utils.com.br)
[![GitHub Stars](https://img.shields.io/github/stars/brazilian-utils?style=social)](https://github.com/brazilian-utils)

</div>

---

## 📖 About

Brazilian Utils is an open-source organization focused on solving common problems faced in the development of applications for Brazilian businesses. We provide utilities for validating, formatting, and generating Brazilian-specific data such as:

- 📄 **CPF & CNPJ** - Validate, format, and generate Brazilian identification numbers
- 📮 **CEP** - Validate, format, and lookup postal codes
- 📞 **Phone Numbers** - Validate and format Brazilian phone numbers
- 🚗 **License Plates** - Support for both old and Mercosul formats
- 💰 **PIS/PASEP** - Validate and format social integration program numbers
- ⚖️ **Legal Process Numbers** - Handle Brazilian legal process identifiers
- 🗳️ **Voter ID** - Validate Brazilian electoral titles
- 🏛️ **IBGE Data** - Work with official Brazilian geographic codes
- 📧 **Email** - Brazilian-specific email validation
- 💵 **Currency** - Format and convert Brazilian Real values
- 🎉 **Holidays** - Check Brazilian national and state holidays
- ...and much more!

## 🚀 Available Implementations

We maintain libraries in multiple programming languages to serve different ecosystems:

| Language | Repository | Stars | Package |
|----------|-----------|-------|---------|
| **JavaScript/TypeScript** | [brazilian-utils/javascript](https://github.com/brazilian-utils/javascript) | ![Stars](https://img.shields.io/github/stars/brazilian-utils/javascript?style=social) | [![npm](https://img.shields.io/npm/v/@brazilian-utils/brazilian-utils)](https://www.npmjs.com/package/@brazilian-utils/brazilian-utils) |
| **Python** | [brazilian-utils/python](https://github.com/brazilian-utils/python) | ![Stars](https://img.shields.io/github/stars/brazilian-utils/python?style=social) | [![PyPI](https://img.shields.io/pypi/v/brutils)](https://pypi.org/project/brutils/) |
| **Go** | [brazilian-utils/go](https://github.com/brazilian-utils/go) | ![Stars](https://img.shields.io/github/stars/brazilian-utils/go?style=social) | - |
| **.NET (F#)** | [brazilian-utils/dotnet](https://github.com/brazilian-utils/dotnet) | ![Stars](https://img.shields.io/github/stars/brazilian-utils/dotnet?style=social) | - |
| **Ruby** | [brazilian-utils/ruby](https://github.com/brazilian-utils/ruby) | ![Stars](https://img.shields.io/github/stars/brazilian-utils/ruby?style=social) | - |
| **Rust** | [brazilian-utils/rust](https://github.com/brazilian-utils/rust) | ![Stars](https://img.shields.io/github/stars/brazilian-utils/rust?style=social) | - |

## 📚 Quick Start

### JavaScript/TypeScript

```bash
npm install @brazilian-utils/brazilian-utils
```

```javascript
import { isValidCPF, formatCPF } from '@brazilian-utils/brazilian-utils';

isValidCPF('12345678909'); // false
formatCPF('82178537464'); // '821.785.374-64'
```

### Python

```bash
pip install brutils
```

```python
from brutils import is_valid_cpf, format_cpf

is_valid_cpf('12345678909')  # False
format_cpf('82178537464')    # '821.785.374-64'
```

## 🌟 Why Brazilian Utils?

- ✅ **Comprehensive** - Covers a wide range of Brazilian-specific validations and utilities
- 🧪 **Well-Tested** - High test coverage ensures reliability
- 📦 **Zero Dependencies** - Lightweight libraries with minimal overhead
- 🌍 **Multi-Language** - Consistent APIs across different programming languages
- 🤝 **Community-Driven** - Built and maintained by the Brazilian developer community
- 📖 **Well-Documented** - Clear documentation and examples
- 🔄 **Actively Maintained** - Regular updates and improvements

## 🎯 2025 Roadmap

We're excited about the future! Here's what we're planning:

- 🔨 **Code Refactoring** - Simplifying and standardizing project structures
- 📚 **New Documentation** - Comprehensive docs covering all language implementations
- 🎊 **Version 1.0 Release** - Official V1 with migration guides
- 🐛 **Issue Resolution** - Addressing all pending community issues
- 🌐 **Expanded Language Support** - More programming language implementations

## 🤝 Contributing

We welcome contributions of all kinds! Whether you want to:

- 🐛 Report bugs or suggest features via [Issues](https://github.com/brazilian-utils/javascript/issues)
- 💬 Discuss ideas via [Discussions](https://github.com/brazilian-utils/javascript/discussions)
- 👨‍💻 Contribute code by opening Pull Requests
- 📖 Improve documentation
- 🌍 Add support for new languages

Check out individual repositories for contribution guidelines!

## 📄 License

All Brazilian Utils projects are released under the [MIT License](https://opensource.org/licenses/MIT).

## 💚 Support the Project

If Brazilian Utils has helped you, consider:

- ⭐ Starring our repositories
- 🐦 Sharing with your network
- 🤝 Contributing to the codebase
- 💬 Helping others in discussions

---

<div align="center">

**Built with ❤️ by the Brazilian developer community**

[Website](https://brazilian-utils.com.br) • [JavaScript](https://github.com/brazilian-utils/javascript) • [Python](https://github.com/brazilian-utils/python)

</div>
