FROM python:3.14@sha256:a7097ae62ea4cf4fec036282cbf97f0d0b7b4f9cb286277951115fb30442527d

LABEL image_name="pandasai-sandbox"

# Install required Python packages
RUN pip install pandas numpy matplotlib

# Set the working directory inside the container
WORKDIR /app

# Default command keeps the container running (useful for testing or debugging)
CMD ["sleep", "infinity"]
