swagger:
	swagger generate spec -o ./swagger.yaml --scan-models

gen-client:
	cd sdk && swagger generate client -f ../swagger.yaml -A product-api