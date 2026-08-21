# AFDCS Honour Guard Digital Contact Card

Standalone, mobile-first contact site for the Airdrie Fire Department Honour Guard Executive Board.

The repository root is the complete static website. It provides a shared board email, an organization vCard, and direct call, email, text, and vCard actions for each executive member. It has no build step, database, credentials, analytics, or visitor-data collection.

## Public address

`https://hgcard.apffa.ca`

The repository includes a `CNAME` file for this custom domain and a GitHub Actions workflow that publishes the repository root through GitHub Pages.

## Local preview

From the repository root, run:

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Photo status

Approved Honour Guard portraits are included for all four executive members.
