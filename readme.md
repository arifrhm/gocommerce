# Gocommerce

go mod init gocommerce

go get -u github.com/gin-gonic/gin
go get -u github.com/jinzhu/gorm
go get -u github.com/jinzhu/gorm/dialects/mysql

go get github.com/dgrijalva/jwt-go

go tool pprof http://localhost:6060/debug/pprof/profile

export PATH=$(go env GOPATH)/bin:$PATH
