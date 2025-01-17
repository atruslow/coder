## coder ping

Ping a workspace

```
coder ping <workspace> [flags]
```

### Options

```
  -h, --help               help for ping
  -n, --num int            Specifies the number of pings to perform. (default 10)
  -t, --timeout duration   Specifies how long to wait for a ping to complete. (default 5s)
  -v, --verbose            Enables verbose logging.
      --wait duration      Specifies how long to wait between pings. (default 1s)
```

### Options inherited from parent commands

```
      --global-config coder   Path to the global coder config directory.
                              Consumes $CODER_CONFIG_DIR (default "~/.config/coderv2")
      --header stringArray    HTTP headers added to all requests. Provide as "Key=Value".
                              Consumes $CODER_HEADER
      --no-feature-warning    Suppress warnings about unlicensed features.
                              Consumes $CODER_NO_FEATURE_WARNING
      --no-version-warning    Suppress warning when client and server versions do not match.
                              Consumes $CODER_NO_VERSION_WARNING
      --token string          Specify an authentication token. For security reasons setting CODER_SESSION_TOKEN is preferred.
                              Consumes $CODER_SESSION_TOKEN
      --url string            URL to a deployment.
                              Consumes $CODER_URL
```

### SEE ALSO

- [coder](coder.md) -
