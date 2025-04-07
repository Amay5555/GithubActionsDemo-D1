# Creating the sample React App
  Used the npx create-react-app command to create the sample node app.
  
# Pushed it to Github
  Created a new Github repo and pushed the entire app onto the remote repository.

# Seting up of the Docker image
  Configured a dockerfile using node:18 as the base image, exposed port 3000 to access the webapp. Once configured, build and image and push it to a public dockerhub repository.

# Configuring main.yml file
  Using the Github actions sample syntax configured a simple workflow which triggers every single time there is a push or pull request. After that tests are run inside the container.
  Finally docker runs the webapp.
