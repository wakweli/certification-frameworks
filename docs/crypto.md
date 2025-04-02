# Cryptocurrency Certification Framework

## Usage

Certifies authenticity, ownership, and compliance of cryptocurrency assets, ensuring secure and trustworthy exchanges.

## Framework ID

```
crypto
```

## URI format

```
<chain>:<smart-contract-id>
```

### Examples :

* `
ethereum:0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48` for [USDC](https://etherscan.io/token/0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48){:target="_blank"}

## Expected data parameters (optional)

* `description`: Free text describing the request 
* `resources[]`: add extra ressources to the request
    * `type`: Resource's mime-type
    * `url`: IPFS URL of the resource
    * `description`: Free text describing the ressource 

``` json
{
    "image": "",                     // IPFS url of the image
    "description": "<description>",  // Free text describing the request 
    "resources": [
        {
        "type": "",                  // Resource's mime-type
        "url": "",                   // IPFS URL of the resource
        "description": ""            // Free text describing the ressource 
        }
    ]
}
```
