# justins_app/Dockerfile
FROM python:3.9-slim

# Install dependencies
RUN pip install streamlit

# Copy the app file into the container
COPY justins_app.py /app/justins_app.py

# Set the working directory
WORKDIR /app

# Expose the port Streamlit will run on
EXPOSE 8502

# Run the app
CMD ["streamlit", "run", "justins_app.py", "--server.port=8502", "--server.enableCORS=false"]
