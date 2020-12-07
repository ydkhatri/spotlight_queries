iOS Safari
```SQL
SELECT _kMDItemDomainIdentifier, kMDItemTitle, kMDItemPhysicalSize, _kMDItemInterestingDate, 
kMDItemContentURL, kMDItemDescription, kMDItemUsedDates, kMDItemLastUsedDate,
kMDItemUseCount, 
--_kMDItemContentIndexVersion, -- ios 14 only?
pageVisitCount, kMDItemTextContentDataSource
FROM "Spotlight-NSFileProtectionCompleteUntilFirstUserAuthentication-store" -- replace with your tablename
WHERE _kMDItemBundleId="com.apple.mobilesafari"
```
