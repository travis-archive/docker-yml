# docker-yml
This is a proof of concept for leveraging Travis's directory caching for speeding up Docker builds. It works by configuring the Docker daemon to use a folder under current user's (Travis) control. That way you have the privileges to use the caching feature of Travis.
