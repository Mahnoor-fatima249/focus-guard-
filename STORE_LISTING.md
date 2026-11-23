# Focus Guard: store submission notes

## Upload these files
| Store | File | Where |
|---|---|---|
| Chrome Web Store | focus-guard-chrome-edge.zip | chrome.google.com/webstore/devconsole ($5 one-time fee) |
| Microsoft Edge Add-ons | focus-guard-chrome-edge.zip (same file) | partner.microsoft.com/dashboard/microsoftedge (free) |
| Firefox (AMO) | focus-guard-firefox.zip | addons.mozilla.org/developers (free) |

## Name
Focus Guard: Distraction Blocker

## Short description (under 132 characters)
Block YouTube, Instagram and Facebook while you study or work. Simple timer, Pomodoro, schedules and a daily report.

## Full description
Most of us don't lack discipline. We lack friction. One quick look at YouTube turns into an hour, and the work you sat down to do is still waiting.

Focus Guard adds that friction back. Start a session and the sites that pull you away stay closed until the timer ends. When you're done, they open again. No account, no complicated setup.

What you can do
- Block the sites that cost you time. YouTube, Facebook, Instagram, TikTok, X and Reddit are ready to go, and you can add any other site.
- Focus with a simple timer, or use Pomodoro rounds with short and long breaks. You choose the lengths.
- Let schedules do the starting for you, for example weekdays from 9am to 1pm.
- Keep one useful page open, like a lecture playlist, while the rest of the site stays blocked.
- Write down what you're working on, and see it each time you're tempted to drift.
- Set a daily goal and build a streak.
- Check your daily report to see how long you focused, how many distractions were stopped and roughly how much time you saved.

Made for students and freelancers who want their time back.

Private by design
Everything stays on your device. Focus Guard doesn't collect your data, read the pages you visit or send anything anywhere. There are no ads and no tracking. Remove the extension and your data goes with it.

## Single purpose (Chrome/Edge)
Block user-selected distracting websites during timed focus sessions and report focus time.

## Permission justifications
- storage: saves your blocklist, schedules, settings and focus statistics on your device.
- alarms: ends focus sessions on time, starts schedules, and sends the daily summary.
- notifications: tells you when a session, break or schedule starts or ends.
- declarativeNetRequest: redirects blocked sites to the "Stay focused" page during a session.
- Host access (all sites): needed so the blocklist can match any site the user chooses to block. Page contents are never read.

## Privacy policy (paste into a public page, then link it)
Focus Guard does not collect, transmit, sell or share any personal data. Your blocklist, schedules, settings and focus statistics are stored locally in your browser using extension storage and never leave your device. The extension does not read page contents, track browsing history, use analytics or load remote code. Removing the extension deletes all stored data.

## Before you publish
- Uninstall feedback: open background.js, find FEEDBACK_URL near the top and paste a public form link (for example a Google Form). Then run ./build.sh and upload the new zips. Leave it empty to skip.
- Support contact: add your support email or website in each store's listing form.

## Browser notes
- Edge accepts the Chrome package unchanged.
- Firefox: the extension ID is focus-guard@focusguard.app. Change it in manifest.firefox.json if you want your own domain-style ID. Firefox may ask the user to allow access to all sites, so the popup shows an "Allow site access" button if it is missing.
- Firefox review: choose "No data collection" if asked. No build step or minification is used, so no source upload is needed.
- Screenshots: take 1280x800 screenshots of the popup, the blocked page, the report and settings.
- To rebuild the packages after any change, run ./build.sh
