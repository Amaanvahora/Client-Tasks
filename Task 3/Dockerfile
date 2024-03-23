# Use Nginx Alpine as the base image
FROM nginx:alpine

# Expose port 80
EXPOSE 80

# Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Create a new file in the working directory
RUN echo "This is a test file created during the image build." > testfile.txt

# Copy files from your local 'my-local-directory' to the container's working directory
COPY ./my-local-directory/* ./
