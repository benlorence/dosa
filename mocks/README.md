# Mocks generated by mockgen.

These are the commands used to generate the mocks found here.
Currently generated using github.com/rkuris/mock to reduce the
number of warnings from golint.

mocks/client.go:

    mockgen -package mocks github.com/uber-go/dosa Client,AdminClient > mocks/client.go

mocks/connector.go:

    mockgen -package mocks github.com/uber-go/dosa Connector > mocks/connector.go

OR just run `make mocks`
