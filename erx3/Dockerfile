FROM debian:9.5-slim  
ADD entrypoint.sh /entrypoint.sh 
RUN chmod +x /entrypoint.sh 
ENTRYPOINT ["/entrypoint.sh"]
ADD test.sh /test.sh
ENTRYPOINT ["/test.sh"]
