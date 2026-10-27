# CCA 3: Think Aloud Usability Testing of 99acres vs. our Redesign

We asked five people to do real property-hunting tasks on the live 99acres website and then on our redesigned 99acres prototype, speaking their thoughts out loud the whole time. This folder holds the raw recordings, the transcripts, and what we took away from them.

## Group Members

| Name | PRN |
| --- | --- |
| Amey Nitin Tarmale | 1032232006 |
| Vedant Prashant Kaskar | 1032231979 |
| Bilal Shahid Mohammad | 1032233984 |

## Prototype

- **Figma prototype:** https://www.figma.com/design/8FgFJA8IVJoePg6EDZIXMB/Untitled
- **Live version (deployed on Vercel):** https://99acres-replica.vercel.app/

## Folder Structure

```
CCA 3/
├── README.md                this file: members, prototype link, final conclusion
├── Conclusion_Report.docx   the final conclusion as a formatted report
├── audio_files/             raw Think Aloud recordings (5 participants, 8 files; 3 sessions were recorded in two parts)
└── transcripts/             speech-to-text transcripts, as .docx and as plain .txt
```

| Participant | Audio | Transcript |
| --- | --- | --- |
| Reuben Sam | `Reuben Sam Interview.m4a` | `Interview 1 Reuben` |
| Riya Gupta | `Riya Gupta Interview.m4a`, `Riya Gupta Interview part 2.m4a` | `Interview 2 Riya` |
| Anushka Ambadkar | `Ansuhka Ambadkar Interview part 1.m4a`, `Anushka Ambadkar Interview part 2.m4a` | `Interview 3 Ansuhka` |
| Vishwajit Chavan | `VIshwajit Chavan Interview.m4a` | `Interview 4 Vishwajit` |
| Naman Chachan | `Naman chachan Interview part1.m4a`, `Naman Chachan Interview part 2.m4a` | `Interview 5 Naman` |

## How We Ran the Sessions

Each participant used the original 99acres site first and our redesign second. Most were given a concrete, personal goal rather than a checklist: find a 2BHK or 3BHK in Bengaluru, compare a few options, and get in touch with the actual owner without getting spammed. They talked through what they were seeing and feeling, and four of the five gave each site a score out of 10 at the end.

Alongside the interviews, we also draw on our earlier lab work on the same redesign:

- **Experiment 5 (Heuristic Evaluation):** three evaluators from another group scored the prototype against 15 usability principles. Average severity was **34.7 / 75** (lower is better).
- **Experiment 6 (Microsoft Clarity):** session recordings and heatmaps from the deployed prototype's search page.

---

## Final Conclusion

The full report is also available as a formatted Word document: [Conclusion_Report.docx](Conclusion_Report.docx).

### The short version

People liked our redesign a lot more than the real 99acres site, and they were specific about why. Scores for 99acres ranged from **1 to 3 out of 10**; our prototype got **7, 7 and 8** from the three who scored it. But almost every participant also ran into things in our prototype that looked like they worked and didn't. The honest summary is the one Riya gave: right now it's *"a bit of a showroom. You can walk around, but you can't buy anything yet."*

### What frustrated people on 99acres

The same problems came up again and again, mostly without us prompting for them:

- **Too much in the way before they could even search.** Pop-ups, banners, loan offers and a "confirm you're human" check, all before seeing a single listing. Naman said that at 9 p.m. it *"feels like one more hoop."*
- **Menus that repeat themselves.** Buyers, Tenants, Owners and Dealers all opened near-identical lists of insights, articles and tools. Riya: *"I came to look at flats, not solve a menu."* Several insights links led to dead pages, which Anushka said made her *"nervous handing it my number."*
- **No way to compare.** Nobody found a compare feature. Riya, Anushka and Vishwajit all ended up switching between tabs and relying on memory or a notes app. Vishwajit forgot which flat had parking and had to go back.
- **Not knowing who you're talking to, or what happens next.** "View number" needed a login and an OTP, with no explanation of what that would lead to. Naman stopped right there and refused to give his number, because he couldn't tell whether the listing was from an owner or an agent and he had read about people getting flooded with sales calls.
- **No sign of freshness.** Anushka and Naman both scrolled through a listing looking for when it was posted or updated and couldn't find it.
- **Hard on the eyes.** Small text, no dark mode, no way to make text bigger. This came up with Riya, Anushka and Vishwajit.

To be fair to 99acres, Riya's summary was *"it has everything, it just makes you work for it,"* and Reuben pointed out that it has more search filters and flexibility than our prototype.

### What worked in our redesign

- **A calm first screen.** No pop-ups, one search bar, a short and clear menu (Buy, Rent, Saved, My Activity, List property). Everyone noticed the difference straight away.
- **The Compare page was the clear winner.** Every participant who tried it valued it. Seeing price per sq ft, metro distance, parking, availability and owner-or-agent side by side let Vishwajit pick a flat in *"a minute or two."* Anushka: *"99 acres was two tabs and a notes app. This is the entire one screen."*
- **Trust signals, placed where people need them.** "Updated 2 hours ago", "re-verified on", the owner's name, "usually replies in 1 hour", and especially the privacy note saying calls go through a private relay. That last one directly answered the biggest fear Riya, Anushka and Naman all raised. Naman: *"I knew who the owner was, I knew what would happen with my number and I knew what would come next."*
- **Telling people what happens after they make contact.** After 99acres "went silent", seeing "request sent, you'll get an SMS/email, track it in My Activity" felt like a relief. Riya: *"On 99 acres, I got silence. Here I get a plan."*

### Where our redesign fell short

This is the part we most need to own. The participants' complaints line up almost exactly with what the heuristic evaluators found in Experiment 5:

- **Controls that look clickable but do nothing.** Filter chips, "More filters" and sort didn't change anything. Searching brought back the same three homes, and Rent showed the same results as Buy. Schedule Visit did nothing.
- **Every card opens the same property.** No matter which listing you click, you get Cedar House. Naman noticed this while trying to open a different flat.
- **Navigation going to the wrong place.** Saved opened a property page, My Activity opened Compare, and List property went nowhere.
- **Our data contradicts itself.** This one hurts the most, because trust is the whole idea behind the design. Anushka caught the owner's name being *Rhea Menon* on one page and *Rakesh K.* on another, "updated 2 hours ago" vs "2 days ago", a reply time of 24 hours vs 1 hour, and home counts of 4,280 vs 184 vs 42 with only 3 actually shown. As she put it: *"if a verified site contradicts itself it isn't really verified."*
- **Mobile is broken.** Below roughly 700 px the menu disappears and there's no hamburger menu.
- **Small inconsistencies.** The contact page has a different dark header and logo, and the Call button changes colour between pages.

Our Clarity data supports this. On the search page, **33% of sessions had dead clicks** and **33% had quick backs**. There were no rage clicks and the site loaded fast with no JavaScript errors, so the problem is broken interactions, not performance.

### What we'd fix, in order

1. **Make the data consistent.** Use one source for owner name, update time, reply time and listing counts across every page. This is small to fix and has the biggest effect on trust.
2. **Make the core flow work end to end:** search → filter → open the *right* listing → save → contact or schedule a visit. Hide anything that isn't wired up yet rather than leaving it as a dead button.
3. **Fix navigation targets** for Saved, My Activity, Rent and List property, and add a mobile menu.
4. **Keep and build on what people loved:** the Compare page, the freshness and verification labels, the privacy relay note, and the "what happens next" screen after contact.
5. **Add back some of the search depth Reuben missed**, such as exact budget and area ranges and a locality picker, without bringing back the clutter.

### Honest limitations

- **Five participants is a small sample.** It's enough to spot the big recurring problems, which is what Think Aloud is good for, but not enough to call these scores statistically meaningful.
- **All participants are fellow students** of similar age and tech comfort. Real home buyers, older users, and people buying for the first time might react differently.
- **The order was always the same**, 99acres first and then our redesign. By the second site participants already knew what to look for, which probably helped our prototype.
- **Some participants were partly guided.** Several sessions followed a similar task script, and a couple of transcripts read more like a planned walkthrough than spontaneous thinking aloud. Reuben's session in particular describes the steps without much reaction, and he didn't give a score.
- **The feedback doesn't fully agree.** In his session Vishwajit said the filters were "working perfectly fine" and mentioned dark mode, while the other participants and the heuristic evaluators (Vishwajit among them) found the filters inactive. We've gone with the majority finding, but we're flagging the disagreement rather than hiding it.
- **Our Clarity sample is tiny:** 3 sessions from 2 unique users on the search page. It agrees with the interviews, but on its own it isn't strong evidence.

### Final word

The redesign got the *idea* right. When people can see who they're dealing with, what's been verified, and what happens to their phone number, they relax and actually make decisions. Vishwajit said he felt like he *"made a decision"* instead of guessing. What we haven't done yet is deliver on that idea consistently. A trust-first design can't afford contradictory data or buttons that don't work, because those are exactly the details that make users suspicious. Fixing them is our next step, and it should be a reasonably quick one.
