## VS Code Plugin

Trying to use the VS Code plugin generated this error:

```
API Error: 400 {"error":{"message":"{"type":"error","error":{"type":"invalid_request_error","message":"Unexpected value(s) prompt-caching-scope-2026-01-05 for the anthropic-beta header. Please consult our documentation at docs.anthropic.com or try again without the header."},"request_id":"req_vrtx_011CXqfyPDWCV1c4zQcYCUJ6"}. Received Model Group=claude-sonnet-4-5-20250929\nAvailable Model Group Fallbacks=None","type":"None","param":"None","code":"400"}}
```

Claude told me this was due to newer API features that the extension is trying to use. Using the "install specific version" option on the plugin and using version 2.0 instead of 2.1 fixed this.