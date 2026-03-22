# careerpilot-ai

AI job application bot that auto-labels emails, tailors your resume & writes cover letters — fully automated, one-click send.

## Features

- **Email Auto-Labeling**: Automatically categorizes job application emails
- **Resume Tailoring**: Customizes your resume for each job application
- **Cover Letter Generation**: AI-powered cover letter writing
- **One-Click Send**: Streamlined application submission
- **Fully Automated**: Minimal manual intervention required

## Installation

### Prerequisites
- Python 3.8+
- Node.js (optional, for frontend)
- API keys for required services

### Setup

1. Clone the repository:
```bash
git clone https://github.com/HamzaBasar/careerpilot-ai.git
cd careerpilot-ai
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Configure environment variables:
```bash
cp .env.example .env
# Edit .env with your API keys and configuration
```

## Usage

```bash
python main.py
```

## Configuration

Create a `.env` file in the root directory with the following variables:

```
API_KEY=your_api_key_here
EMAIL_CONFIG=your_email_config
OPENAI_API_KEY=your_openai_key
```

## Project Structure

```
careerpilot-ai/
├── src/
├── config/
├── tests/
├── README.md
└── requirements.txt
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see LICENSE file for details.

## Contact

For questions or support, please open an issue on GitHub or contact the maintainer.