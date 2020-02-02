# application artifact id - simple-http-client
this application does the following:
1. read a text file, name provided via command line, that contains HTTP request.
2. sends this request to the target web application.

# NON-FUNCTIONAL REQUIREMENTS:
1. the HTTP Request file location should be configurable externally using properties file
2. the application should be deployable to 3 environments as listed below:
  a. test environment
  b. trial environment
  c. production environment
3. the application should use the frameworks provided below along with the purpose:
  a. LOGGING - java logging api
  b. TESTING - junit framework
  c. BUILD - maven
  d. VCS - git
  e. IDE - ANY
