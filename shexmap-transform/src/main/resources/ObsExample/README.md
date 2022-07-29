export PATH=$PATH:[BASE_DIR]/shex.js/packages/shex-cli/bin

In browser, open:

/Users/cnanjo/repository/third\ party/shex.js/packages/extension-map/doc/shexmap-simple.html

# Write Me

``` shell
git clone https://github.com/shexjs/shex.js
cd $_
npm ci
./node_modules/.bin/lerna bootstrap
export PATH=$PATH:$(pwd)/shex.js/packages/shex-cli/bin
```


## Run Me

``` shell
~/checkouts/shexSpec/shex.js/packages/shex-cli/bin/validate \
  -d observation-example-bloodpressure.ttl \
  -x Obs-smaller.shex \
  -m "<http://hl7.org/fhir/Observation/blood-pressure>@START"
```

