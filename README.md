# FORM mobile training journal

Installable offline training journal, published through GitHub Pages. Workout data lives in a separate private database behind an authenticated API. No user records, photos, access keys or server credentials are included in this repository.

On iPhone: open the private access link in Safari, choose Share → Add to Home Screen, then launch once online and wait for the offline-ready indicator. Record sets offline; reopen online and use Sync before asking for a remote review. Closed-app background sync is not guaranteed. Export backups regularly.

The application uses IndexedDB, a local mutation queue, optimistic cloud revisions and conflict preservation. API responses are never cached by the service worker.
