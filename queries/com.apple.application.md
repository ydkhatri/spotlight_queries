iOS Apps
```SQL
SELECT _kMDItemExternalID, kMDItemDisplayName, kMDItemContentCreationDate, 
kMDItemVendorName, kMDItemAlternateNames, _kMDItemInterestingDate, kMDItemAppStoreCategory,
_kMDItemRankingLaunchCountLast30Days, _kMDItemApplicationLastLaunchedDate,
_kMDItemRankingLaunchCountLast7Days, _kMDItemRankingLaunchCountDay, _kMDItemRankingLaunchCountOld
FROM "Spotlight-store" -- replace with your Tablename
WHERE _kMDItemBundleID LIKE "com.apple.application"

```
