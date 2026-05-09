---
name: neo-mission
status: active
---

# Neo — Active Mission

## Mission
Find an iPhone 17 phone stand on Printables or Thingiverse. Download it, validate mesh quality with Blender, check if it physically fits an iPhone 17 Pro Max (~163 × 77.6 × 8.25 mm), then upload to Google Drive.

## Status
`in_progress`

## Progress
- [ ] Find iPhone 17 phone stand model
- [ ] Download model STL/3MF
- [ ] Run Blender mesh validation (triangles, non-manifold edges, dimensions)
- [ ] Verify iPhone 17 Pro Max physical fit (~163 × 77.6 × 8.25 mm)
- [ ] Upload to Google Drive
- [ ] Report results

## iPhone 17 Dimensions (for fit check)
| Model | Height | Width | Depth |
|-------|--------|-------|-------|
| iPhone 17 Pro Max | ~163 mm | ~77.6 mm | ~8.25 mm |
| iPhone 17 Pro | ~147.6 mm | ~71.5 mm | ~8.25 mm |
| iPhone 17 | ~163 mm | ~77.6 mm | ~8.25 mm |

## Quality Thresholds
| Rating | Triangles | Notes |
|--------|-----------|-------|
| Excellent | 100K–500K | Print-tested, good detail |
| Good | 20K–100K | Standard resolution |
| Acceptable | 5K–20K | Simple prints, functional |
| Poor | <5K | Too blocky |
| Oversampled | >2M | May cause slicing issues |

## Issues / Blockers
None.

## Key Decisions
- Blender validation on Aarz's local machine via `blender-start.sh`
- Composio Browser Tool for downloads
- Google Drive for storage

## Started
2026-05-09
