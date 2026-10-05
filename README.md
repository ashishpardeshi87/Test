# DarkGuard APEX — live talk-over script (about 3:30)

Short lines. Read the **SAY** part out loud while you do the **DO** part.

## Before you press record (2 minutes)

1. Open the 5 PowerShell windows. Check **5 STATUS** says all UP and Tor 100%.
2. Open http://127.0.0.1:5500 and log in.
3. Go to **Attribution** → **Stored persona corpus** → press **Random** → run it.
   Repeat until the result says **PROBABLE**. Keep that pair selected.
4. Close every other tab and app. Start OBS recording.

---

## 1. Terminals — 15 sec

**DO:** Show the 5 PowerShell windows. Stop on **5 STATUS**.

**SAY:**
> This is DarkGuard APEX, running fully on our own machine.
> Four services: Tor, the scraper, the attribution engine, and the dashboard.
> Tor is connected — one hundred percent.

## 2. Problem — 15 sec

**DO:** Switch to the browser. Click **APEX Console** in the left menu.

**SAY:**
> Our problem statement is SIH 26151 from NTRO — finding who is behind a dark web identity.
> Criminals change their names, keys and wallets.
> But their habits and their servers stay the same. That is what we track.

## 3. Pipeline — 25 sec

**DO:** On the APEX Console, click the stage boxes one by one:
**Collect → Safety filter → Store → Confidence engine.** Pause one second on each.

**SAY:**
> Every request goes through six steps.
> First we collect, through our own Tor connection.
> Then a safety filter — it blocks illegal content *before* we even open the page.
> Everything we collect is hashed at capture, so nobody can tamper with it later.
> Then the confidence engine weighs all the evidence and tells us how sure it is.

## 4. Live network — 15 sec

**DO:** Click **Network Status** in the left menu. Point at the Tor exit IP, then the two charts.

**SAY:**
> This is live. This is our real Tor exit IP.
> We have about seventy-five dark web marketplaces, collected from public directories —
> dark.fail, tor.taxi and onion.live.

## 5. Scan — 15 sec *(skip if it loads slowly)*

**DO:** Click **New Scan** → type a test keyword → start. Show the canvas for a few seconds.

**SAY:**
> A scan visits each marketplace and searches it.
> You can see each one — online, dead, or blocked — as it happens.

## 6. Attribution — 25 sec

**DO:** Click **Attribution**. Your PROBABLE pair is already selected. Press **Run**.
Let the evidence bar animate.

**SAY:**
> Now the main part — attribution. Are these two dark web sellers the same person?
> This is our test data, where we know the right answer.
> Each signal pushes this marker. Right means same person. Left means different people.
> If a signal finds nothing, it counts as zero. We don't hide it.

## 7. Result — 20 sec

**DO:** Scroll to the **Verdict** panel. Point at the tier (PROBABLE) and the band.
Then point at the coloured signal chips.

**SAY:**
> The answer is not a guess. It's "probable" — likely linked — with the exact reasons.
> Behaviour alone can never give us the top level.
> For that we need a hard proof, like a shared key or a shared server.

## 8. Identifiers + email trace — 20 sec

**DO:** Click the **Identifiers** tab. Then click the **Email trace** tab.

**SAY:**
> Here are their keys, wallets and contact emails, side by side.
> Even when the email changes, we check the pattern — same name, same provider, number going up.
> The email trace finds every account with that same pattern,
> and shows how many are really the same person.

## 9. Dossier — 15 sec

**DO:** Click the **Actor dossier** tab. Move the mouse down the rows.

**SAY:**
> This is everything the problem statement asked us to store:
> confidence, category, last scan date, source, and linked suspects.

## 10. Export — 15 sec

**DO:** Click **CSV**, then **JSON**, then **Report**. Open the PDF for two seconds.

**SAY:**
> We can export it as CSV, JSON, or a full report —
> built to intelligence and forensic standards, with every limit written inside.

## 11. Limits — 15 sec

**DO:** Click **APEX Console**. Scroll down to **What this system cannot do**.

**SAY:**
> We are honest about our limits.
> A well-hidden server can't be traced — research says only about five percent can.
> We can't follow Monero.
> Our system gives a lead for an officer to check. Never a final verdict.

## 12. End — 10 sec

**DO:** Scroll back to the top of APEX Console. Stop recording.

**SAY:**
> DarkGuard APEX — collect, connect, and prove, in one self-hosted system.
> Thank you.

---

## If something goes wrong

- A page is slow → say "this takes a moment" and click the next item.
- The result is not PROBABLE → say "likely linked" only if it shows PROBABLE. If it shows INSUFFICIENT, say:
  "Here it says the evidence is not enough — so it refuses to guess."
- Never say: "real-time", "it finds the real person", "AI-powered".
