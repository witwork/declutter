# Changelog

All notable changes to Declutter will be documented in this file.

## [1.0.0] - 2024-12-17

### Added
- Initial release
- Duplicate file detection using xxHash64
- Similar image finder using perceptual hashing (dHash)
- AI-powered scene matching using Apple Vision FeaturePrint
- Large file finder
- Cache cleaner for system and app caches
- Statistics dashboard with scan history
- Safe deletion (always moves to Trash)
- Export deletion plan (JSON/CSV)
- Thumbnail caching for fast previews
- Multiple keep strategies (oldest, newest, largest, smallest)
- Settings persistence
- Firebase Analytics integration
- Professional logging system

### Security
- Code signed with Developer ID
- Notarized by Apple
- Privacy Manifest included
