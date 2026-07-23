# COMP6441 Personal OSINT & OpSec Audit

Supporting evidence repository for the COMP6441 (Security Engineering) project:
**"Personal OSINT & OpSec Audit: Mapping My Own Digital and Physical Attack Surface"**

Author: Jinqi Chen (z5542528)

This repository contains the raw evidence referenced in the written report
(`Report-z5542528.pdf`), organised by the two phases of the project: leak
discovery (Section 4) and mitigation implementation (Section 6.1).

## Repository Structure

### `physical_osint/`
Photos and observation logs from the physical OSINT audit described in
Section 4.2, including the shared parcel collection area and building
entrance observations (Figures 5–6). Identifying details of other residents
have been masked or de-identified in accordance with Section 6.2.

### `exif_data/`
ExifTool output and source images used for the EXIF metadata comparison in
Section 4.3, comparing the original phone photo against the same photo after
being shared via WeChat (Appendix C).

### `blind_test/`
Materials and de-identified notes from the blind test conducted with
Participant R, as described in Section 4.4.

### `defense_evidence/`
Evidence of the mitigations implemented in Section 6.1, corresponding to
leaks L4 and L7:
- Parcel label destroyed before disposal (L4 mitigation)
- Camera app location services disabled (L7 mitigation)
- ExifTool metadata comparison before/after manual stripping (L7 mitigation)

## Note on Privacy

GPS coordinates, exact addresses, and other directly identifying information
have been redacted or rounded in both the report and this repository,
consistent with the ethical handling described in Section 6.2 of the report.

## Generative AI Disclosure

See Section 8 of the accompanying report for full disclosure of Generative AI
tool usage in this project.
