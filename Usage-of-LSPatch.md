```
Usage: <main class> [options] apks
  Options:
    -h, --help
      Print this message
    -r, --allowdown
      Allow downgrade installation by overriding versionCode to 1 (In most 
      cases, the app can still get the correct versionCode)
      Default: false
    -d, --debuggable
      Set app to be debuggable
      Default: false
    -m, --embed
      Embed provided modules to apk
      Default: []
    -f, --force
      Force overwrite exists output file
      Default: false
    -k, --keystore
      Set custom signature keystore. Followed by 4 arguments: keystore path, 
      keystore password, keystore alias, keystore alias password
      Default: [null, 123456, key0, 123456]
    --manager
      Use manager (Cannot work with embedding modules)
      Default: false
    -o, --output
      Output directory
      Default: .
    -l, --sigbypasslv
      Signature bypass level. 0 (disable), 1 (pm), 2 (pm+openat). default 0
      Default: 0
    -v, --verbose
      Verbose output
      Default: false
```
