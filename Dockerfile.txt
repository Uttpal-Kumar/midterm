# Use official Python image
FROM python:3.10-slim

# Set working directory
WORKDIR /app

# Copy file into container
COPY fibonacci.py .

# Run the script
CMD ["python", "fibonacci.py"]