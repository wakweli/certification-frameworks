# NFT Certification Framework

## Usage

Validates the authenticity, provenance, uniqueness, and ownership of NFTs and digital collections, enhancing trust and transparency in digital asset marketplaces.

## Framework ID

```
nft
```

## URI format

```
<chain>:<smart-contract-id>:<token-id>
<chain>:<smart-contract-id>
```

### Examples :

* `ethereum:0x0da65a5704b930ae3a5f0a563d13d0339b010c8f:1` for [Wakweli's Alpha 3.0 Pass NFT](https://opensea.io/assets/ethereum/0x0da65a5704b930ae3a5f0a563d13d0339b010c8f/1){:target="_blank"}
* `ethereum:0xbc4ca0eda7647a8ab7c2061c2e118a18a936f13d` for the [Bored Ape Yacht Club](https://opensea.io/collection/boredapeyachtclub){:target="_blank"} collection

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
