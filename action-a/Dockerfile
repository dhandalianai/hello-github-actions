FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello World"
LABEL "com.github.actions.description"="Write arguments to the standard output"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="http://github.com/octocat/hello-world"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Octocat <octocat@github.com>"

ADD entrypoint.sh /entrypoint.sh
ADD entrypoint2.sh /entrypoint2.sh
RUN chmod +x /entrypoint.sh
RUN chmod +x /entrypoint2.sh
ENTRYPOINT ["/entrypoint.sh"]
ENTRYPOINT ["/entrypoint2.sh"]

