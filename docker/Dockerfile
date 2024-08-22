# Use the hugomods/hugo:latest image as the base image
FROM hugomods/hugo:latest

# Set the working directory
WORKDIR /src

# Copy the current directory contents to the working directory
COPY ../ /src

# Expose port 6969
EXPOSE 6969

# Set the command to run the Hugo server on port 6969 and bind it to all network interfaces
CMD ["hugo", "server", "-p", "6969", "--bind", "0.0.0.0"]