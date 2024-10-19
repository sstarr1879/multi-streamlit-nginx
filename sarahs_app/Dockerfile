
# sarahs_app/Dockerfile
FROM python:3.9-slim

# Install dependencies
RUN pip install streamlit

# Copy the app file into the container
COPY sarahs_app.py /app/sarahs_app.py

# Set the working directory
WORKDIR /app

# Expose the port Streamlit will run on
EXPOSE 8501

# Run the app
CMD ["streamlit", "run", "sarahs_app.py", "--server.port=8501", "--server.enableCORS=false"]
