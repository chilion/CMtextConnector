# CMtextConnector
A connector to the CM sms service

# Usage
	## composer
    "CJSDevelopment/CMtextConnector" : "dev-master"
    
    ## app.php
    ### ServiceProvider
    'CJSDevelopment\CMtextConnectorServiceProvider'

    ### Facade
    'SMS' => 'CJSDevelopment\CMtextConnector',

    ## initialize
    SMS::sendMessage("0031600000000", "Test with Connector")

# Config
	Don't forget to fill in the right company name and product token
