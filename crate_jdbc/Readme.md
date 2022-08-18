CrateDB JDBC connector. This requires the Postgres JDBC driver.


https://tableau.github.io/connector-plugin-sdk/docs/capabilities


connector-packager % python3 setup.py install


cp packaged-connector/crate_jdbc.taco /Users/gtraar/Documents/My\ Tableau\ Repository/Connectors/crate_jdbc.taco 
python3 -m connector_packager.package /Users/gtraar/Developer/tableau/crate-tableau-connector-jdbc/crate_jdbc    



Run Tableau
/Applications/Tableau\ Desktop\ 2022.2.app/Contents/MacOS/Tableau -DDisableVerifyConnectorPluginSignature=true