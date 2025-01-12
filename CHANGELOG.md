# Change Log

## [1.4] - 2019-08-23
- Fix compliation errors and update all builds with latest Qt (5.13)
- Fix Config button command
- Further fix and tweak progress display. Add ETA and Total Size fields
- Fix remotes icons display
- Add sftp icon
- Fix progress display for rclone > 1.37 (by DinCahill)
- Add a Public Link option to the right-click menu (by DinCahill)
- Add preference: Show hidden files and folders (by DinCahill)
- Add Mega icon (by DinCahill)
- Refresh when Shared is toggled (by DinCahill)
- Disable Upload button for Shared (by DinCahill)
- Support for shared Google Drive files. Enable the checkbox when you open a remote, and all rclone commands will be passed --drive-shared-with-me (by DinCahill)
- Set cache mode for mounts (by DinCahill)
- Fixed missing leading / in path (required for some SFTP servers) (by DinCahill)


## [1.2] - 2017-03-11
- Calculate size of folders, issue #4
- Copy transfer command to clipboard, issue #20
- Support custom .rclone.conf location, #21
- Export list of files, issue #27
- Bugfix for folder refresh not working after rename, issue #30
- Remember empty text fields in transfer dialog, issue #32
- Error message when too old rclone version is selected
- Support portable mode, issue #28
- Create .deb packages, issue #26

## [1.1] - 2017-01-31
- Added `--transfer` option in UI, issue #1
- Supports encrypted `.rclone.conf` configuration file, issue #2
- Fixed crash when canceling active stream
- Added ETA tooltip for transfer progress bars
- Allow to specify extra arguments for rclone, issue #7
- Fix for browsing Hubic remotes, issue #10
- Support high-dpi mode for macOS

## [1.0.0] - 2017-01-29
- Allows to browse and modify any rclone remote, including encrypted ones
- Uses same configuration file as rclone, no extra configuration required
- Simultaneously navigate multiple repositories in separate tabs
- Lists files hierarchically with file name, size and modify date
- All rclone commands are executed asynchronously, no freezing GUI
- File hierarchy is lazily cached in memory, for faster traversal of folders
- Allows to upload, download, create new folders, rename or delete files and folders
- Can process multiple upload or download jobs in background
- Drag & drop support for dragging files from local file explorer for uploading
- Streaming media files for playback in player like mpv or similar
- Mount and unmount folders on macOS and GNU/Linux
- Optionally minimizes to tray, with notifications when upload/download finishes

[1.4]: https://github.com/kapitainsky/RcloneBrowser/releases/tag/1.4
[1.2]: https://github.com/mmozeiko/RcloneBrowser/releases/tag/1.2
[1.1]: https://github.com/mmozeiko/RcloneBrowser/releases/tag/1.1
[1.0.0]: https://github.com/mmozeiko/RcloneBrowser/releases/tag/1.0.0
