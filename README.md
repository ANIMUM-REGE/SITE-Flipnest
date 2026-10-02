# Flipnest — site

> Marketing and support pages for Flipnest: Reseller Tracker.

Static site for the app in [`APP-Flipnest`](https://github.com/ANIMUM-REGE/APP-Flipnest).
Part of the Perpetua app fleet (`VNTR-Perpetua`).

## Hosting

**No `CNAME` committed** — this site has no custom domain configured in the repo. If it is expected to be publicly reachable, verify how it is served before assuming it is.

## Pages

- `index.html`
- `privacy.html`
- `support.html`

## App status

Flipnest is ✅ READY_FOR_SALE on the App Store (v0.1.0).

> Status drifts — **re-verify rather than trust this line.**
> `VNTR-Perpetua/company/state/ops-drops/store-versions.json` (live ASC / Play / public-store reads, refreshed each publisher cycle by `PRJ-Perpetua/dashboard/store_versions.py`)
> carries the fleet-wide picture.

## Editing

Plain HTML, no build step — edit and commit. Keep privacy/support URLs stable: they
are referenced from live App Store and Play listings, and a broken support URL is a
review-rejection trigger.
