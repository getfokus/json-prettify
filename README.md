json-prettify
========

A tool that output json in pretty way in CLI

## Usage

Use tool via command line:

```
./command-with-json-output | json-prettify
```

Example output is Pretty formated JSON:

```
{
    "code": "success",
    "response": [
        {
            "autoTaggingEnabled": false,
            "canManageClients": false,
            "companyName": "",
            "conversionTrackingSettings": {
                "conversionOptimizerMode": "ONE_PER_CLICK"
            },
            "currencyCode": "PLN",
            "customerId": "12345678",
            "dateTimeZone": "Europe/Warsaw",
            "descriptiveName": "",
            "testAccount": false,
            "trackingUrlTemplate": null
        }
    ]
}
```

## Installation

#### Installation via `curl`

```
curl https://raw.githubusercontent.com/getfokus/json-prettify/master/json-prettify.sh > json-prettify
mv json-prettify /usr/local/bin/json-prettify
chmod +x /usr/local/bin/json-prettify
```

#### Installation via `wget`

```
wget https://raw.githubusercontent.com/getfokus/json-prettify/master/json-prettify.sh -O json-prettify
mv json-prettify /usr/local/bin/json-prettify
chmod +x /usr/local/bin/json-prettify
```

### Requiremts

* Python
