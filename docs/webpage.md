# Webpage Certification Framework

## Usage

Provides verification of authenticity, content integrity, security compliance, and legitimate ownership for websites, preventing fraud, phishing, and misinformation online.

## Framework ID

```
webpage
```

## URI format

```
url:<canonical-url>
```

### Examples :

* `url:wakweli.com` for [https://wakweli.com/](https://wakweli.com/){:target="_blank"}

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
