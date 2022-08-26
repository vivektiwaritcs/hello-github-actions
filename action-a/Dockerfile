FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint
RUN chmod +x /entrypoint
ENTRYPOINT ["/entrypoint"]
#!/bin/sh -l

sh -c "echo Hello world my name is $INPUT_MY_NAME"
