FROM python:3.14@sha256:edf6433343f65f94707985869aeaafe8beadaeaee11c4bc02068fca52dce28dd

LABEL image_name="pandasai-sandbox"

# Install required Python packages
RUN pip install pandas numpy matplotlib

# Set the working directory inside the container
WORKDIR /app

# Default command keeps the container running (useful for testing or debugging)
CMD ["sleep", "infinity"]
