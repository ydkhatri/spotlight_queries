iOS Mail
```SQL
SELECT kMDItemContentType, _kMDItemExternalID, _kMDItemStorageSize, kMDItemKind, kMDItemDisplayName,kMDItemPrimaryRecipientEmailAddresses, kMDItemAccountType, 
kMDItemAuthorEmailAddresses, kMDItemAuthors, kMDItemAccountHandles, kMDItemContentCreationDate, 
kMDItemSubject, com_apple_mail_dateReceived, _kMDItemSnippet, kMDItemMailboxes, kMDItemEmailConversationID, 
com_apple_mail_messageID, _kMDItemInterestingDate, kMDItemApplicationName, 
kMDItemTitle, _kMDItemUserActivityRequiredString, _kMDItemRankingLaunchDates, _kMDItemUserActivityType, 
kMDItemUsedDates, kMDItemLastUsedDate, kMDItemLastUsedDate_Ranking
FROM "Spotlight-NSFileProtectionComplete-store" -- change to your table name
WHERE _kMDItemBundleId="com.apple.mobilemail"

```
