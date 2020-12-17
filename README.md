# url-shortener

## Get url from shortUrl
curl {Server IP} -XGET -d "shortUrl=https://shortUrl"
Please, check that it is 'shortUrl' not 'shorturl'.


## Create shortUrl from url
curl {Server IP} -XPOST -d "url=https://url"

### When duplicated request comes
When duplicated, it will return below.
{"message":"Shortened URL already registered"}