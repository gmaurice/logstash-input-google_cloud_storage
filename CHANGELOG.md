## 0.12.0

- Add the ability to archive log files in another bucket
  it helps to improve performance when plugin is looking for
  log files to process.

## 0.11.0

- Change gzip file detection to use mime type instead of extension

## 0.10.0

- Updated JAR dependencies.
- Changed the way lines were being read to not strip the included line endings.

## 0.9.0

- Initial release
- File inclusion/exclusion by 
  - regex
  - processed database
  - metadata key
- Authenticate using Application Default Credentials or JSON keys
- Read GZipped files
