# Office-hours links

- ECON 516: https://carlosmolinaguerra.github.io/office-hours/516/
- ECON 221: https://carlosmolinaguerra.github.io/office-hours/221/

The course links open the booking calendar configured in `_data/office_hours.yml`. Both courses can use the same destination or separate destinations. No paid hosting, custom domain, or link-shortener subscription is required.

## Change a booking destination

1. Sign in to GitHub and open [the destination file](https://github.com/carlosmolinaguerra/carlosmolinaguerra.github.io/edit/main/_data/office_hours.yml).
2. Replace the URL beside `econ221` or `econ516`. Keep the quotation marks and use the full public booking URL beginning with `https://`. Do not use a private admin/settings URL.
3. Select **Commit changes**, enter a short description, and commit directly to `main`.
4. Wait for the GitHub Pages deployment to finish in the repository’s **Actions** tab.
5. Open each student link in a fresh tab and confirm it reaches the intended calendar. If an old destination appears briefly, reload the original GitHub Pages address after deployment finishes.

Students keep using the same GitHub links when a destination changes. Keep this repository, account name, and the course paths unchanged to preserve those links. Changes here do not update old Calendly links already distributed.

Availability, meeting length, location, calendar conflict checks, and existing appointments remain managed in the booking app. Redirects only control which booking page students open.

## Files

- `_data/office_hours.yml`: editable destination URLs.
- `_layouts/office-hours-redirect.html`: shared automatic redirect with a clickable fallback.
- `office-hours/516/index.html`: the permanent ECON 516 address.
- `office-hours/221/index.html`: the permanent ECON 221 address.

The existing home page and personal website redirect are unchanged.
