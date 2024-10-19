# marvins_app/Dockerfile
FROM python:3.9-slim

# Install Streamlit
RUN pip install streamlit

# Copy the app file into the container
COPY marvins_app.py /app/marvins_app.py

# Set the working directory
WORKDIR /app

# Expose the port Streamlit will run on
EXPOSE 8503

# Run the app
CMD ["streamlit", "run", "marvins_app.py", "--server.port=8503", "--server.enableCORS=false"]
