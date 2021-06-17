<H2>Welcome to api automation via postman and generate HTML report</H2>

<H3>1. Install Newman Html extra repoter </H2>

    "npm install -g newman-reporter-htmlextra"


<H3>2. Command line to execute test with newman</H2>
 
Goto path where collection is saved  and Run script to execute test and generate report

     "newman run Test.postman_collection.json -r htmlextra" 
