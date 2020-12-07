```SQL
SELECT _kMDItemExternalID, kMDItemContentCreationDate, kMDItemSubject, com_apple_mail_dateLastViewed,
com_apple_mail_read, kMDItemUseCount, 
_kMDItemSnippet, kMDItemAuthorEmailAddresses, kMDItemAuthors, kMDItemPrimaryRecipientEmailAddresses
-- ,_kmdItemLaunchString, _kMDItemShortcutLastUsedDate -- may not be present always!
FROM "Spotlight-store.db" -- Change db name here to yours
WHERE kMDItemKind LIKE "email message"

```
