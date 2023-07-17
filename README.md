# grpc_test_automation
Automate GRPC server testing with GRPC client : This package contains following kinds of GRPC server based on how client is going to communicate with server :

	1. GRPC Server without TLS -> GRPC client with insecure channel
	2. GRPC Server with TLS -> GRPC client with secure channel without sharing public certificate chain
	3. GRPC Server with Mutual TLS -> GRPC client with secure channel with its own public certificate chain
