# Environment Variables Setup

This project does not specifically require or provide instructions for setting up environment variables.

# Build

```sh
#docker:command=dev
docker build -t vonwig/prompts -f Dockerfile .
```

This command will build your Docker image with the tagname "vonwig/myproject:latest", using the Dockerfile in your current directory.

# Run

To run this project, use Docker run command:

```sh
#docker:command=dev
docker run vonwig/prompts
```