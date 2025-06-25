# The ADK Playbook

A comprehensive collection of 12 practical examples for building AI agents with Google's Agent Development Kit (ADK). From simple chat agents to complex multi-agent systems with tools, persistence, and orchestration.

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Google Cloud Platform account
- Basic familiarity with Python and AI concepts

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/naakaarafr/The-ADK-Playbook.git
   cd The-ADK-Playbook
   ```

2. **Set up virtual environment**
   ```bash
   # Create virtual environment
   python -m venv .venv
   
   # Activate virtual environment
   # macOS/Linux:
   source .venv/bin/activate
   # Windows CMD:
   .venv\Scripts\activate.bat
   # Windows PowerShell:
   .venv\Scripts\Activate.ps1
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

### Google Cloud Setup

1. **Create Google Cloud Project**
   - Go to [Google Cloud Console](https://cloud.google.com/?hl=en)
   - Create a new project or select an existing one

2. **Get API Key**
   - Visit [Google AI Studio](https://aistudio.google.com/apikey)
   - Create an API key
   - Assign the key to your project
   - Connect to a billing account

3. **Configure Environment Variables**
   - Navigate to any example folder
   - Copy `.env.example` to `.env`
   - Replace the placeholder with your API key:
     ```
     GOOGLE_API_KEY=your_api_key_here
     ```
   - Repeat for each example you want to run

## 📚 Examples Overview

### 01. Basic Agent
**What you'll learn:** Introduction to ADK fundamentals
- Create your first AI agent
- Handle basic user interactions
- Understand the ADK architecture

### 02. Agent with Tools
**What you'll learn:** Extending agent capabilities
- Integrate external tools and APIs
- Function calling and tool execution
- Error handling and validation

### 03. LiteLLM Integration
**What you'll learn:** Model abstraction and flexibility
- Switch between different LLM providers
- Abstract away provider-specific details
- Configure multiple model backends

### 04. Structured Output
**What you'll learn:** Consistent response formatting
- Use Pydantic models for output schemas
- Ensure structured, validated responses
- Handle complex data types

### 05. Session Management
**What you'll learn:** Maintaining conversation state
- Implement session-based memory
- Handle multi-turn conversations
- Manage conversation context

### 06. Persistent Storage
**What you'll learn:** Data persistence across sessions
- Store agent data permanently
- Handle application restarts
- Database integration patterns

### 07. Multi-Agent Orchestration
**What you'll learn:** Coordinating multiple agents
- Design specialized agent roles
- Implement agent communication
- Solve complex tasks through collaboration

### 08. Stateful Agents
**What you'll learn:** Advanced state management
- Maintain complex application state
- Handle state transitions
- Implement stateful workflows

### 09. Event Callbacks
**What you'll learn:** Monitoring and responding to events
- Implement real-time event handling
- Monitor agent behaviors
- Create responsive systems

### 10. Pipeline Workflows
**What you'll learn:** Sequential agent processing
- Design multi-stage workflows
- Handle data flow between stages
- Implement error recovery

### 11. Parallel Agents
**What you'll learn:** Concurrent processing
- Execute agents in parallel
- Handle concurrent operations
- Optimize performance through parallelism

### 12. Iterative Refinement
**What you'll learn:** Self-improving agents
- Implement feedback loops
- Iterative output refinement
- Quality improvement mechanisms

## 🛠️ Usage

Each example is self-contained and can be run independently:

```bash
# Navigate to any example folder
cd basic-agent

# Copy and configure environment file
cp .env.example .env
# Edit .env with your Google API key

# Run the example
python main.py
```

## 🏗️ Project Structure

```
The-ADK-Playbook/
├── greeting_agent/
│   ├── main.py
│   └── .env.example
├── testing_tools/
│   ├── main.py
│   └── .env.example
├── ...
├── requirements.txt
└── README.md
```

## 📖 Documentation

- **[Official ADK Documentation](https://ai.google.dev/agentic)** - Complete ADK reference
- **[Google AI Studio](https://aistudio.google.com/)** - Development environment
- **[Agent Development Guide](https://ai.google.dev/agentic/docs)** - Comprehensive tutorials

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Add tests if applicable**
5. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
6. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
7. **Open a Pull Request**

### Contribution Guidelines
- Follow existing code style and patterns
- Include clear documentation for new examples
- Test your changes thoroughly
- Update README if adding new examples

## 📋 Requirements

- Python 3.8 or higher
- Google Cloud Platform account with billing enabled
- Basic understanding of:
  - Python programming
  - API concepts
  - AI/ML fundamentals

## 🚨 Troubleshooting

### Common Issues

**Authentication Error**
```
Error: API key not found
```
- Ensure your `.env` file contains a valid `GOOGLE_API_KEY`
- Verify the API key is assigned to your project
- Check that billing is enabled on your Google Cloud account

**Import Error**
```
ModuleNotFoundError: No module named 'google.generativeai'
```
- Activate your virtual environment
- Run `pip install -r requirements.txt`

**Rate Limiting**
```
Error: Quota exceeded
```
- Check your Google Cloud billing and quotas
- Implement rate limiting in your applications
- Consider upgrading your quota limits

### Getting Help

If you encounter issues:
1. Check the [Issues](https://github.com/naakaarafr/The-ADK-Playbook/issues) section
2. Review the official [ADK documentation](https://ai.google.dev/agentic)
3. Create a new issue with detailed information about your problem

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Google AI team for creating the Agent Development Kit
- The open-source community for inspiration and feedback
- Contributors who help improve this project

## 📞 Support

- **Issues:** [GitHub Issues](https://github.com/naakaarafr/The-ADK-Playbook/issues)
- **Discussions:** [GitHub Discussions](https://github.com/naakaarafr/The-ADK-Playbook/discussions)
- **Documentation:** [Official ADK Docs](https://ai.google.dev/agentic)

---

⭐ **Star this repository** if you find it helpful!

Built with ❤️ for the AI development community.
