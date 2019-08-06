Desktop Cleaner
===

A Bitbar plugin for cleaning desktop

# Configure

Config file locate at `~/.desktop_cleaner`

```yaml
---
backup_dir: '/Volumes/GoogleDrive/My Drive/Desktop'
threshold_days: 7
archive_extnames:
  - ".app"
  - ".playground"
```

Example config means

- Desktop files backup to `/Volumes/GoogleDrive/My Drive/Desktop` when it updated at 7 days ago or older.
- Archive(zip) it when extname is `.app` or `.playground`.

# License

```
Copyright 2019 tomorrowkey

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
