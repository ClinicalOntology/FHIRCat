# Write Me

``` shell
git clone https://github.com/shexjs/shex.js
export PATH=$PATH:$(pwd)/shex.js/packages/shex-cli/bin/validate
```


## Run Me

``` shell
~/checkouts/shexSpec/shex.js/packages/shex-cli/bin/validate \
  -d observation-example-bloodpressure.ttl \
  -x Obs-smaller.shex \
  -m "<http://hl7.org/fhir/Observation/blood-pressure>@START"
```

