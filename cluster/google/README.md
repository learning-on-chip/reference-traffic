# Google

The directory contains traces extracted from Google’s [cluster-usage data][1].

## submit.sqlite3

The database contains the time stamps of the `SUBMIT` events found in the
`job_events` table. Two time moments have been excluded, namely, 0 (before the
beginning of the trace window) and 2<sup>63</sup> - 1 (after the end of the
trace window).

[1]: https://github.com/google/cluster-data
