# Wiremock

* Make sure the [WireMock](https://wiremock.org/) is present as JAR. Execution via cmdline
* Make sure mappings is present with the `call` and `make payment`

`> java -jar wiremock-standalone-3.3.1.jar`

Install [RESTer](https://addons.mozilla.org/de/firefox/addon/rester/) to verify the REST API

`POST` http://localhost:8080/makePayment
`GET` http://localhost:8080/callPayment

The simple tests can be run via SOAPUI and the according testplan

