FROM python:3.14@sha256:be8ccd085666c34273c9dc5607c9842f8b2e3116128aae45148ce164c07ce09d

LABEL image_name="pandasai-sandbox"

# Install required Python packages
RUN pip install pandas numpy matplotlib

# Set the working directory inside the container
WORKDIR /app

# Default command keeps the container running (useful for testing or debugging)
CMD ["sleep", "infinity"]
