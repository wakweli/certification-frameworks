# Social Media Certification Framework

## Usage

Certifies the authenticity and legitimacy of profiles on X (formerly Twitter) or Bluesky, protecting users against impersonation and ensuring trustworthy communication.

## Framework ID

```
social-media
```

## URI format

```
<social-platform>:<handle>
```

### Examples :

* `x:wakwelichain` for [https://x.com/wakwelichain](https://x.com/wakwelichain){:target="_blank"}
* `bluesky:wakweli.com` for [https://bsky.app/profile/wakweli.com](https://bsky.app/profile/wakweli.com){:target="_blank"}

## Expected data parameters (optional)

* `data`: Specific data for social-media profiles
    * `type`: Type of social-media profile
        * `legitimate`
        * `fan-page`
        * `fake`
* `description`: Free text describing the request 
* `resources[]`: add extra ressources to the request
    * `type`: Resource's mime-type
    * `url`: IPFS URL of the resource
    * `description`: Free text describing the ressource 

``` json
{
    "data": {                        // Specific data for social-media profiles
        "type": "type",              // Type of social-media profile
    },
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
