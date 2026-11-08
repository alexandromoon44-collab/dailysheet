# Daily Sheet · ទំនិញប្រចាំថ្ងៃ

A simple web page for recording 5 goods every day. Enter the weight (kg) and the price per kg in Khmer riel (៛), and the page calculates the totals. It works on phones, tablets and computers.

**Live site:** https://alexandromoon44-collab.github.io/dailysheet/

## What it does

- 5 rows for 5 goods (default: ត្រសក់, ត្រឡាច, ម្រះ, សណ្ដែកគួ, ត្រប់)
- Row total = kg × price per kg, plus a grand total in riel
- Saves each day and keeps a History of all saved days
- Shows the change in total compared with the previous saved day
- Opens on today's real date every time
- Saves a report as a picture (PNG) for your Gallery
- Light and dark theme

## How to use

1. Open the link in **Safari** (iPhone) or **Chrome** (Android). Do not use the browser inside Telegram or other apps.
2. The page opens on **today's date**.
3. For each good, type the **weight (kg)** and the **price per kg (៛)**. The row total and the grand total update as you type.
4. Press **Save · រក្សាទុក**. The day is saved and stays on the same date.
5. Press **Save report as picture** to make a picture of the day's report, then press **Save picture**.
   - iPhone: choose **Save Image** in the share sheet.
   - Android and computers: the picture goes to your Downloads folder, or a share sheet opens.
   - If it doesn't work, press and hold the picture and choose Save image.

## Other things you can do

- **Rename a good:** type a new name in the name box, then press Save.
- **Change the date:** use the date box or the ◀ ▶ buttons. A day you skipped stays empty until you fill it in.
- **Prices carry over:** a new day starts with the prices from your last saved day, so you only change the ones that moved.
- **Edit an old day:** tap its date in the History table, change the numbers, and press Save.
- **Delete a day:** press ✕ in the History table.
- **Theme:** press the ◐ Theme button to switch between light and dark.

## Add it to your home screen

- **iPhone (Safari):** tap Share, then **Add to Home Screen**.
- **Android (Chrome):** tap the ⋮ menu, then **Add to Home screen**.

On some iPhones the home screen icon can open with its own separate storage and look empty. If that happens, your days are still in Safari. Pick one way to open it and always use that one.

## Where is my data stored?

Your data is stored **only in your phone's browser**. It is not in a database and not on GitHub.

- Other phones and computers will not see it.
- Each link has separate data. `localhost`, an IP address and the GitHub link do not share days.
- Clearing browser data, or using a private window, can erase it.

**Back it up:** save the report picture at the end of each day.

## Language

- You can type goods in **Khmer or English**, and Khmer text displays correctly.
- The page is **partly Khmer**. The main labels are shown in both English and Khmer, but some text is English only (for example the History table, the top cards and the messages).
- Khmer text uses your device's own fonts, so it looks slightly different on each phone.

## Troubleshooting

| Problem | Fix |
| --- | --- |
| Save picture does nothing | Open the link in Safari or Chrome, not inside Telegram |
| My days are gone | Check you opened the same link as before |
| The page looks old after an update | Wait a minute, close the tab, and open the link again |
| Khmer letters look wrong | Update your phone's system fonts or browser |

## Update the site (GitHub Pages)

Run these in the project folder:

```bash
git add index.html
git commit -m "Update"
git push
```

The site updates in about a minute.

## Files

- `index.html`: the whole app (HTML, CSS and JavaScript in one file)
- `README.md`: this guide
