# nginx-plus-docker
Dockerfiles to create NGINX Plus images. For complete documentation please refere to this [blog](https://www.nginx.com/blog/deploying-nginx-nginx-plus-docker/).

# Note: Never upload your NGINX Plus images to a public container registry such as Docker Hub. Doing so violates your license agreement.

## Creating a Docker Image for NGINX Plus

Before you can create the NGINX Plus Docker image, you have to download your version of the nginx-repo.crt and nginx-repo.key files. NGINX Plus customers can find them at the [customer portal](https://cs.nginx.com/); if you are doing a free trial of NGINX Plus, they were provided with your trial package. Copy the files to the directory `nginx/ssl/nginx-repo.key` `nginx/ssl/nginx-repo.crt`  respectfully. 

