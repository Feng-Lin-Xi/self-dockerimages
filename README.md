# self-dockerimages
构建镜像 docker build -t <image:tag> -f <Dockerfile_xxx> .
已验证的Dockerfile
Dockerfile_chrome : 基础镜像 debian:bullseye  , 安装了google-chrome-stable、wkhtmltopdf 软件

Dockerfile_ruby : 基础镜像 buildpack-deps:bullseye ,安装ruby2.3.1环境，bundle2.0.1 、passenger+nginx 、google-chrome, 该镜像用于公司智图服务