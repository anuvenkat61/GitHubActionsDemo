

curl -X POST \
-H "Accept: application/vnd.github+json" \
-H "Authorization: token {PAT}" \
-d '{"event_type": "webhook", "client_payload": {"key": "value"} }' \
https://api.github.com/repos/anuvenkat61/GitHubActionsDemo/dispatches