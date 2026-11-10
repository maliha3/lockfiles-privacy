Confirmed — and it's B, not A.

The live page still has the old text. You never pasted the update into GitHub; that's the whole discrepancy. Nothing else is wrong.

Do not do fix A. I checked build 7's binary directly: grep -c 'Send crash reports' returns 0. There is no crash-reporting code, no reporting SDK, and no HTTP client in the app. Declaring "Diagnostics → Crash Data" would tell Apple you collect data your app is physically incapable of collecting. That's a false privacy declaration — worse than the mismatch it's trying to fix, and it would be wrong in a way that's hard to walk back.
