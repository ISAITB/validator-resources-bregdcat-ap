# BRegDCAT-AP Validator

**Usage note:**
Please be informed that the BRegDCAT-AP validator is now being redirected to the [SEMIC SHACL Validator](https://www.itb.ec.europa.eu/shacl/semic-shacl/upload). 
The domain-aliases set in place will redirect the current validator ensuring that this change does not affect your existing setups for the BRegDCAT-AP validator.

In case any issues arise, kindly flag them in the [SEMIC SHACL Validator repository](https://github.com/SEMICeu/semic-shacl-validator/issues).





The files you may edit to adapt the validation are as follows:
* Folder `resources` contains the validation artefacts and vocabularies (in subfolders per validation type).
* File `resources\config.properties` contains the configuration that you may want to adapt.

To publish changes commit and push your updates. In 1-2 minutes the online service will be updated.

The online service is accessible as follows:
* Web UI: https://www.itb.ec.europa.eu/shacl/bregdcat-ap/upload.
* REST API (Swagger docs): https://www.itb.ec.europa.eu/shacl/swagger-ui.html (use 'bregdcat-ap' as the domain value in requests).
* REST API (Hydra docs): https://www.itb.ec.europa.eu/shacl/bregdcat-ap/api.
* SOAP API: https://www.itb.ec.europa.eu/shacl/soap/bregdcat-ap/validation?wsdl.
