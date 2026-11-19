# Changelog

All notable changes to ForgottenSaves are listed here, newest first.

## 0.1.1 (2026-11-19)

### Fixed
- Saving posts from **Explore** sometimes recorded the wrong author, thumbnail or link, because details of a neighbouring post in the grid could be picked up. The extension now reads details only from the post that was actually opened.
- Post details collected from the page are now checked against the post that Instagram reports as saved. If they don't match, they are discarded instead of being stored.
- The saved link now always comes from the saved post itself, so it can't point to a different post.
- **Videos** now get a thumbnail: the video's cover image when there is one, otherwise a single frame taken from the video.
- Older entries with a mismatched link are repaired automatically when you open your list.

## 0.1.0 (2026-11-10)

### Added
- First public release.
- Records the date and time of every post you save on instagram.com.
- Browse your saves by month and year, and search by author or caption.
- Keeps a small thumbnail of each post.
- Marks posts you later removed from your saved list.
- Back up and restore your list as a JSON file.
