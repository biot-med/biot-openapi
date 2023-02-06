BioT uses the REST convention in it different APIs and the documentation of the different APIs can be found [here](ref:getting-started).

You can always make direct API calls, but if you prefer you may auto generate an SDK that will wrap these API calls and make save development of boilerplate code.

To generate the SDK you will have to use the JSON files supplied by BioT for each release.  
These files can be found here:  
<https://bitbucket.org/softimize/biot-openapi>

Navigate to version of your platform and locate the JSON files from there.  
Next to generate the SDK use the [OpenAPI Generator](https://github.com/OpenAPITools/openapi-generator) to generate the actual SDK.