FROM metabase/metabase:latest

USER root

# Future utilities
RUN apk add --no-cache curl jq
#curl is for HTTPS Requests & jq is for parsing JSON data

USER metabase

EXPOSE 3000