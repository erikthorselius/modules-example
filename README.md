# go mod init github.com/erikthorselius/modules-example
go: creating new go.mod: module github.com/erikthorselius/modules-example
# go get github.com/go-openapi/swag
# go get github.com/go-openapi/validate
# go get github.com/labstack/echo
# go clean -modcache

# jfrog rt go build --no-registry
[Info] Using go: go version go1.11 linux/amd64

go: finding github.com/mattn/go-isatty v0.0.4
go: finding github.com/go-openapi/validate v0.17.2
go: finding github.com/mattn/go-colorable v0.0.9
go: finding github.com/valyala/fasttemplate v0.0.0-20170224212429-dcecefd839c4
go: finding github.com/go-openapi/swag v0.17.2
go: finding github.com/labstack/gommon v0.2.7
go: finding github.com/valyala/bytebufferpool v1.0.0
go: finding github.com/labstack/echo v3.3.5+incompatible
go: finding golang.org/x/crypto v0.0.0-20181106171534-e4dc69e5b2fd
go: finding github.com/davecgh/go-spew v1.1.1
go: finding github.com/mailru/easyjson v0.0.0-20180823135443-60711f1a8329
go: finding github.com/stretchr/testify v1.2.2
go: finding github.com/pmezard/go-difflib v1.0.0
go: finding gopkg.in/yaml.v2 v2.2.1
go: finding github.com/go-openapi/analysis v0.17.0
go: finding github.com/go-openapi/spec v0.17.0
go: finding github.com/go-openapi/jsonpointer v0.17.0
go: finding github.com/go-openapi/loads v0.17.0
go: finding github.com/go-openapi/strfmt v0.17.0
go: finding github.com/go-openapi/errors v0.17.0
go: finding github.com/go-openapi/swag v0.17.0
go: finding github.com/go-openapi/runtime v0.0.0-20180920151709-4f900dc2ade9
go: finding github.com/asaskevich/govalidator v0.0.0-20180720115003-f9ffefc3facf
go: finding github.com/pborman/uuid v1.2.0
go: finding github.com/globalsign/mgo v0.0.0-20180905125535-1ca0a4f7cbcb
go: finding github.com/mitchellh/mapstructure v1.1.2
go: finding gopkg.in/check.v1 v0.0.0-20161208181325-20d25e280405
go: finding github.com/go-openapi/analysis v0.0.0-20180825180245-b006789cd277
go: finding golang.org/x/text v0.3.0
go: finding github.com/go-openapi/jsonreference v0.17.0
go: finding github.com/PuerkitoBio/purell v1.1.0
go: finding golang.org/x/net v0.0.0-20181005035420-146acd28ed58
go: finding github.com/PuerkitoBio/urlesc v0.0.0-20170810143723-de5bf2ad4578
go: finding github.com/google/uuid v1.0.0
go: downloading github.com/labstack/echo v3.3.5+incompatible
go: downloading github.com/labstack/gommon v0.2.7
go: downloading golang.org/x/crypto v0.0.0-20181106171534-e4dc69e5b2fd
go: downloading github.com/mattn/go-isatty v0.0.4
go: downloading github.com/valyala/fasttemplate v0.0.0-20170224212429-dcecefd839c4
go: downloading github.com/mattn/go-colorable v0.0.9
go: downloading github.com/valyala/bytebufferpool v1.0.0

# jfrog rt go-publish go --self=false --deps=ALL
[Info] Using go: go version go1.11 linux/amd64

[Info] Publishing package dependencies...
[Info] Publishing: github.com/labstack/echo:v3.3.5+incompatible to go
[Info] Publishing: github.com/mattn/go-isatty:v0.0.4 to go
[Info] Publishing: github.com/labstack/gommon:v0.2.7 to go
[Info] Publishing: github.com/mattn/go-colorable:v0.0.9 to go
[Info] Publishing: golang.org/x/crypto:v0.0.0-20181106171534-e4dc69e5b2fd to go
[Info] Publishing: github.com/valyala/bytebufferpool:v1.0.0 to go
[Info] Publishing: github.com/valyala/fasttemplate:v0.0.0-20170224212429-dcecefd839c4 to go
{
  "status": "success",
  "totals": {
    "success": 7,
    "failure": 0
  }
}

export GOPROXY="https://artifactory.example.com/artifactory/api/go/go"
# go clean -modcache
# go build
go: finding github.com/valyala/bytebufferpool v1.0.0
go: finding github.com/go-openapi/validate v0.17.2
go: finding github.com/go-openapi/swag v0.17.2
go: finding github.com/mattn/go-isatty v0.0.4
go: finding github.com/valyala/fasttemplate v0.0.0-20170224212429-dcecefd839c4
go: finding github.com/labstack/gommon v0.2.7
go: finding github.com/labstack/echo v3.3.5+incompatible
go: finding github.com/mattn/go-colorable v0.0.9
go: finding golang.org/x/crypto v0.0.0-20181106171534-e4dc69e5b2fd
go: github.com/go-openapi/swag@v0.17.2: unexpected status (https://artifactory.example.com/artifactory/api/go/go/github.com/go-openapi/swag/@v/v0.17.2.info): 404 Not Found
go: github.com/go-openapi/validate@v0.17.2: unexpected status (https://artifactory.example.com/artifactory/api/go/go/github.com/go-openapi/validate/@v/v0.17.2.info): 404 Not Found
go: error loading module requirements


