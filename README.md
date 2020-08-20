A logstash filter to parse CloudFront logs and turn the Edge Location into an actual city name.

* s3 input filter to read data from an s3 bucket, ensure you set the type property to 'cloudfront'.
* iata.yaml dictioanry in a useful spot.
* parse filter in the config dir, pointing at the correct iata dictionary filepath.
* make reports with actual city names.
