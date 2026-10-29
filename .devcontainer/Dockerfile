ARG BASE
FROM ${BASE}

RUN if grep ubuntu:x:1000:1000 /etc/passwd >/dev/null; then userdel -f -r ubuntu; fi

ENV HISTSIZE=-1
ENV HISTFILESIZE=-1
ENV HISTFILE="/home/coder/.cache/._bash_history"
