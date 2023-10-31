# to create a stack
aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network-infra.yaml --parameters file://dev-parameter-file.json
# to delete a stack
aws cloudformation delete-stack \ --stack-name dev-network-infra-pf