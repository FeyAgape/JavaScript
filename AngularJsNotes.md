Using .find
```
let defaultSite = $ctrl.siteAddresses.find((item) =>
item.SiteAddressTypes.some((type) => type.Name === 'Main'));

$ctrl.setSite(defaultSite);
```

Using .filter
```
let defaultSite = $ctrl.siteAddresses.filter(item =>
item.SiteAddressTypes.some((type) => type.Name === 'Main'));

$ctrl.setSite(defaultSite[0]);
```        
