# Phone Guard privacy policy

Effective: October 29, 2026
Version: 1.0, for Phone Guard 1.0 (Android, package `com.phoneguard.app`)
Version française : [politique de confidentialité](politique-de-confidentialite.md)

## Who we are

Phone Guard is made by Jacques Dev, an individual developer in Quebec, Canada ("we", "us").

Person in charge of the protection of personal information (Quebec Law 25): Jacques Dev, jacques_dev@icloud.com.
Write to that address for any privacy question or request. We answer within 30 days.

## The short version

- Phone Guard checks your apps and files on your phone. Everything it reads, works out or stores stays on your phone. None of it is sent to us or to anyone else.
- Phone Guard has no internet access. It cannot send anything to us or to anyone else. Its rules and lists ship inside the app and update when the app updates through Google Play.
- We don’t sell data. We don’t show ads. Phone Guard contains no advertising, analytics or crash-reporting code.
- Phone Guard doesn’t share user data with anyone.
- Phone Guard has no accounts.

## 1. What Phone Guard reads, only on your phone

Phone Guard reads each item below only after you agree on a screen that explains it. None of it leaves your phone.

**Your apps** (after you agree on the "See your apps" screen)
- Every installed app’s name, version, who signed it, what it can access (its permissions), where it was installed from, and when it was installed and last updated.
- Each app’s install files, to look for code from ad networks and to work out a fingerprint of each file. This runs in a separate, locked-down part of Phone Guard with no access to your data. Phone Guard never runs code from other apps.
- Phone Guard does this when you open it, and once a day in the background to check new and updated apps.

**Usage** (only if you turn on Usage access)
- When you last opened each app, how long each app ran in the background, how much mobile and Wi-Fi data each app used and how much of it was in the background, and how much storage each app and its data take.

**Notification counts** (only if you turn on Notification access)
- For each notification: which app sent it, when it arrived, its type (for example "message" or "promotion") and how important the app marked it.
- Phone Guard never reads or keeps the title, the text, pictures or who a notification is from. It never dismisses, snoozes or taps your notifications.

**Your files** (only in folders you choose)
- Phone Guard looks only at folders you pick in Android’s folder picker, and files you pick in Downloads. Phone Guard asks the picker to show only storage on your phone, not cloud storage.
- For each file it reads the name, folder, size, type and date. For files of the same size, it also reads the content, to find identical copies. For installer files, it also reads the app name and version number inside the file.
- It looks only while the file screen is open. It doesn’t keep the list of files it found, except the files you tell it to keep and the files it moved to the trash (section 2).

## 2. What Phone Guard stores on your phone, and for how long

| What | Kept for |
|---|---|
| When you agreed to each explanation screen, and which version of it | Until you delete Phone Guard’s data or uninstall it |
| Your settings (daily check, notification counting) | Until you delete Phone Guard’s data or uninstall it |
| Results for each app (concerns found, reasons, unused or duplicate) | Replaced at every check |
| Results of the install-file check (ad networks found, file fingerprints) | While that app stays installed; removed at the next install-file check after it’s uninstalled |
| Notification counts | 14 days, then deleted. "Stop counting and delete counts" deletes them at once |
| The apps you chose to remove in a cleanup, and what happened to each | Until that cleanup is over and you close its summary |
| The folders you shared with Phone Guard | Until you tap Remove access in the Folders list |
| Files you told Phone Guard to keep (name, folder, size, date) | Until you change your mind or delete Phone Guard’s data |
| Files Phone Guard moved to Android’s trash (name and size) | Until you restore or delete them, or 35 days at most |

Phone Guard turns off Android backup and device-to-device transfer for all of its data, so none of it is copied to your Google account or to another phone.

## 3. What leaves your phone

Nothing. Phone Guard has no internet access. It cannot send anything to us or to anyone else.

Google Play handles app downloads and updates under Google’s own privacy policy.

## 4. Why Phone Guard asks for each permission

- **See all apps** (`QUERY_ALL_PACKAGES`): to check every installed app, including apps without an icon.
- **Usage access** (optional): for the usage information in section 1.
- **Notification access** (optional): for the notification counts in section 1.
- **Request to delete apps** (`REQUEST_DELETE_PACKAGES`): to open Android’s own uninstall prompt for apps you choose. Android asks you to confirm every removal.
- **Run at startup** (`RECEIVE_BOOT_COMPLETED`) and **view network status** (`ACCESS_NETWORK_STATE`): added by Android’s background-task library, so the daily check is still scheduled after a restart. Viewing network status can’t send anything.

Phone Guard reaches your files only through Android’s own folder and file pickers. It has no permission to read all your photos, videos or files.

## 5. Defaults, and how to turn each part off

| Part | Default | How to turn it off |
|---|---|---|
| App check when you open Phone Guard | On after you agree | Uninstall the app |
| Daily background check | On after you agree | Phone Guard Settings > Daily check |
| Usage access | Off until you turn it on | Android Settings > Usage access > Phone Guard |
| Notification counting | Off until you turn it on | Phone Guard Settings > Stop counting and delete counts. To also take back the access: Android Settings > Notification access > Phone Guard |
| Folder access | Off until you pick a folder | Remove access in the Folders list on the results screen |

## 6. Deleting your data

- **Delete all data:** in Phone Guard, open Settings > Delete all Phone Guard data. This uses Android’s own "Clear storage". It deletes everything in section 2, removes the folder access you gave, turns off notification access, cancels the daily check and closes Phone Guard.
- **Uninstall:** uninstalling Phone Guard deletes everything it stored.
- Two things stay, because they belong to Android, not to Phone Guard:
  - Files you moved to the trash stay in Android’s trash until you restore them or Android deletes them, in about 30 days.
  - Usage access stays on until you turn it off in Android settings. Phone Guard doesn’t use it again until you agree again.

We hold no data about you on any server, so there is nothing to delete on our side. The only exception is an email you send us (section 7).

## 7. Our website and email

The Phone Guard app has no servers. Our website, where this policy is published, is hosted on GitHub Pages. It uses no cookies or analytics. GitHub keeps its own visitor logs under the GitHub privacy statement.

If you email us, we use your email only to answer you, and delete it within 12 months.

## 8. No sale, no ads, no sharing

We don’t sell data. We don’t show ads. Phone Guard contains no advertising, analytics or crash-reporting code, and doesn’t use the advertising ID. We never sell, share or use your app list for advertising, analytics or any other purpose, because we never receive it.

Google Play’s Data safety section for Phone Guard says that it collects no user data and shares no user data. That matches this policy: the app sends nothing off your phone.

The list of ad networks Phone Guard looks for comes partly from the Exodus Privacy tracker database (ODbL licence). It ships inside the app; Phone Guard doesn’t contact Exodus Privacy.

## 9. Your rights

Depending on where you live (for example Quebec, the rest of Canada, the EU or the UK), you can ask us to access, correct or delete the personal information we hold about you, or object to how we use it. The app sends us nothing, so the only personal information we may hold about you is an email you sent us. Write to jacques_dev@icloud.com. You can also complain to a data protection authority, such as the Commission d’accès à l’information du Québec.

EU and UK: if you email us, we use your email on the basis of our legitimate interest in answering you (Article 6(1)(f) GDPR).

We don’t sell or share personal information as US state privacy laws define those terms.

## 10. Children

Phone Guard is not directed at children. It is meant for people aged 13 and over. Phone Guard collects no personal information from anyone.

## 11. Changes

If we change this policy, we update the date at the top. If a future version of Phone Guard would send anything off your phone, we update this policy and Google Play’s Data safety section before that version ships, and the app explains it and asks you first.

## 12. Contact

Jacques Dev, Quebec, Canada. jacques_dev@icloud.com.
