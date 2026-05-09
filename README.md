[![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square&logo=javascript)](https://www.javascript.com/)
[![Claude API](https://img.shields.io/badge/Claude-API-purple?style=flat-square)](https://anthropic.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Global Hack Week](https://img.shields.io/badge/Global%20Hack%20Week-2026-red?style=flat-square)](https://mlh.io/)

---

[![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square&logo=javascript)](https://www.javascript.com/)
[![Claude API](https://img.shields.io/badge/Claude-API-purple?style=flat-square)](https://anthropic.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Global Hack Week](https://img.shields.io/badge/Global%20Hack%20Week-2026-red?style=flat-square)](https://mlh.io/)

---

[![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=flat-square&logo=javascript)](https://www.javascript.com/)
[![Claude API](https://img.shields.io/badge/Claude-API-purple?style=flat-square)](https://anthropic.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Global Hack Week](https://img.shields.io/badge/Global%20Hack%20Week-2026-red?style=flat-square)](https://mlh.io/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=flat-square&logo=github)](https://github.com/artemisct-QA/ai-test-script-generator)

---

# AI Test Script Generator 🤖

Auto-generate production-ready test automation scripts from API specifications using Claude AI.

## ✨ Features

- **pytest Support** - Generate Python tests with fixtures, mocking, and comprehensive assertions
- **Jest Support** - Generate JavaScript tests with describe blocks and mock setup
- **Multiple Scenarios** - Automatically generates happy path, error cases, and edge cases
- **Authentication Support** - Handles Bearer tokens, API keys, and custom headers
- **Production Quality** - Generated code includes proper error handling and realistic test data

## 🚀 Quick Start

```bash
pip3 install -r requirements.txt
npm install
export ANTHROPIC_API_KEY="sk-ant-your-key"
python3 generate_pytest.py --spec "Test GET /api/status endpoint"
node generate_jest.js --spec "Test GET /api/users endpoint"
```
## 📊 Example Generated Tests

- **pytest**: ~200+ lines of production-quality code with fixtures, mocking, multiple test scenarios
- **Jest**: ~200+ lines of production-quality code with describe blocks and mock setup

## 🎯 Use Cases

- Rapidly generate test suites from API documentation
- Ensure consistent test structure across teams
- Reduce boilerplate in test automation
- Speed up SDET workflows

## 🛠 Tech Stack

- **Claude API** - AI-powered test generation
- **Python** - pytest implementation
- **Node.js** - Jest implementation
- **Anthropic SDK** - LLM integration

## 📈 Generated Test Coverage

Each generated test includes:
- ✅ Happy path tests
- ✅ Error case handling (4xx, 5xx responses)
- ✅ Authentication validation
- ✅ Field validation tests
- ✅ Edge case scenarios
- ✅ Proper mocking setup
- ✅ Meaningful assertions

## 🎓 Built During Global Hack Week 2026 - GenAI Track

SDET Portfolio Project demonstrating AI-powered test automation
