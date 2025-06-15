FROM python:3.11-slim

# Set work directory
WORKDIR /app

# Copy requirements (if you have one) or install Flask directly
RUN pip install flask

# Copy project files
COPY . .

# Expose port
EXPOSE 5000

# Run the app
CMD ["python", "app.py"]