primary_plane: 3
reads_from: [3, 4, 5]
writes_to: [3]
floor: 3
ceiling: 5
reasoning: |
  Test Runner produces structured JSON results. Operates at Plane 3 (structured data)
  because experiments need type-safe analysis. Reads research hypotheses from Plane 4-5.
