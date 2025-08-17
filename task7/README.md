Suspicious/Unnecessary Extensions Removed:

LI Prospect Finder — B2B lead-scraping tools typically request broad permissions and may process sensitive page data. Privacy risk if not essential → Removed.

ZED: Zoom Easy Downloader — “Downloader” extensions often inject scripts into video sites and can have mixed reputations. Not required for core Zoom use → Removed.

Monica: ChatGPT AI Assistant — AI assistant extensions inject content scripts widely and contact external APIs. If not essential for daily work, safer to remove to reduce data exposure on arbitrary sites → Removed.

Pop-up Blocker for Chrome (Poper Blocker) — Redundant because AdBlock already handles most pop-ups; extra blockers increase attack surface → Removed.

Nature NewTab Extension — New tab changers commonly request “read/change data on all sites” and alter default settings; low trust value → Removed.

Safe/Reasonable Extensions Kept
AdBlock — Reputable; keep only one blocker. Set Site access to “On click” or “On specific sites” if possible.

Google Docs Offline — Published by Google; keep if offline editing is needed. Otherwise, remove to reduce surface area.

Wappalyzer — Useful for tech profiling; enable only when needed and restrict Site access to “On click.”

Netcraft Extension — Phishing/malware intelligence; helpful for security awareness. Keep updated.

Galaxy Wallpaper (optional) — Cosmetic; not a security risk but unnecessary. Consider removing to keep the profile lean.

Additional hardening applied
Limited Site access: For kept extensions, changed permissions to “On click” or “On specific sites” where available.

Disabled in sensitive sessions: Avoid running nonessential extensions during banking, email, or admin work.

Version and publisher verified: Confirmed official listings and recent update activity before retaining.

Key Learnings:
Install only from known, reputable developers with clear privacy policies and recent updates.

Avoid redundancy (multiple ad/pop-up blockers). Each extra extension expands the attack surface.

Audit extensions monthly; remove anything unused or that requests broad permissions without necessity.

Restrict permissions using “On click” or per-site access rather than “On all sites.”