FROM python:3.14@sha256:1eb6b7d4b76454b1de8317863ac3213b678c337b27e604a4e3fb70bddbb2bad7

LABEL image_name="pandasai-sandbox"

# Install required Python packages
RUN pip install pandas numpy matplotlib

# Set the working directory inside the container
WORKDIR /app

# Default command keeps the container running (useful for testing or debugging)
CMD ["sleep", "infinity"]
