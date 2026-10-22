FROM python:3.14@sha256:90bdf58a84b9ed919c2942fddafd6c4c8256b22073cc95ecd2710ea255671eba

LABEL image_name="pandasai-sandbox"

# Install required Python packages
RUN pip install pandas numpy matplotlib

# Set the working directory inside the container
WORKDIR /app

# Default command keeps the container running (useful for testing or debugging)
CMD ["sleep", "infinity"]
