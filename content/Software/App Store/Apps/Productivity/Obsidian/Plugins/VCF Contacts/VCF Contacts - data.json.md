---
cssclasses:
  - source-code-cascadia-mono
tags:
  - documentation/data-json
---
{
&nbsp;&nbsp;"[[VCF Contacts - Settings#Contacts folder location|contactsFolder]]": `"<FOLDER PATH>"`,
&nbsp;&nbsp;"[[VCF Contacts - Settings#Default hashtags|defaultHashtag]]": `"<HASHTAG NAME>"`,
&nbsp;&nbsp;"processors": {
&nbsp;&nbsp;&nbsp;&nbsp;"[[VCF Contacts - Settings#UidProcessor|UidProcessor]]": `true OR false`,
	&nbsp;&nbsp;&nbsp;&nbsp;"[[VCF Contacts - Settings#SyncUnknownProcessor|SyncUnknownProcessor]]": `true OR false`
&nbsp;&nbsp;},
&nbsp;&nbsp;"[[VCF Contacts - Settings#Sync method|syncSelected]]": `"None" OR "CardDAV"`,
&nbsp;&nbsp;"[[VCF Contacts - Settings#Synchronization|syncEnabled]]": `true OR false`,
&nbsp;&nbsp;"groupInsights": true,
&nbsp;&nbsp;"CardDAV": {
&nbsp;&nbsp;&nbsp;&nbsp;"[[VCF Contacts - Settings#Address book URL|addressBookUrl]]": `"<URL>"`,
&nbsp;&nbsp;&nbsp;&nbsp;"syncInterval": 900,
&nbsp;&nbsp;&nbsp;&nbsp;"authKey": "",
&nbsp;&nbsp;&nbsp;&nbsp;"authType": "apikey"
&nbsp;&nbsp;}
}