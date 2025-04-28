# Smart Inventory AI (Setup Phase)

This project is an AI-based inventory tool to help Indian shopkeepers digitize their product listings using mobile camera images. The current phase focuses on setting up the foundational environment, config, and documentation.

## ✅ Completed:
- Directory structure initialized
- Core config and docs prepared
- Python 3.11.7 venv environment with PyTorch and MobileSAM ready

## ⌛ Next Steps:
- Add prediction agent
- Begin training setup
- Connect data preprocessing

## Development Environment

### Python Virtual Environment Setup

We use Python 3.11.7 with a virtual environment to ensure a clean, reproducible development environment.

#### Automated Setup (Recommended)

1. **Run the setup script** (requires administrator privileges):
   ```bat
   setup_env.bat
   ```
   This script will create the virtual environment, install all dependencies, and verify the installation.

#### Manual Setup

If you prefer to set up manually:

1. **Create a virtual environment**:
   ```bat
   python -m venv kirana360_env
   ```

2. **Activate the environment**:
   ```bat
   call kirana360_env\Scripts\activate.bat
   ```

3. **Install dependencies**:
   ```bat
   python -m pip install --upgrade pip setuptools wheel pip-tools
   python -m piptools compile requirements_final.in
   pip install -r requirements.txt
   ```

4. **Verify the environment**:
   ```bat
   python test_env.py
   ```

**Note:** For detailed setup instructions, see [Project Setup Guide](docs/project_setup.md)