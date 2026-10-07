# Evidence Architecture

## E01 — Case Intake
Initial incident report and authorized scope.

## E02 — Evidence Manifest
SHA-256 validation records.

## E03 — CDR Dataset
Fictional call-detail records containing call identifiers, endpoints, start/end times and durations.

## E04 — SIP Signaling
Synthetic signaling records for selected calls.

## E05 — PBX Routing
Synthetic routing and extension-mapping records.

## E06 — PBX Audit
Administrative configuration-change history.

## E07 — Authentication
Synthetic authentication records associated with administrative access.

## E08 — Network Evidence
Sanitized/synthetic flow and packet-analysis summaries; no real communications.

## E09 — Time Sources
Clock-offset and time-normalization evidence.

## E10 — Case Notes
Fictional witness statements and analyst intake notes.

Every final artifact must be documented in provenance.csv and validated by SHA-256 before release.
