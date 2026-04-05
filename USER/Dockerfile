FROM almalinux:9
RUN dnf install nginx -y
#root access required to create user or install packages
RUN useradd balaji
USER balaji
CMD [ "sleep","200" ]
