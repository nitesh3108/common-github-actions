FROM golang:1.23

LABEL "com.github.actions.name"="go-code-formatter-vetter"
LABEL "com.github.actions.description"="Checks for formatting and vetting issues"
LABEL "com.github.actions.icon"="eye"
LABEL "com.github.actions.color"="gray-dark"

LABEL version="1.0.0"

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
