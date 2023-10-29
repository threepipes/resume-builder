FROM ghcr.io/mszep/pandoc_resume:master

RUN mkdir -p /home/app/resume -m 777
WORKDIR /home/app/resume
COPY pandoc_resume ./

ENTRYPOINT ["/entrypoint.sh"]
