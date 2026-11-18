FROM python:3.14@sha256:e5de6bc932256f8138c2353023dc4fd24d010d72f6b5cb06be126f0a4cd53784

LABEL image_name="pandasai-sandbox"

# Install required Python packages
RUN pip install pandas numpy matplotlib

# Set the working directory inside the container
WORKDIR /app

# Default command keeps the container running (useful for testing or debugging)
CMD ["sleep", "infinity"]
