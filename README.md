# LIFEPLAY — working prototype

LIFEPLAY is a mobile-first prototype for a student project. It includes:
- My Life: daily tasks and the goal of the day.
- Food Life: food stock, expiry dates and meal ideas.
- IT Play: computer science quiz, explanations and XP points.
- Mood Play: optional mood journal and break ideas.
- LIFEPLAY CORE: profile, levels, badges, statistics, history, export/import and reset.

## Running the app
### Simplest method
Open `index.html` in a recent browser. The main features work locally. Some offline installation features (PWA) need a local server or HTTPS.

### Recommended local server
If Python is installed, open a terminal in this folder and run:
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

To test on a phone, the computer and the phone must be on the same Wi-Fi network and the server must be reachable from the phone. For a real PWA installation, use HTTPS on a hosting service or a secure test environment.

## Data and limitations
- Data is saved in the browser's `localStorage`, on the device.
- There is no online account, no multi-device sync, no server and no remote database.
- The prototype budget can be zero with free tools. A domain, hosting or professional development may cost more.
- Meal ideas are simple and do not replace nutritional advice. Date reminders are only an aid: always check the condition and labeling of food.
- Mood tracking is a personal well-being tool, not a medical diagnosis.

## Possible team split
1. Food Life: food data, dates and meal ideas.
2. My Life: tasks, goals and habits.
3. IT Play: quiz and educational content.
4. Mood Play: mood, break activities and user experience.
5. LIFEPLAY Core: integration, testing, documentation and presentation.

Each member should test the features of the other modules. The prototype is a demonstration base; before any public release, plan for user testing, a privacy policy, security testing and a real backup strategy.

## Installing on a phone
To install LIFEPLAY as a PWA, the files must be published at an HTTPS address. Simply opening `index.html` from the phone's storage is not enough to enable all PWA features. The manifest includes 192×192 and 512×512 icons.

After publishing over HTTPS:
- **Android / Chrome**: open the LIFEPLAY address, tap the ⋮ menu, then "Install app" or "Add to Home screen".
- **iPhone / Safari**: open the address, tap Share, then "Add to Home Screen".

Labels may vary depending on the browser and the phone.
