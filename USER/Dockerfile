FROM almalinux:9
RUN dnf install git -y
RUN useradd gopi

USER gopi
CMD ["google.com"]
#ENTRYPOINT ["ping","google.com"]
ENTRYPOINT ["ping"]