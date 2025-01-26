# Code Citations

## License: unknown
https://github.com/sdelahaies/gtp-prompts/tree/8170b5819414016d5c58d0e2ad700ee9d3e6dc7b/nodejs-neo4j/Dockerfile

```
the working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the port the app runs on
EXPOSE 3000

# Start the application
```

