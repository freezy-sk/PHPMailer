FROM instrumentisto/phpdoc:2

LABEL "repository"="https://github.com/PHPMailer/PHPMailer"

LABEL "com.github.actions.name"="Build Docs"
LABEL "com.github.actions.description"="Build Docs with phpDocumentor"
LABEL "com.github.actions.icon"="file-text"
LABEL "com.github.actions.color"="blue"

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
