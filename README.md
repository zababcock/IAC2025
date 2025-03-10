aws cloudformation deploy \
  --template-file [filename.json] \ 
  --stack-name WebserversDev \
  --capabilities CAPABILITY_NAMED_IAM \
  --parameter-overrides KeyPair="KEY : PAIR HERE" YourIp=[YOUR IP HERE]
