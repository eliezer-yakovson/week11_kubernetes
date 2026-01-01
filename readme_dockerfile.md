This Dockerfile builds a Python image, installs the requirements, and runs Streamlit on port 8080.
Build: docker build -t streamlit-app .
Run: docker run --rm -p 8080:8080 streamlit-app
