# SalesForceChallenge

## Implement a Function to get all Sites of an Url (Not is necessary implement GetChildrens)

` 
List<String> GetSites (String startUrl)
`
<br />
`
Use Get Childrens of this URL
`
<br />
`
List<String> GetChildrens (String url)
`
<br />
## Example
- Start url: wiki.com
- wiki.com -> GetChildrens() -> wiki.com/a
- wiki.com/a -> GetChildrens() ->wiki.com/b
- wiki.com/b -> GetChildrens() -> [wiki.com/c,wiki.com/d]
- wiki.com/d -> GetChildrens() ->wiki.com
- With Start Url wiki.com you should receive with GetSites() an array like [wiki.com , wiki.com/a , wiki.com/b , wiki.com/c , wiki.com/d]
