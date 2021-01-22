# loan-wizard-azure-func

## A simple Azure Function using Core Tools

**To start the local functions host:** 

func start 

or 

func start "&"> ~/loan-wizard/output.txt "&" 

**To send an HTTP GET request to the locally-running function:**

curl.exe "http://localhost:7071/api/simple-interest" -w "\n" 

curl.exe "http://localhost:7071/api/simple-interest?principal=5000&rate=.035&term=36" -w "\n"
