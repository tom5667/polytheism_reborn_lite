# Polytheism Reborn — Changelog

**Heads up**: this update is mostly a big cleanup and correction pass. Not much brand-new content, but a lot of bugfixes and historical accuracy work.

## New
- **Expanded divine syncretism**: for several cultures (Illyrian, Germanic, Romano-British, Gallo-Roman, Phoenician/Levantine, Egyptian, Celtiberian/Iberian), gods now display a historically grounded alternate name instead of the generic Roman one — for example Jupiter Ammon, Venus Isis, Mars Azizos, Bindus Neptunus. Every name is based on an actually attested cult name (votive inscriptions, coinage, ancient authors), not just a loose comparison.
- **Latin Revival follow-up story**: after inviting a Latin speaker to the Roman court, you can now found a scriptorium or a grand academy — each grants you a lasting personal bonus and gets some of your courtiers speaking Latin outright.
- **Hellenic patron gods**: Athena and Demeter join Zeus, Hera, Ares, Aphrodite, and Hermes as devotion options. The choice menu has been reorganized into two pages (like the existing Roman one) so all seven fit cleanly.
- **New Gallo-Roman family and given names**: Gallo-Roman dynasties no longer just borrow the same generic Roman family names as everyone else — they now draw from their own set of Latinized Gallic family names (e.g. Iūliī, Cingetorīgis, Vercassivellauniī), alongside a batch of additional authentic Gallo-Roman given names.
- **Carthaginian names rewritten as proper Punic transliterations**: dynasty names (e.g. "Azart ša Hhannō", "Bīt ša Ābar") and dozens of given names replace the old placeholder list. Also fixes a long-standing vanilla typo along the way — "Abdosi" is now correctly "Abdosir".

## Fixes & historical accuracy
- **Switching patron gods now always removes the old bonus.** Two long-standing bugs meant that switching to a new deity didn't clean up properly: worshippers of Ceres kept her bonus even after picking a different Roman god, and Hellenic worshippers kept their old deity's bonus no matter which new one they picked.
- **God names now show the correct one for each culture.** Several cultures (including Greek) were accidentally always showing a wrong or generic god name instead of their own name or the intended fallback.
- **Graeco-Egyptian faith**: its "devil" name was accidentally a Roman underworld god that had nothing to do with either pantheon — replaced with Typhon, the name Greeks in Egypt actually used for Set.
- **Roman regional sub-cultures now speak their own historical language.** Gallo-Roman, Romano-British, Romano-Germanic, Romano-Hispanic, and Afro-Roman used to all speak the exact same generic Latin despite their distinct regional ancestry — they now each speak their own regional Latin dialect (Gallo-Romance, British Latin, Moselle Romance, Hispano-Romance, African Romance). Romano-Egyptian now speaks Coptic instead of Latin, since Latin was never actually spoken there.
- **Holy sites**: roughly 40% of all holy sites had a broken "extra conversion speed" bonus or a mismatched tooltip — fixed.
- **Religions (all 15)**: dozens of broken tooltip references fixed, and a couple of religions (Sumerian and Assyrian) were missing required doctrine settings — including whether they even have a head of faith at all — that kept them from loading correctly; filled in.
- **Religion and faith descriptions rewritten** for all 15 religions, including a Roman description that was cut off mid-sentence and two religions that accidentally named the wrong high god.
- **Crypto-religion cleanup, two fixes.** Openly converting to Cultus Deorum now actually clears a lingering secret conversion instead of leaving it in place. Separately, the decision to start secretly converting no longer keeps offering itself once you're already doing so.
- **Several names now show their proper form** (with correct accents/characters) instead of a raw internal reference — including Old Irish dynasty branches, the new Gallo-Roman family and given names, and a number of Iranian, Greek, and Iberian names.
- **A few Germanic "Holy Reconquest" decisions** referenced a non-existent troop type and silently failed to raise an army — fixed.
- **Various decisions and events** that pointed to misspelled or non-existent provinces/titles (including Baghdad, Carinthia, Italy, Aquitaine) work correctly again.
- **Gaulish Empire**: now correctly shows its own name and coat of arms through the existing Kingdom of France title, instead of a separate, less robust title.
- **Dozens of tooltips corrected** (god names, opinion modifiers, court position bonuses, activities) that were previously blank or showed the wrong text.
- **Gates of Janus**: closed an exploit that allowed infinitely farming piety/prestige.
