# Delete these from the docs repo

Old URLs redirect (see `redirects` in docs.json).

```bash
rm -rf ai-tools api-reference integrations documentation/sessions
```

- ai-tools/_, api-reference/introduction.mdx, api-reference/endpoint/_, api-reference/openapi.json: Mintlify starter template (plant store). The real spec is /openapi.json and stays.
- integrations/introduction.mdx: duplicate of the introduction.
- documentation/development.mdx, README.md: Mintlify starter.
- documentation/sessions/\*: /v1/sessions returns 410 in the engine; payment intents replace it.
