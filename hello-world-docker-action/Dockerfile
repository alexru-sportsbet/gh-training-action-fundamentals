# Use the Alpine 3.10 base image
FROM alpine:3.10

# Set the working directory
WORKDIR /usr/src/app

# Copy the entrypoint.sh script into the container
COPY entrypoint.sh .

# Make the entrypoint.sh script executable
RUN chmod +x entrypoint.sh

# Define the default command to run the script
ENTRYPOINT ["./entrypoint.sh"]
