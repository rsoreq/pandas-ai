FROM python:3.14@sha256:22caa054c0d309b1eee6f448326a8821a674a75b98653247fe706db90491fc87

LABEL image_name="pandasai-sandbox"

# Install required Python packages
RUN pip install pandas numpy matplotlib

# Set the working directory inside the container
WORKDIR /app

# Default command keeps the container running (useful for testing or debugging)
CMD ["sleep", "infinity"]
