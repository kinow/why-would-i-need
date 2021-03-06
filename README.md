# why-would-i-need

Why would I need ... ?

A repository containing examples that answer questions like "Why would I need backup?",
"Why would I need pentest?", or "Why would I need unit tests?".


## Development

### Use the latest stable JVM? or Know what is new in the new JVM?

* Thread dumps before 1.6 did not include lock information
    - https://helpx.adobe.com/experience-manager/kb/TakeThreadDump.html
* Java 1.7's Double#parseDouble is synchronized, and was fixed in 1.8
    - http://dalelane.co.uk/blog/?p=2936
    - http://bugs.java.com/view_bug.do?bug_id=7032154

## Infrastructure

### Backup

* In 2008 Gentoo Wiki died, and they did not have a backup
    - https://forums.gentoo.org/viewtopic-t-725207-start-0.html
    - https://www.reddit.com/r/linux/comments/4ys03i/why_did_gentoo_peak_in_popularity_in_2005_then/d6q3flh

### Same OS / hardware

* TripAdvisor had issues in Postgres due to different versions of glibc. They were upgrading the hardware, so some servers had slightly different glibc versions. This caused corrupted indices, which resulted in invalid join.
    - https://www.postgresql.org/message-id/flat/BA6132ED-1F6B-4A0B-AC22-81278F5AB81E%40tripadvisor.com

## Data

### Data Sharing

* GIS data for Christchurch got a lot better after the big earthquake in 2011
    - http://www.linz.govt.nz/news/2012-05/christchurch-plugfest-2012
