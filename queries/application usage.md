Application usage for macOS DATA volume's spotlight database
```SQL
SELECT kMDItemDisplayName, _kMDItemFileName, kMDItemUseCount, kMDItemUsedDates, kMDItemLastUsedDate  
FROM "Spotlight-1-store"
WHERE kMDItemKind LIKE "Application" and kMDItemUseCount not like ""
ORDER BY kMDItemUseCount DESC

```

Application usage for macOS SYSTEM volume's spotlight database
```SQL
SELECT kMDItemDisplayName, _kMDItemFileName, kMDItemUseCount, kMDItemUsedDates, kMDItemLastUsedDate  
FROM "Spotlight-BootVolume_1-store"
WHERE kMDItemKind LIKE "Application" and kMDItemUseCount not like ""
ORDER BY kMDItemUseCount DESC
```
