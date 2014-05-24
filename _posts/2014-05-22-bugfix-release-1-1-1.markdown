---
title:  "Croggle 1.1.1 bugfix release"
date:   2014-05-22 14:18:44
categories: release version 1.1.1 notes
---

This is just a small anouncement of the freshly released Croggle version 1.1.1.
There is nothing new in this version, only bug fixes/stability improvements.

### Release notes:

The following issues have been fixed:

* Remove illegal usage of 'f' indicators for float literals in shaders (e.g. 1.f).
  This caused the NVidia driver on a Macbook to throw compile errors, and probably a Galaxy Tab 3, too.
* Fix for package 2/level 2, which was impossible to solve due to a change of the evaluation rules introduced in 1.1.

Stay tuned for more news coming up in the next days.
