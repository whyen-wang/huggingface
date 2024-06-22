# huggingface
## Environment Setup
```bash
# Create virtual environment
python -m venv .env

# Activate virtual environment
source .env/bin/activate  # bash
.env/bin/Activate.ps1  # PowerShell
.env\Scripts\activate.bat  # cmd

# Install requirements
python -m pip install --upgrade pip
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install onnxruntime-gpu --extra-index-url https://aiinfra.pkgs.visualstudio.com/PublicPackages/_packaging/onnxruntime-cuda-12/pypi/simple/
pip install -r requirements.txt

# Check requirements
pip check
```