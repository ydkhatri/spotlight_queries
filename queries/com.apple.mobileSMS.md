iOS MobileSMS App (Tested iOS 13)

```SQL
SELECT _kMDItemExternalID, kMDItemPrimaryRecipientEmailAddresses, kMDItemContentCreationDate, 
kMDItemPhysicalSize, _kMDItemInterestingDate, kMDItemAuthorAddresses, _kMDItemDomainIdentifier, 
_kMDItemSnippet, kMDItemAuthors, com_apple_mobilesms_indexType, kMDItemRecipientAddresses, 
kMDItemAccountHandles, com_apple_mobilesms_chatStyle, kMDItemAccountIdentifier, 
kMDItemUsedDates, kMDItemLastUsedDate, kMDItemContentURL, kMDItemFilename, 
kMDItemRelatedUniqueIdentifier, kMDItemRecipients, kMDItemURL, com_apple_mobilesms_lpPluginPaths, 
com_apple_mobilesms_suggested_contact_photo, com_apple_mobilesms_lpDescription, 
com_apple_mobilesms_suggested_contact_name, kMDItemLatitude, kMDItemLongitude, 
kMDItemOwnerIdentifier, kMDItemAuthorEmailAddresses 
FROM "Spotlight-NSFileProtectionCompleteUntilFirstUserAuthentication-store" -- change to your tablename
WHERE _kMDItemBundleId="com.apple.MobileSMS"

```
