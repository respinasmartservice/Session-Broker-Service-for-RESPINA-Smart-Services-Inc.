# README.md

Session Broker Service for RESPINA Smart Services Inc.

This microservice implements:
 - Room creation and management via gRPC
 - Token-based authentication (JWT)
 - Quality-of-Service (QoS) parameter selection per session
 - Service discovery and distributed coordination via etcd

## Requirements
 - Go 1.20+
 - etcd v3 cluster accessible
 - Protoc + protoc-gen-go + protoc-gen-go-grpc

## Setup
1. Clone service into GOPATH.
