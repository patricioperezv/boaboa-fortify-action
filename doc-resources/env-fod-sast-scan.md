
{{include:env-fod-login.md}}

{{include:env-fod-release.md}}

{{include:env-package.md}}

**`EXTRA_FOD_SAST_SCAN_OPTS`**    
Optional: Extra FoD SAST scan options; see [`fcli fod sast-scan start` documentation]({{var:fcli-doc-base-url}}/manpage/fcli-fod-sast-scan-start.html)

**`DO_WAIT`**    
Optional: By default, this action will not wait until the scan has been completed. To have the workflow wait until the scan has been completed, set the `DO_WAIT` environment variable to `true`. Note that `DO_WAIT` is implied if `DO_EXPORT` is set to `true`; see below.

**`DO_EXPORT`**    
Optional: If set to `true`, this action will export scan results to the GitHub Security Code Scanning dashboard.