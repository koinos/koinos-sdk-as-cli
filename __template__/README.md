# ##_CONTRACT_NAME_##

## Build
```sh
# build the debug version
npm run build:debug
# or
npm exec koinos-sdk-as-cli build-all debug 0 ##_PROTO_PACKAGE_##.proto 

# build the release version
npm run build:release
# or
npm exec koinos-sdk-as-cli build-all release 0 ##_PROTO_PACKAGE_##.proto 
```

## Test
```sh
npm run test
# or
npm exec koinos-sdk-as-cli run-tests
```