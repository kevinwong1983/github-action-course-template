FROM mcr.microsoft.com/dotnet/core/sdk:3.1

LABEL "com.github.actions.name"="Action Release Milestone"
LABEL "com.github.actions.description"="Drafts a GitHub release base"

Label version="0.1.0"

COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]