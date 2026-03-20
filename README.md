# BoardGame Loans for WordPress

A complete lightweight solution to manage board game loans, rentals, and waitlists for associations and ludotheques, built directly as a WordPress Plugin.

## 🎲 Features

- **Check-in / Check-out** board games to registered users or external guests.
- **Copy Tracking:** Track multiple identical physical copies using specific "Copy Numbers" and "Internal Codes".
- **Waitlist System:** Integrated waitlist and queue system with specific statuses (`Waitlist`, `Available for Pickup`) to reserve games safely. Visual alerts warn the librarian if a returned game is reserved for someone else!
- **Admin Dashboard:** A detailed back-office with search, complex filters, and color-coded statuses (`Open`, `Returned`, `Overdue`).
- **Extensions:** Extend loans with a single click by adding predefined extra days.
- **Public Shortcodes:** Use customizable shortcodes like `[bg_loans_list]` and `[bg_loans_waitlist]` to showcase active loans and queue on any front-end page. Parameters are available to hide dates or show specific statuses.
- **Internationalization:** Full WordPress i18n support. Ready to be localized in any language.

## ⚙️ Installation

1. Upload the `boardgame-loans` directory to your `/wp-content/plugins/` directory.
2. Activate the plugin through the **Plugins** menu in WordPress.
3. Access the **BoardGame Loans** menu in your admin dashboard to configure Settings and start registering loans.
4. Place the `[bg_loans_list]` shortcode on any public page to display the current rentals.

## ❓ FAQ

**Does it integrate with TablePress or BGG?**
Yes, you can enable "Advanced Mode" in the Settings to reveal a Reference field specifically designed to link your physical games to a main catalogue (like a TablePress list ID or a BGG reference).

**Is the waitlist automatic?**
When returning a game, the plugin checks if there is someone in the Waitlist for that specific physical copy. If there is, it warns the administrator with a visual badge so you can manually put the game "Under the counter" and call the next person in line.

## 📝 License

This project is licensed under the GPL-2.0 or later license - see the `license.txt` file for details.
